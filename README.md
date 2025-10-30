# g328_async_GeoJSON
This repository is for Lab 3 in UW's GEOG 328 course where we will work on asynchronous GeoJSON data loading and visualization.

### earthquake.html
The Lab begins with an example in the _earthquake.html_ file. This file loads in a background map, as well as a table that aligns with data points located on the background map, showing earthquake locations within Japan. The earthquake data comes from the _earthquake.geojson_, while the counties of Japan are added with the _japan.json_, both of which are located within the assets folder. 

### index.html
The deliverable for this Lab is the _index.html_ file, which contains my own attempt of asynchronous GeoJSON data loading and visualization. For this assignment, I chose to map the universities in Washington State using the _WA_County_Boundaries.geojson_ from the [Washington State Department of Natural Resources](https://data-wadnr.opendata.arcgis.com/datasets/wa-county-boundaries/explore). I created the _wa_uni.geojson_ using [geojson.io](https://geojson.io/#new&map=2/0/20), and public data from universities across Washington. 

When accessing _index.html_ you'll find a global map, centered on Washington State. You'll see the Washington counties shown in grey, while blue points mark each university location. In the sidebar on the right, there is a table listing each university, when they were founded, whether they are public or private, their approximate student population (approximate as it does vary by year and term), and the name of the county in which the university is located. You are able to sort the table by size (student population) by clicking the button just above it.
