# Travel App
The project will include a simple form where you enter the location you are traveling to and the date you are leaving. If the trip is within a week, you will get the current weather forecast. If the trip is in the future, you will get a predicted forecast. The OpenWeather API is fantastic but it doesn’t let you get future data for free and it’s not that flexible with what information you enter; we are going to use the Dark Sky API for you to see how another API accomplishes the same goals. Dark Sky has one problem, it only takes in coordinates for weather data -- it’s that specific. So, we’ll need to get those coordinates from the Geonames API. Once we have all of this data, we’ll want to display an image of the location entered; for this, we will be using the Pixabay API.

## Getting started

Remember that once you clone, you will still need to install everything:

`cd` into your new folder and run:
- `npm install` `npm run build-prod` `npm run start`

To run dev server `npm run build-dev`

To start project quickly `npm run start-reloader`

To run test `npm run test`

## APIs in server backend
* port we use is `8000`
* `/geonames`
* `/darksky`
* `/pixabay`

## Services we use
* [Geonames](http://www.geonames.org/export/web-services.html)
* [Dark Sky](https://darksky.net/dev)
* [Pixabay](https://pixabay.com/api/docs/)

