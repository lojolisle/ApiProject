API project using Node Express and Vue js

This project use three API
1) to get current user location, uses this coordinates to plot on map which is build using the Leaflet library
2) Uses another API to get geocoding from MapBox. This helps in search using a keyword say for example 'Scarborough' and it list places which are closer to users current location
3) on selecting a location, the co-ordinates from API payloads is used to plot on map
4) Again another weather API using OpenWeatherMap to also gather the weather details of the place selected by the user   


5) cd into server folder and start server using 'npm run dev'

6) client side is using vue cli and can be run using 'npm run serve'
   cd into client folder and enter 'npm run serve' to start
 

# client

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
