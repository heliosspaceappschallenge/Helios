# Helios
Project Helios was created to attend the challange "You Are My Sunshine" from Nasa space apps Hackaton.

The app monitors solar irradiance and estipulates energy generation based on user location, or any other location selected by the user. 

Users can input the value from energy bills, and the total energy that was used last month to calculate how much money they can save per solar plate installed on the house, depending on the sunlight incidence in the location.

Graphics can also be displayed with historical info about irradiance based on period selected by the user.

# So, lets take a tour on the app!

Splash Page:

![Splash page](https://user-images.githubusercontent.com/91791747/135771458-92389d6c-389e-4817-8a6b-5720a1cf7857.png)

The splash page pops up when you first open the app. Its just a nice display of our logo, with and awesome photo background provided by NASA.

Location Page:

![Location Page](https://user-images.githubusercontent.com/91791747/135771494-daa02ad2-1cf9-4e05-9b12-a1d93d7dd3ee.png)

This page is where you make the selection that fits you the most.
If you want to "Use your location", the app will get your coordinates from your phone's GPS to determine where you are, and uses that to make the measurings.

If you prefer to "Select your region", you will be redirected to the "Select you region" Page, that looks like the following:

![Region Selection Page](https://user-images.githubusercontent.com/91791747/135771560-4dc84982-7170-4ff0-96c1-4e58a22338bc.png)

There you can select your country: 
![Region Selection Page-CountryDropdown](https://user-images.githubusercontent.com/91791747/135771576-6bee07f3-8bd6-4768-a7ac-9b46eede7d69.png)

And the region down below.

After you choose one of the localization methods, the app will navigate to its Home page:

![Home Page](https://user-images.githubusercontent.com/91791747/135771593-86596959-7602-44dd-8b84-228cebdc56cf.png)

In the Home Page we have plenty of information. First thing on screen, up on the appbar, is the location you selected, or provided by your GPS.
On the body of the page the first information is the Irradiance on the current user location. That monitor is updated from time to time to keep you informed.

![Home Page Irradiance](https://user-images.githubusercontent.com/91791747/135772206-91de583d-ddee-45de-ae0f-d5ee7078276c.png)

Below the Irradiance monitor we have the Energy generation monitor. It calculates how many energy is being generated with 1 solar plate, based on current irradiation os the users location.

![Home Page Energy](https://user-images.githubusercontent.com/91791747/135772211-53a068ce-bcaf-4996-971b-094fd3741b32.png)

As we continue to go down, we will find a chart with the expected sunlight time for Each season, based on data collected from previous years.

![Home PageSeasons](https://user-images.githubusercontent.com/91791747/135772219-cb864711-57be-4216-ab8c-c6da1a6325f3.png)

And last but not least, we have 3 indicators: Temperature, Humidity and Wind speed, just to let you know.

![Home Page Measurings](https://user-images.githubusercontent.com/91791747/135772221-1edbfbca-f408-4578-891d-48c49d52e429.png)

The next page is reachable by sliding the screen to the side. We called it the Energy Consumption Page:

![Energy Consumption Page](https://user-images.githubusercontent.com/91791747/135771751-bca7f158-7dac-4ec6-910c-91381d4b5fa7.png)

From there, the user can input the energy consumption from last month for example, in kW/h. and the total he paid for that usage.
With this data we can calculate the average cost for each kW, and display how much he would save per solar plate installed on his house. All of this considering the user current location, and the energy generated for that specific solar incidence.

These data are displayed on the Energy Consumption Page 2:

![Energy Consumption Page 2](https://user-images.githubusercontent.com/91791747/135771876-1beb7ea9-b8e8-4617-a37d-5532e379fe67.png).

From any of the 3 previous pages, we can click the chart icon to go to the Graphics page:

![Graphics Page](https://user-images.githubusercontent.com/91791747/135771893-4ab975f7-7fc6-477a-bd2c-2312d3ff1bb8.png)

That page will shows data from 1 Year behind, and that can be changed by the user depending on the period selected.
It shows graphics for UVA and UVB Irradiance.

All the data used to create this graphics were provided by the NASA POWER API, using the archives created by NASA DATA ACESS VIEW.

# Thats all folks!

You can find the prototype and preview on the following link: https://www.figma.com/community/file/1026591561762784769
Thanks for your time, and helps us make the planet more susteinable by sharing information of renewable energy!
