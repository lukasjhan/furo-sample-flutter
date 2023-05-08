# Furo Flutter Sample Project

This is a Flutter sample project for the Furo. Check out the [Offical Docs](https://docs.furo.one) for more information.

## Getting Started

1. Clone this repository
2. Set up clientId in `lib/main.dart`
3. Set up redirect uri in `lib/main.dart` and Furo console.
4. Run Project and click login button to start authentication.
   1. if you want to use moblie follow these steps.
   - Android
     - Add deeplink scheme in project/android/app/src/main/AndroidManifest.xml
     - Set up redirect uri in `lib/main.dart` and Furo console: `scheme://auth`
   - iOS
     - Add deeplink scheme in project/ios/Runner/Info.plist
     - Set up redirect uri in `lib/main.dart` and Furo console: `scheme://auth`
