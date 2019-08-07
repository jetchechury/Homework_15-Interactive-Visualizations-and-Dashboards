# Interactive Dashboard - Biodiversity

## Background

The task was to build an interactive dashboard to explore the Belly Button Biodiversity DataSet.

## The Process

Plotly.js was used to build interactive charts for the dashboard. A pie chart that used data from the samples route (`/samples/<sample>`) was created to display the top 10 samples. A bubble chart was also created that used data from the samples route (`/samples/<sample>`) to display each sample.  Lastly, a card was used to display each key/value pair from the sample metadata. 

Upon selecting a sample value, all of the plots are updated to reflect the data associated with that sample.

The Flask app was deployed to Heroku and can be found at: https://belly-button-biodiversity-jetc.herokuapp.com/
