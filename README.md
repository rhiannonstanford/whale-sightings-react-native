
## OPEN Whale Siting API

http://hotline.whalemuseum.org/api

##  Google MAP API

https://developers.google.com/maps/documentation/maps-static/start
API KEY: AIzaSyASnLGhffYBRZ60GqFHOYBSoPiHpW_kJSE

EXAMPLE:

https://maps.googleapis.com/maps/api/staticmap?center=7.480785,80.3402663&zoom=12&size=400x400&maptype=hybrid&key=YOUR_API_KEY


https://blog.codemagic.io/how-to-build-react-native-ui-app-with-material-ui/

##  Dependencies

[] npm i react-native-paper

[] npm install react-native-vector-icons

[] import { Provider as PaperProvider } from "react-native-paper";

  > import at the app level
  > use PaperProvider to avoid naming problems with Redux

[] npm install axios

[] npm install redux (INSTALL FIRST)

[] npm install react-redux (INSTALL SECOND)



## Intsall redux-logger

[] npm i --save redux-logger
  or
  npm add redux-logger


  import logger from 'redux-logger'; 
  or
  import { applyMiddleware, createStore } from 'redux';

## Install redux- thunk

[] npm install --save redux-thunk

  import thunk from 'redux-thunk';

  ## Install react-router-native

  https://reactrouter.com/native/guides/quick-start

  [] npm install react-router-native

  [] import { NativeRouter, Route, Link } from "react-router-native";

  ## Icons

import Icon from 'react-native-vector-icons/FontAwesome';
const myIcon = <Icon name="rocket" size={30} color="#900" />;

arrow-left
arrow-right
binoculars
coffee
home
list
map
ship
tree
globe
globe-americas

> Rule is that you can have 4-5 icons max

"FortAwesome/Font-Awesome": "*"
to the dependencies in your component.json.

https://www.npmjs.com/package/font-awesome