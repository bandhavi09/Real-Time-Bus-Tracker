# Real-Time-Bus-Tracker
First create index.html file.
Inside head tag wirte the title.
After title write script src which uses javascript and then write the link which uses css.
After that write the link which we use to change styles in html file.
Inside body tag create div id = "map".
Inside map div create another div class = "map-overlay top".
Inside map-overlay top create button which is show stops between MIT and Harvard.
Write the script src link which connects index.html and ./mapanimation.js.
Create styles.css.
Write code for body which consists of margin, padding.
After body write for map which consists of position, top, bottom, width.
After map write code for map-overlay which consists of position, left, padding.
Create mapanimation.js.
Create array busStops with coordinates which are latitude and langitude.
Get accessToken from mapbox and write here.
Create new mapboxg1.Map({}) which consists of container, style, center, zoom.
Then add marker to the map at the first coordinates in the array busStops.
Set counter and use function move(){}.
Inside function move use setTimeout function.
