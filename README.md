# react-native-xamarin
A framework for building native Xamarin apps with React. http://facebook.github.io/react-native/

## Introduction

This repository contains the work-in-progress attempt to build Xamarin apps using the [React Native](http://facebook.github.io/react-native/) stack. Since it is a work in progress, do not expect it to fully work. As the project grows, the steps involved will be documented here.

## What it takes to build Xamarin app on React Native

 1. NPM package containing build scripts for Xamarin apps
 2. A dependant NPM package containing the actual `.sln` with actual code for all target platforms
 3. Explain `react-native` that the above scripts exist and enable `react-native xamarin` and `react-native xamarin-forms` commands.
 4. Use a JavaScript interpreter to actually run React code. We will use [JINT](https://github.com/sebastienros/jint) for that because it is a self-contained, cross-platform JavaScript engine that can also interact with CLR.
 5. Map all primitives in React Native to the corresponding primitives - e.g. `Text` view in React should map to the corresponding UI platform class.
 
## Pull requests and contributions

This is an open source project and we accept contributes. Please be mindful about style changes when submitting pull requests, we will reject those pull requests which are mostly style changes.
 
 ## Build instructions
 
 TBD
 
 ## License
 
 Everything here is licensed under MIT.
