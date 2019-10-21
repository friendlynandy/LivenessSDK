
[![Build Status](https://img.shields.io/cocoapods/p/LivenessSDK)](https://img.shields.io/cocoapods/p/LivenessSDK)
[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/LivenessSDK)](https://img.shields.io/cocoapods/v/LivenessSDK)
[![Updated](https://img.shields.io/github/last-commit/friendlynandy/LivenessSDK)](https://img.shields.io/github/last-commit/friendlynandy/LivenessSDK)
[![Licence](https://img.shields.io/cocoapods/l/LivenessSDK?color=red&logo=red)](https://img.shields.io/cocoapods/l/LivenessSDK?color=red&logo=red)


# LivenessSDK
LivenessSDK for iOS


* [Features](#-features)
* [Installation](#-installation)
  * [Cocoapods](#using-cocoapods)
* [How to use](#-how-to-use)
* [Delegates](#-delegates)
   *[LivenessDelegate](#-livenessdelegate)
* [Customization](#-customization)
  * [Steps](#-steps)
  * [Thersholds](#-thresholds)  
* [Documentation](#-documentation)
* [Supported OS & SDK Versions](#-supported-os--sdk-versions)
* [License](#-license)

## 🌟 Features
- Supports iOS 12.0+
- Supports binary
- Supports iPhone and iPad


## 📲 Installation
Requires Swift 4/5 and Xcode 10.x

#### Using [CocoaPods](https://cocoapods.org)

[CocoaPods](https://cocoapods.org) is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate Alamofire into your Xcode project using CocoaPods, specify it in your `Podfile`:


Create `Podfile` and add `pod 'LivenessSDK'`:

```ruby
use_frameworks!

target 'YourApp' do
    pod 'LivenessSDK', '~> 0.0.3'
end
```

Install pods:

```
$ pod install
```

Import the module:

Swift:
```swift
import LivenessSDK
```

## 🐒 How to use
```swift
import LivenessSDK

  var liveness = Liveness()

  liveness.delegate = self
 
  liveness.startLiveness()

```
##  Delegates
#### LivenessDelegate

```swift

 func livenessSuccess(live: Bool) {
  }
  
 func livenessError(live: Bool, error: NSError) {
  }

```

## 🎛 Customization

You can set some properties for liveness.

#### Steps
| Steps | Value | Default | 
| ------- | ------- |------- | 
| **Eyes**(enableEyes)  | `Bool` | `false` | 
| **Mouth**(enableMouth)   | `Bool` | `false` | 
| **Yaw**(enableYaw)   | `Bool` | `false` | 
| **Random Steps**(randomSteps)   | `Bool` | `true` | 


#### Thresholds
| Property | Values | Default | 
| ------- | ------- |------- | 
| **Eyes closed Threshold**(eyeThreshold)  | `0.05...0.2` | `0.1` | 
| **Mouth opened Threshold**(mouthThreshold)   | `0.1...0.6` | `0.35` | 
| **Each step timer**(timerSeconds)   | `Seconds` | `5 seconds` | 




### 📋 Supported OS & SDK Versions
* iOS 12.0+
* iPadOS 13.0+
* Swift 5

### 📚 Documentation 
Coming soon...😅

- [LivenessSDK](https://nuclearace.github.io/LivenessSDK/Classes/LivenessSDK.html)

## 👮🏻 License
MIT
