# Joe’s Seaside Plotting Python Project
## SOLUTION *Hosted at seaside-pass-lat-long-plot.tylermneher.me*
## seaside-pass-lat-long-plot.neherdata.com

<b>Goal:</b> Using the latitude and longitude pairs from the ‘location’ key in the `pass.json` file, accomplish the following:

- Create a dataframe using the python library `Pandas` and load the latitude and longitude data pairs into columns labeled `latitude` and `longitude`, respectively. 
- Using a reverse geocoding api like [positionstack](https://positionstack.com/documentation#reverse_geocoding) (there are tons of them out there, most require an api key which you sign up for), create columns in your dataframe labeled `address`, `city`, `state`, and `country` and populate each latitude and longitude with its respective `address`, `city`, `state`, and `country` data.
- Using either the python library [Folium](https://python-visualization.github.io/folium/latest/), [GeoPandas](https://geopandas.org/en/stable/), or (preferred) [Plotly](https://plotly.com/python/), render a map that plots each of the latitude and longitude data pairs.
- Export the rendered map as both a PNG image file named `map.png` and as a HTML file named `index.html` - commit and push both files to the repository on GitHub.
- Using GitHub Actions, publish the `index.html` file to GitHub Pages as a static HTML site.
- Enable the setting to secure the GitHub Pages site with HTTPS.
- Have the GitHub Pages site resolve to the custom domain `seaside-pass-lat-long-plot.neherdata.com` from the GitHub Pages settings panel. I’ve already configured the DNS on the registrar side to work with the domain, you just need to enable it.
- THEN YOU’RE DONE!

* Pro Tip # 1 - create a conda environment to work inside of and install your python libraries in.
* Pro Tip # 2 - use a Jupyter notebook. You’ll install it as a python library *after you’ve created and activated your Conda environment*.