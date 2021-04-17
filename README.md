# World_Weather_Analysis

## Purpose:
Collecting, Analyzing and Visualizing **PlanMyTrip** data to provide executable code to make trip recommendations to clients based off of their weather preferences


<img width="550" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/78561980/115102889-8042f980-9f13-11eb-940f-5dd60d43d67b.png">

## Collecting Data:
Using Matplotlib and NumPy, we generated 2000 random latitudes and longitudes, then selected the closest city for each point using citipy. We then ran an API request for each city and parsed the JSON data needed to compare weather stats for each location.

<img width="645" alt="Screen Shot 2021-04-16 at 11 29 28 PM" src="https://user-images.githubusercontent.com/78561980/115103085-b5038080-9f14-11eb-99a8-ba2c3c23e5f2.png">


<img width="814" alt="Screen Shot 2021-04-17 at 12 31 27 AM" src="https://user-images.githubusercontent.com/78561980/115103040-6950d700-9f14-11eb-86df-b7fd2afa549f.png">

## Analysis and Visualization:
Once we reteived the data, we created a DataFrame from the cities csv file. We then allowed the customer to input minimum and maximum temperatures they would prefer, and created a new DataFrame that met those parameters. Next, using Google Maps API, we identified a hotel in each city.

<img width="1440" alt="Screen Shot 2021-04-17 at 12 30 57 AM" src="https://user-images.githubusercontent.com/78561980/115103054-77065c80-9f14-11eb-94a8-2f91a7d7c7ed.png">


## Results:
Ultimately, the weather analysis allowed us to create an easy-to-use vacation planning system for **PlanMyTrip** that matches the clients weather preferences. 



<img width="818" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/78561980/115102866-5f7aa400-9f13-11eb-8976-ea37e5d702a2.png">
<img width="1060" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/78561980/115102928-aff20180-9f13-11eb-9c74-e4312136aca9.png">
