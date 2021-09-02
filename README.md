# Finding-New-Potential-Restaurant-Locations
Goal of project is to filter and analyze data to find potential locations for new restaurants in Downtown Vancouver. Initial data will be a cleaned dataset of OSM data with geographic tags and descriptions. A function for determining the attractiveness for a potential location based on the relative distance between location and other competitors/attractions will be created. Interactive maps will also be used to better visualize the results.


# HOW TO USE CODE:

1. Need to install folium, sklearn and seaborn packages
2. Obtain OSM data and use the cleaning_data.ipynb code to clean data into a file named output.csv (original OSM data used from amenities-vancouver.json)
3. finding-attractive-locactions.ipynb finds locations based off a generated set of points along a diagonal line while finding-attractive-locactions-with_grid_search.ipynb generates points in a grid-like manner
