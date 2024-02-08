# Weather Or Not

Weather Or Not - Hackathon Project #2 - is a Front-end Web Application that provides Users with live weather data and forecast data. It demonstrates manipulating DOM elements with JSON from an open API. It demonstrates core Javascript that is uses to add functionality to the site. In addition, it also utilises core bootstrap, css, and HTML in regards to design.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/142e1d42-da4d-4aba-a683-342923bc8e1e" style="width:70%;">

# Contents

1. [UX Design](#ux-design)
2. [User Stories](#user-stories)
3. [Features](#features)
4. [Testing](#testing)
5. [Deployment](#deployment)
6. [Credits/Technologies Used](#credits)
7. [Future Features](#future-features)

<a id="ux-design"></a>
## UX Design

### Home Page Wireframe Design
<img src="assets/readmePhotos/wireframeLaptop.png" style="width:80%;">
<img src="assets/readmePhotos/wireframePhone.png" style="width:40%;">



<a id="user-stories"></a>
## User Stories

- As a User, I can search for the weather using a city name
  - There is a clearly visible search bar for the user to enter their desired city, and an assocaited search button. (They can also press enter to search)
- As a User, I can search for the weather using my current location
  - There is a "Use my location" button that will provide a pop up asking the user to allow the use of their devices geolocation
- As a User, I can see the forcasted weather for my searched city or my location for 5 days and the current day.
  - There is a 
- 
  - 
- 
  - 
- 
  - 

As can be seen from the project board, the completed sprint was composed of 17 separate items. Having used the MoSCoW approach to prioritisation, 10 were classified as "Must-Have" making up less than 60% of the tasks as recommended. The rest of the first sprint was made up of "Should-Have", "Could-Have" and bug fixes.
The project backlog contains several "Could-Have" user stories and two "Won't Have" items.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/cea3c3e8-7df9-4fb9-8418-7d43bef02a95" style="width:100%;">

<a id="features"></a>
## Features

- **Search Bar**
The User can instead, enter their own custom location into the Input. Once they click search, the weather API will return weather data for that location.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/6278e0e9-371f-4190-8527-9988f7a4d5c4" style="width:70%;">

- **User Location Button**
The User can click the current location button which uses the Geolocation API, the browser will then ask the User permission to access their device's location. Once that is accepted, the weather results shown will be for that location - using latitude and longitude of the User's device.

- **Live Weather**
When the User submits a search - current or custom location - the app will display a live weather container. This live weather will have key information about the location. This includes Temperature, Humidity, Wind Speed, Sunrise, Sunset and a description of the weather e.g Cloudy.

- **Five Day Forecast**
In addition to live weather, the User will receive Forecasted Weather for that location. It will provide the User with the next 6 days of weather information - combined with live weather, totals to 7 day weather data. The Forecasted Weather prediction will have minimal but crucial information - date, temperature and weather description.

- **Footer?**




<a id="testing"></a>
## Testing

### Manual Testing
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/c0e89b6c-78a8-42a2-8b48-bc6b39ac513e" style="width:100%;">

### Lighthouse
The site was tested using Lighthouse with the following results:
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/ed031055-ecac-4a09-93e0-d9710011e550" style="width:70%;">


### Responsive Testing

Alongside the built in Bootstrap responsive CSS, media queries were used throughout our own CSS to provide a consistent user experience. Chrome dev tools were used frequently to test the site at standard screen sizes and the site was manually viewed on laptops, tablets and phones.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/216eaf29-7853-4fe9-b3e1-4ed9ff705c84" style="width:70%;">


### Browser Compatibility
The site was tested on the following browsers:
- Chrome
- Firefox
- Edge
- Opera
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/2104c398-4375-40d0-af15-25cba812c33e" style="width:70%;">


### Validator Testing

- HTML

  - No errors were returned when passing through the official [_W3C validator_](https://validator.w3.org/nu/?doc=https://mbriscoe.github.io/Ethereal-Expressions)

- CSS
  - No errors were found with our own CSS code when passing through the official Jigsaw validator. However, there were many errors found in the Bootstrap CSS code, which is a normal result.

## Bugs
All bug fixes were dealt with efficiently and cleanly.
- BUG: contact page width issue
- BUG: Footer overlapping content
- BUG: Shading display on gallery page

<a id="deployment"></a>
## Deployment

- The site was deployed to GitHub pages from the main branch of the repository early in the developemnt stage for continuous deployment and checking.

- The live link can be found [_here_](https://mbriscoe.github.io/Ethereal-Expressions/)

<a id="credits"></a>
## Credits

### Content

- 
- 
- 

### Media

- Favicon: we generated the image using AI IDDLE (CHAT GPT) and we formatted it with the website [_favicon.io_](https://favicon.io/favicon-converter/#google_vignette)

- Weather Icon: we used the icons provided by the API  [_OpenWeather_](https://openweathermap.org/)


<a id="future-features"></a>
## Future Features

There are various features and user stories that we were not able to implement due to time constraints, but would be added in future iterations of the website.

- Interactive Map that shows your current search geographical location 
- Change the backgroung colour based on the temperature of the forecast



A Weather or Not Production


