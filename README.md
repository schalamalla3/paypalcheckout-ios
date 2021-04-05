# Native Checkout for iOS

## Docs

To get started, first checkout out our [quickstart integration guide](https://developer.paypal.com/docs/business/native-checkout/ios/)!

You can also find our reference documentation [here](https://paypal.github.io/mobile-checkout-docs/ios/reference/)

## Installation

### Carthage

To install the PayPalCheckout SDK via [Carthage](https://github.com/Carthage/Carthage), simply add the following line to your `Cartfile`:
```
binary "https://github.com/paypal/paypalcheckout-ios/raw/main/Carthage/PayPalCheckout.json" 
```
### CocoaPods
To install the SDK via [CocoaPods](https://cocoapods.org/), add the following to your `Podfile`:
```
pod 'PayPalCheckout'
```

### Swift Package Manager
If you are working in the context of another package, you can add the PayPalCheckout SDK as a dependency in your `Package.swift` file: 
```swift
let package = Package(
    name: "MyPackage",
    dependencies: [
        .package(url: "https://github.com/paypal/paypalcheckout-ios.git", from: "0.42.0"),
    ],
    ...
)
```
If you are adding the PayPalCheckout SDK into a standalone project, you can add the PayPalCheckout SDK by following Apple's [package integration guide](https://developer.apple.com/documentation/xcode/adding_package_dependencies_to_your_app), while specifying `https://github.com/paypal/paypalcheckout-ios.git` as the source git repository.


## License

See the LICENSE file for more info.
