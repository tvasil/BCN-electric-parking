## Barcelona mobility projects

This repo holds two small projects I did playing around with data from the [Open Data Barcelona](https://www.google.com/search?q=barcelona+open+data&oq=barcelona+open+data&aqs=chrome..69i57j0l5.2771j0j7&sourceid=chrome&ie=UTF-8) page. 

The two projects are: 

### [Electric car charging](https://github.com/tvasil/BCN-electric-parking/tree/master/electric_car_charging)
#### What has been done
- Parsing of the current status of electric car and motorcycle charging sports around Barcelona from the API
- Generating an HTML map with all the spots, descriptions, using `folium`

#### TODO
- Turn the notebook into a Python script and run with a cronjob every 5 minutes to show most current availability status
- Host the HTML visualization on a public server

[### **Traffic accidents**](https://github.com/tvasil/BCN-electric-parking/tree/master/traffic_accidents)
#### What has been done
- Going through all accidents that occured in Barcelona in 2017 to uncover spatial and temporal patterns
- EDA with visualizations and some statistical analysis

#### TODO
- Incorporate more years of data and build a time-series prediction on the volumes of traffic accidents
