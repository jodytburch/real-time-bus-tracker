# Real Time Bus Tracker
## Description:
This project tracks the bus stops between MIT and Harvard on a map.  It currently uses a predefined set of coordinates for the bus stops.  When the button is clicked, the map marker will move along the bus route showing each stop between MIT and Harvard.


## How To Run:
1. Fork and clone this repo to your local computer: https://github.com/jodytburch/eyes-exercise
    You will see these files:
    - mapanimation.js
    - styles.css
    - index.html
2. You will need your own API Token from mapbox in order to display the map.  First, sign up for a free account at https://www.mapbox.com. Then, navigate to and follow instructions to generate an API Token.
3. Open mapanimation.js and insert your token into this line:
    mapboxgl.accessToken = 'REPLACE-WITH-YOUR-MAPBOX-ACCESS-TOKEN';

4. Save the file, and drag/drop the "index.html" file into a browser. 
5. The map should load with the starting marker. When the button is clicked, the marker will move along the bus route from MIT to Harvard.

## Roadmap of Future Enhancements:
- Explore different mapbox styles.
- Get real-time data from MBTA API (url), and use that to plot the bus route.
- Use Google Maps API to display actual locations on the map.

## License Information:
**See: [LICENSE](./LICENSE)**
