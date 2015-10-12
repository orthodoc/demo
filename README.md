# DEMO

Ionic demo project

## Instructions
1. Clone the repo locally `git clone https://github.com/orthodoc/demo.git`

1. Change into the cloned repo `cd demo`

1. Run `npm install`

1. Run `bower install`

1. Run `ionic setup sass`

1. Install the helpshift plugin `ionic plugin add helpshift-plugin-phonegap`

1. Set up Helpshift configuration in the `www/js/app.js` file as per the [dev docs](https://developers.helpshift.com/phonegap/getting-started-ios/)

1. For iOS

  * `ionic platform add ios`
  * You need to have the latest version of Xcode
  * Find the `Demo.xcodeproj` in the folders `/platform/ios`
  * Click on it to open it in Xcode
  * Select the provisioning profile where you have added the iOS device id
  * Search for `Enable Bitcode` in `Build Settings` and turn it to no (helpshift requirement)
  * Connect the iOS device and select it from the list
  * Run build from within Xcode
