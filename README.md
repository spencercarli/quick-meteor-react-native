Short example of connecting a React Native app to a Meteor App.

## To Run

- `git clone https://github.com/spencercarli/quick-meteor-react-native.git`
- `cd quick-meteor-react-native`
- `open RNApp/ios/RNApp.xcodeproj`
- `cd meteor-app && meteor`
- Press play in Xcode (or equivalent for Android)

## Note to Android Users

Make sure that you change the `host` in the `DDPClient` initialization to the IP Address of your machine. For some reason `localhost` doesn't work on Android.
