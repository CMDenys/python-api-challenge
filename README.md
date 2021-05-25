# python-api-challenge

<h1>Part I - WeatherPy</h1>

To better understand weather patterns in various cities across the world, a representative model was created using Python libraries and the OpenWeatherMap API to visualize the weather of 500+ cities across the world of varying distance from the equator. 

To create a list of cities, NumPy was used to create a set of random latitude and longitude combinations.  Once the lat/lng coordinates were produced, citipy was used to identify the nearest city to each coordinate.

<p align="center">
  <img src="images/1_generate_cities.png" width="600">
</p>

Next, a weather check on each city was conducting using a series of successive API calls.  Included was a print log of each city as it was being processed (with the city number and city name).

<p float="left" align="center">
  <img src="images/2_perform_apis.png" width="400"/>
  <img src="images/3_citylist.png" margin-top="0" width="400"/> 
</p>

Data was then converted into a data frame.
<p align="center">
  <img src="images/4_dataframe.png" width="400"/>
</p>

To visual what the data was telling us, a series of scatter plots to showcase the following relationships:

<p float="left" align="center">
  <img src="images/5_img1.png" width="400"/>
  <img src="images/6_img2.png" width="400"/> 
</p>
<p float="left" align="center">
  <img src="images/7_img3.png" width="400"/>
  <img src="images/8_img4.png" width="400"/> 
</p>



