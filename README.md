# World_Weather_Analysis

**Utilizing python modules and API's to retrieve and analyze data to provide real-time suggestions on vacation trips.**

## **Overview**

**Creating python script for a hypothetical betaApp meant to provide recommendations for hotel/lodging suggestions for a comapny based on user_end provided criteria.**

**[Weather_Database](Weather_Database)**

- **The [numpy module](https://github.com/numpy/numpy) was used to generate 2,000 latitudes and longitude combinations**

- **The [Citypy](https://github.com/wingchen/citipy) module was used to retrieve the nearst city latitude/longitude combinations**

- **The [Open Weather Map API](https://openweathermap.org/api) was also used to retrieve up-tp-date weather data for the provided cities**

**[Vacation_Search](Vacation_Search)**

- **The weather data from the [Weather_Database](Weather_Database) is parsed, formattedm and visualized with Google Maps API's**

- **The focus of these visualizations are markers and up to date pop-up markers with information dispalyed by category**

**[Vacation_Itinerary](Vaction_Itinerary)**

- **The same data form the Vacation_Search is further filtered down by a "trip/itinerary" criteria.**

- **The data is then visualized using Google API's.**

![map (1)](https://user-images.githubusercontent.com/91576834/154822272-973bdbcd-e10c-44db-b7e8-bb0de442f694.png)

## **Resources**

- **Software: Python, JupyterLab**

- ***[Google Cloud Platform](https://cloud.google.com/docs/?hl=en_US#section-6)***

- ***[Google Maps API](https://developers.google.com/maps)***

- ***[OpenWeatherMap API's](https://openweathermap.org/api)***

