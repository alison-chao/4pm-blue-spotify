# 4pm-blue-spotify

Installation
Prerequisites
Node.js React-Native Expo

*Installation Steps*
Run the following commands to install expo and react:

npm install -g expo-cli

npm install -g react-native

npm install -g react-native-cli

new instructions:

INSTALL nav bar tool:

npm install react-native-navbar --save

https://github.com/react-native-community/react-native-navbar#examples

INSTALL navigation tool for multi-page:

npm install --save react-navigation

*INSTALL SPOTIFY MODULE:*

To add the Spotify SDK to your project, cd into your project directory and run the following commands:

npm install --save rn-spotify-sdk

react-native link react-native-events

react-native link rn-spotify-sdk

MANUALLY ADD SPOTIFY FRAMEWORKS for iOS within Xcode (if they do not already exist):

Manually add the frameworks from node_modules/rn-spotify-sdk/ios/external/SpotifySDK to Linked Frameworks and Libraries in your project settings. Then add ../node_modules/rn-spotify-sdk/ios/external/SpotifySDK to Framework Search Paths in your project settings.

*LAUNCH PROJECT* with the following steps:

cd into project folder

*Run* npm start and launch through expo or iOS similator

