# Apptentive iOS SDK

The Apptentive iOS SDK provides a simple and powerful channel to communicate in-app with your customers. 

Use Apptentive features to improve your app's App Store ratings, collect and respond to customer feedback, show surveys at specific points within your app, and more.

## Apptentive Demo App

The Apptentive sample application `FeedbackDemo` is included in this repository along with the SDK.

Use FeedbackDemo to test Apptentive's features. Edit the `defines.h` file to include your Apptentive **API Key** and iTunes **App ID** where specified.

Message Center, the Ratings Prompt, Surveys, and [other Apptentive interactions](http://www.apptentive.com/docs/ios/features/) can all be tested before integrating Apptentive in your own app. 

## Install Guide

Apptentive can be installed manually as an Xcode subproject or via the dependency manager CocoaPods.

The following linked guides walk you through the integration process.

 - [Xcode project setup guide](http://www.apptentive.com/docs/setup/xcode/)
 - [CocoaPods installation guide](http://www.apptentive.com/docs/ios/setup/cocoapods)

## Using Apptentive in your App

After integrating the Apptentive SDK into your project, you can [begin using Apptentive features in your app](http://www.apptentive.com/docs/ios/integration/).

You should begin by engaging Apptentive events at various places in your app:

``` objective-c
#import "ATConnect.h"
...
[[ATConnect sharedConnection] engage:@"event_name" fromViewController:viewController];
```

Later, on your Apptentive dashboard, you will target these events with [Apptentive features](http://www.apptentive.com/docs/ios/features/) such as Message Center, Ratings Prompts, and Surveys.

Please see our [iOS integration guide](http://www.apptentive.com/docs/ios/integration/) for more on this subject.

## Testing Apptentive Features

Please see the [Apptentive testing guide](http://www.apptentive.com/docs/ios/testing/) for directions on how to test that the Rating Prompt, Surveys, and other Apptentive features have been configured correctly.

## Contributing

Our client code is completely [open source](LICENSE.txt), and we welcome contributions to the Apptentive SDK! If you have an improvement or bug fix, please first read our [contribution agreement](CONTRIBUTING.md).

## Reporting Issues

If you experience an issue with the Apptentive SDK, please [open a GitHub issue](https://github.com/apptentive/apptentive-ios/issues?direction=desc&sort=created&state=open).

If the request is urgent, please contact <mailto:support@apptentive.com>.

