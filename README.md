# Twitter Clone using React Navigation v5 and React Native Paper 

This is a fork of the Twitter app implemented for 
[this blog post](https://reactnavigation.org/blog/2020/01/29/using-react-navigation-5-with-react-native-paper/)

## Changes

Updated Expo and various libraries.

Replaced `route.state.name` with `getFocusedRouteNameFromRoute()`.

Replaced `useSafeArea()` with `useSafeAreaInsets()`.

Moved sample data from JavaScript to a Firebase-compatible JSON file.

Updated URL for Evan Bacon's profile image.

## Bugs

Notifications and Messages screens are blank the first time you navigate to them. No error messages in console.



![screenshot demo](./assets/app.gif)

