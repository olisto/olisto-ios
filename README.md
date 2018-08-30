# olisto-ios
The Olisto iOS SDK, for integrating Olisto into your iOS application.

## Installation

Olisto for iOS supports iOS 8, iOS 9, iOS 10 and iOS 11.

Building with Xcode 9 is required, which adds support for iPhone X and iOS 11.

### CocoaPods

Add the Olisto pod into your Podfile and run `pod install`.

```ruby
    target :YourTargetName do
      pod 'OlistoSdk'
    end
```

### Manual Installation

1. Download and extract the zip from the sdk-release folder.
2. Go to your Xcode project's "General" settings. Drag `OlistoSdk.framework` to the "Embedded Binaries" section. Make sure "Copy items if needed" is selected and click Finish.
