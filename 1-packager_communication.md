# React Native Packager and API

React Native app in development mode talks to React Native Packager which is a small app listening on http://localhost:8081 and building/serving js files.
To get the fully built file, the following URL can be used http://localhost:8081/index.ios.bundle?platform=ios&dev=true&hot=false

Similarly, we will use http://localhost:8081/index.xamarin-forms.bundle?platform=xamarin-forms&dev=true&hot=false to build our js file for the target platform.
