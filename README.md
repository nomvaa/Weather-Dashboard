<B>Server-Side APIs: Weather Dashboard</b><br>
Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. Your challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.
Use the OpenWeather API to retrieve weather data for cities. The documentation includes a section called "How to start" that will provide basic setup and usage instructions. Use localStorage to store any persistent data.
<BR><BR>
  <B>User Story</b><br>
AS A traveler<br>
I WANT to see the weather outlook for multiple cities<Br>
SO THAT I can plan a trip accordingly<br>
<BR><BR>
  <B>Acceptance Criteria</b><BR>
GIVEN a weather dashboard with form inputs<BR>
WHEN I search for a city<br>
THEN I am presented with current and future conditions for that city and that city is added to the search history<br>
WHEN I view current weather conditions for that city<Br>
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index<Br>
WHEN I view the UV index<br>
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe<br>
WHEN I view future weather conditions for that city<br>
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity<br>
WHEN I click on a city in the search history<BR>
THEN I am again presented with current and future conditions for that city<Br>
WHEN I open the weather dashboard<br>
THEN I am presented with the last searched city forecast<br>
