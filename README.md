# What does this repo do?
This repo is showing a bug in [react-native-extra-dimensions-android package](https://github.com/Sunhat/react-native-extra-dimensions-android).

# How to run?
As usual,
`yarn; yarn android;`

# How do I prove the bug?
When you start the app, there will be a `keyboardDidShow` event dispatched. However, no text input is focused, and the keyboard is not shown.

# Screenshot
![Screenshot_20220322-111905_keyboard](https://user-images.githubusercontent.com/4147152/159421870-65e088d6-874b-4ebe-9c9c-284d0744cc5a.png)
