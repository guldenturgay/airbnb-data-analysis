## Airbnb Listing Prices and Venues Data Analysis of Seattle

The Capstone_the_battle_of_neighborhoods.ipynb file is the capstone project of IBM Data Science Professional Certificate program. In this project,

### Data
- The data was sourced from [Inside Airbnb](http://insideairbnb.com/get-the-data.html) website and the date that data was compiled on the website is 03/17/20. The attributes used in the analysis are : 
    - `neighbourhood` -  Neighborhood names of each Airbnb listing in Seattle
    - `latitude` - Latitudes of each Airbnb listing
    - `longitude` - Longitudes of each Airbnb listing
    - `price` - Nightly prices of each Airbnb listing in USD at given date
    

- [Foursquare API](https://developer.foursquare.com/) was used to get the top venues of given neighborhood in city of Seattle.

- [Seattle neighborhood boundaries json](https://github.com/seattleio/seattle-boundaries-data/blob/master/data/neighborhoods.geojson) data was utilized to get the neighborhood boundaries.

### Notes
This project uses Foursquare private API keys to fetch data from Foursquare API. In order to fetch the data you will need to get your own Foursquare API keys and copy them into .env file __(you can rename .env.example file by removing .example part)__. 

### To show the notebook with visualizations

Since GitHub does not render Jupyter Notebook, you can use the following link to see the visualizations.
https://nbviewer.jupyter.org/github/guldenturgay/Coursera_Capstone/blob/master/Capstone_the_battle_of_neighborhoods.ipynb
