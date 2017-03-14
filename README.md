# react-native-android-compile
A demo app to reproduce build issues with React Native

The only change from the original generated code here is the upgrading of the Support Library version to 25.1.1: https://github.com/ronocod/react-native-android-compile/commit/764fb853ec7ac0be329d0e80bcd16ae68819bc4b
This change causes the build to fail due to the usage of `compileSdkVersion 23`.
