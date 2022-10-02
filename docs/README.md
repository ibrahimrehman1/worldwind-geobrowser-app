# Worldwind GeoBrowser Web Application

We have utilized an existing template from the [resource](shorturl.at/efmIO), it had very minimal features in the beginning including the control panel at the bottom left of the main page of the web application, the compass and other controls, markers and some layers that are visible at the top left drop-down menu of the page, The search menu allowed to enter a location to be viewed. There were some setting options available as well. The user could also zoom into and zoom out of a location to any extent.



We have made the WorldWind JS web application responsive on mobile devices as well previously it was not. The application allows the user to view the globe in a broad spectrum due to the features added in the existing basic template. The added layers include heat map, which when enabled, depicts a colored overlay on top of the map, areas with higher intensity are colored red, and areas with lower intensity are colored green. The “Bing roads” layer is also added using a geospatial mapping platform Bing map to layer the data relevant to the location on top of the licensed map imagery. We have modified the settings to add stars and atmosphere to the view. The user is able to click or tap on a specific location using a personal computer or mobile phone respectively anywhere on the globe to rotate and move to have a better view of the desired location. The night sky animation feature was added to how the night time view at one half of the globe and daytime view at the other half of the globe. There were previously no projections available, now the user has multiple projections like equirectangular, Mercator, north polar, south polar, North UPS, south UPS, north gnomonic, south gnomonic, and 3D by default All of this was done by extending the WorldWind JS library to add the mentioned layers, projections and setting options. 



With this application we hope we were able to develop a tool that could help users and space enthusiasts to better visualize our globe from the outer space view. The basic template that we utilized was as good as a picture of the globe and had no dynamic visibility options available for better user experience. We added some important features that provided crucially important layers like the heat map and Bing roads. There are multiple features like the projections, switching to different locations on one tap or click, night and daytime view, enabling and disabling the stars and atmosphere from the view that enhances the user experience while using the application. In this age where people use their laptops when absolutely necessary it was very important for the app to be responsive on mobile phones as well which we considered as a top priority. 



The app is based on the following technologies

- HTML5

- CSS3

- JavaScript

- Jquery

- Bootstrap 4

- Knockout JS

- WorldWind JS
