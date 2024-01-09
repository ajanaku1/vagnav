#VagNav - Your Travel Companion

VagNav is a responsive web application built with React and Material-UI, providing an interactive map and list for exploring places of interest. While offering a seamless user experience, please note that due to the deprecation of the Travel Advisor API by Rapid API, certain features may not work as intended.

##Features

###Map Exploration: An interactive Google Map lets you explore various locations with markers indicating places of interest.

###Places List: Dynamically updated list corresponding to the visible map area, providing details such as name, photo, and rating.

###Geolocation: Utilizes the Geolocation API to automatically set the user's location as the map's center for a personalized experience.

##Build Tools

###React & Material-UI: Building responsive interfaces.
###Google Maps API & google-map-react: Powering the interactive map.
###RapidApi: for sourcing Travel advisor api
###axios: Handling API requests.
###Webpack & Babel: Bundling and transpiling code.
###ESLint: Ensuring code quality.

##Installation
Clone: git clone https://github.com/your-username/vagnav.git
Navigate: cd vagnav
Install: npm install
Configure: Create a .env file with REACT_APP_GOOGLE_MAPS_API_KEY=your-api-key.
Start: npm start

##Known Issues
Travel Advisor API Deprecation: Due to the deprecation of the Travel Advisor API by Rapid API, some features may not work as expected. Updates addressing these issues will be provided in future releases.

##Contributing
Contributions are welcome! Report bugs or suggest improvements by creating an issue or submitting a pull request. Refer to the Contributing Guidelines for details.
