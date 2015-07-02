# Gimi SDK - iOS Samples

iOS sample project for using the Gimi SDK.

## Instructions

1. Create an account & set your application up at http://app.gimi.vn
1. Download the latest Gimi SDK from http://docs.gimi.vn/downloads
1. Copy `GimiSDK.framework` into the root directory of this repository
1. Open sample project in Xcode
1. Modify the `GM_APP_KEY` and `GM_APP_SECRET` in the project's `AppDelegate.m` file to your credentials, as given by the Developer Console.
1. Compile and run


### Add Kiip to an existing project

1. Add `GimiSDK.framework` to your project
1. Add `GimiSDKResources.bundle` to your project
1. Use `#import <GimiSDK/GimiSDK.h>`

## Frameworks

Frameworks are already linked that are required, but for reference, the following are required:

* CoreTelephony
* QuartzCore
* SystemConfiguration
* AdSupport
* PassKit
* MediaPlayer

## Support

For integration and reference, see our docs at http://docs.gimi.vn
