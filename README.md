
[![Build Status](https://img.shields.io/cocoapods/p/LivenessSDK)](https://img.shields.io/cocoapods/p/LivenessSDK)
[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/LivenessSDK)](https://img.shields.io/cocoapods/v/LivenessSDK)

# LivenessSDK
LivenessSDK for iOS

## Example
```swift
import LivenessSDK

  var liveness = Liveness()

  liveness.delegate = self
 
  liveness.startLiveness()

```



## Features
- Supports iOS 12.0+
- Supports binary
- Supports iPhone and iPad


## Installation
Requires Swift 4/5 and Xcode 10.x

### CocoaPods 1.0.0 or later
Create `Podfile` and add `pod 'LivenessSDK'`:

```ruby
use_frameworks!

target 'YourApp' do
    pod 'LivenessSDK', '~> 0.0.2'
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




# [Docs](https://nuclearace.github.io/LivenessSDK/index.html)

- [LivenessSDK](https://nuclearace.github.io/LivenessSDK/Classes/LivenessSDK.html)

## License
MIT
