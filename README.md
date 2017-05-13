# ArrowRadiusView

[![Build Status](https://img.shields.io/travis/zengxianshu/ArrowRadiusView.svg?branch=master)](https://github.com/zengxianshu/ArrowRadiusView)
[![Swift 3.0](https://img.shields.io/badge/Swift-3.0-orange.svg?style=flat)](https://github.com/zengxianshu/ArrowRadiusView)
[![Platform](https://img.shields.io/badge/Platforms-iOS-4BC51D.svg?style=flat)](https://developer.apple.com/swift/)
[![Version](https://img.shields.io/cocoapods/v/ArrowRadiusView.svg?style=flat)](https://github.com/zengxianshu/ArrowRadiusView)
[![License](https://img.shields.io/cocoapods/l/ArrowRadiusView.svg?style=flat)](https://github.com/zengxianshu/ArrowRadiusView)

# effect
![](testArrowRadiusView.png)

## Requirements

## Installation

ArrowRadiusView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:
```ruby
use_frameworks!
pod 'ArrowRadiusView' :git => 'https://github.com/zengxianshu/ArrowRadiusView.git'
```
![](Example.png)
```swift
self.topArrowRadiusView.arrowDirection = .top
self.topArrowRadiusView.arrowOffset = CGPoint.init(x: 10, y: 0)
self.topArrowRadiusView.arrowSize = CGSize.init(width: 10, height: 8)
self.topArrowRadiusView.backGroundgColor = .lightGray
self.topArrowRadiusView.boderWidth = 1.0
self.topArrowRadiusView.borderColor = .black
self.topArrowRadiusView.cornerRadius = 3.0
```

## Author

曾墨, zengxsios@gmail.com

## License

ArrowRadiusView is available under the MIT license. See the LICENSE file for more info.
