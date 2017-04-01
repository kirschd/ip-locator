# IP Locator
IP Locator is a simple progressive web application to geo-locate an IP address it demonstrates the use of Google's Material Design Light, Google Maps JavaScript API and ip-api.com JSON API and implements Service Workers, Cache API and offline functionality; the use of a Manifest for Web and Add to Homescreen.

## Progressive Web Apps
Progressive Web Applications take advantage of the latest technologies to combine the best of web and mobile apps; think of it as a website built using web technologies but which acts and feels like an app. Recent advancements in the browser and the availability of service workers, the Cache and the Push APIs, have given web developers the possibility to install web apps to the home screen, receive push notifications and even work offline.

### Service Workers
Event-driven scripts (written in JavaScript) that have access to domain-wide events, including network fetches. Through service workers, it's possible to cache all static resources, which could drastically reduce network requests and have considerable performance improvements too.

### Manifest
A simple JSON file that must follow the specification available on [W3C](a href="https://w3c.github.io/manifest/" target="_blank"), it is possible to run the web app in full-screen as a standalone application, assign an icon which will be displayed once the application is installed onto the device or assign a theme and background colour to your app. In addition, Chrome on Android also proactively suggests to the user to install the web app using [Web App install banners](https://developers.google.com/web/fundamentals/engage-and-retain/app-install-banners/).

### Technology
Built using traditional HTML5 with [Google's MDL](https://getmdl.io/), CSS3 @media queries for responsive design and JQuery that simulates the retrieval of data from the API by AJAX JSON get calls.

### API
The JSON API of [http://ip-api.com/json/](http://ip-api.com/json/) is used for gathering geo-loction data.
Google Maps JavaScript API to display the gathered geo-loction data on map.

## Demo
Demo: [https://vijjusri14.github.io/ip-location/](https://vijjusri14.github.io/ip-location/)
