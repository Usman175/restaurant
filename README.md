# Restaurant Finder
![Preview](./src/assets/logo.png)

#### From the name you can assume that it finds restaurants for you. It displays near by restaurants in map and in feed. 

Download the APK : [Installable APK](https://github.com/ishraqe/restaurant/raw/master/apk/app-release.apk)


## Built With
 - [React Native](https://facebook.github.io/react-native/)
 - [Redux](https://github.com/reactjs/redux)


This is my second application built with react native. I built this application in hope of digging out social authentication like (Facebook, Gmail) and Google Maps. It gives direction how to go to a particular place.For authentication I used Facebook and Google sign In api maintained by Redux state. This nearly has the urges to use database. For that i used AsyncStorage. All the information displayed are from google map and places API. For that i used libraries like which uses google map and places in the background.
 

I would really appricate any suggestions, feedback, PRs and Issues.


## Walkthrough

![Preview](./src/assets/detail.gif)
![Preview](./src/assets/direction.gif)

In Singn in and Sign Up i used components own state combining Redux state.

Upon successful sign in or sign up, the user will be directed to the home page. These page are created using the [React native router flux](https://github.com/aksonov/react-native-router-flux). 


The App contains is consists of three tabs -

 - Home
 - Create new blog
 - Notifications (which is under developed)

These are swipeable tabs that are created by using the library [React native router flux](https://github.com/aksonov/react-native-router-flux). 
The top navigation bar comes also with it. There is also a drawer or side bar present there.  It consists of

- Home
- Search
- Map
- Bookmarks

The "Home" component is a basically [Flat list](https://facebook.github.io/react-native/docs/flatlist.html).  All the data are coming from Google Map API's. In home page user will be displayed with nearby resturant's. Clicking on any restaurnt there will be a siingle page for that particular restaurant will be opened. Which contins Information about that restaurant such as contact, direction to go there, reviews, menu's and images.  Though google doesn't provides any info about menu and image i just added some static data. 


### Debugging & crash-reporting:

Debugging of was pretty straight forward using the built in debug option. Rather than this i used [React native debugger](https://github.com/jhen0409/react-native-debugger), which gives me more flexibilty of debugging and waching over redux state. 

Upon installing the app i had faced some issues that caused the app crash and my bust my head of. By searching and asking on different communities i found some pretty good crash report tools. Among them i found love in [bugsnag](https://www.bugsnag.com/). They came up with some pretty good well formatted crash report. 


## How to create your own copy of this app?
### Prerequisites
To create an own copy of this application, you have some prerequisites. They are -

 - [NodeJS](https://nodejs.org/en/) installed on your system.
 - [React Native](https://facebook.github.io/react-native/) installed on your system.
 - Have the [Android SDK](https://developer.android.com/studio/index.html) and paths set properly. 
 - An android emulator or real device to run the app.

### Make own copy
First clone the repository using:

    git clone https://github.com/ishraqe/restaurant.git

Then install the dependencies using:

    npm install


 Run the following command to run the app on the emulator.

    react-native run-android
Now, you have your own copy of this application!


## License
Gimmi some cash !!, Kidding, Do whatever you want to do.


## Credits
For a noob like me creating an application of this stature woudn't have been possible without help of some awesome libraries i found.   

 - [React](https://facebook.github.io/react/)
 - [React Native](https://facebook.github.io/react-native/)
 - [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
 - [Redux](https://github.com/reactjs/redux)
 - [React Redux](https://github.com/reactjs/react-redux)
 - [Redux thunk](https://github.com/gaearon/redux-thunk)
 - [React native communications](https://github.com/anarchicknight/react-native-communications)
 - [React native google places](https://github.com/tolu360/react-native-google-places)
 - [React native fbsdk](https://github.com/facebook/react-native-fbsdk)
 - [React native linear gradient](https://github.com/react-native-community/react-native-linear-gradient) 
 - [React native google signin](https://github.com/devfd/react-native-google-signin)
 - [React native maps](https://github.com/react-community/react-native-maps)
 - [React native scrollable tab view](https://github.com/skv-headless/react-native-scrollable-tab-view)
 - [React native shadow](https://github.com/879479119/react-native-shadow)
 - [React native snap carousel](https://github.com/archriss/react-native-snap-carousel)
 - [React native video](https://github.com/react-native-community/react-native-video)

 
 
Made with ♥ by [Ishraqe Manjur](https://twitter.com/ishraqe_manjur)
