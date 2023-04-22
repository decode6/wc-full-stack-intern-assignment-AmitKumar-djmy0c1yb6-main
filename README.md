# Cinema

## Features and Tools Used:

1. Vue.js as Front-End Framework
2. Vuex for state management
3. SCSS for styling
4. Responsive UI
4. Animation
5. Local Storage for storing Favourites
6. vue-carousel
7. vue-youtube
9. vue-js-modal
10.Moviedb Api


## How to Load the App
>>npm install 
for installing all dependencies
After That
>>npm run serve 

Once all of the dependencies have been installed you have to create a .env file in root of folder and store API key that you have to get from [TheMovieDB API](https://www.themoviedb.org) 

```
VUE_APP_API_KEY=226fa11333b277fbfc18b9649fc449fc
```

After setting up .env file you can run project by below command

```
npm run serve
```
If You got broken package error then run this command in your terminal
>> export NODE_OPTIONS=--openssl-legacy-provider
After run 
>>npm run serve


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
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
Moviedb  Api reference >> https://developers.themoviedb.org/3
The app is deployed on netlify >> https://decode6-amit-movie.netlify.app
