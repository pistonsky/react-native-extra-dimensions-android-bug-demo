# What does this repo do?
This repo is showing a bug in [react-native-extra-dimensions-android package](https://github.com/Sunhat/react-native-extra-dimensions-android).

# How to run?
As usual,
`yarn; yarn android;`

# How do I prove the bug?
When you start the app, there will be a `keyboardDidShow` event dispatched. However, no text input is focused, and the keyboard is not shown.