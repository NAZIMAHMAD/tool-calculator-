1. Create Vite application -
   1. pnpm create vite
   2. Choose React JS
   3. Install dependencies
2. Setup dot env file.
3. Install dependencies - 
   1. axios
   2. leaflet
   3. react-leaflet
4. Create service files for API calls functions.
5. Working of code - 
      First we get the current location of the user, and based on the location we fetch the restraunts near them (5 max). When the data is fetched we create markers based on the coordinates. 
      If user clicks on any destination marker, we fetch the polyline waypoints from the API and show the routes.