# Shader
[![Version](https://img.shields.io/cocoapods/v/Shader.svg?style=flat)](http://cocoapods.org/pods/Shader)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/younatics/Shader/blob/master/LICENSE)
[![Platform](https://img.shields.io/cocoapods/p/Shader.svg?style=flat)](http://cocoapods.org/pods/Shader)
[![Swift 4.0](https://img.shields.io/badge/Swift-4.0-orange.svg?style=flat)](https://developer.apple.com/swift/)

## Intoduction
#### 🌃 Make simple shade view with Shader!
![demo](Images/1.jpeg)
![demo](Images/2.jpeg)

## Requirements

`Shader` is written in Swift 3. Compatible with iOS 8.0+

## Installation

### Cocoapods

Shader is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'Shader'
```
### Carthage
```
github "younatics/Shader"
```

## Usage
4 methods is available
```Swift 
// Add multiple view using tuple with cornerRadius
let shaderView = Shader.at(framesAndRadius: [(originView.frame, 50), (originView2.frame, 0)], color: UIColor.black.withAlphaComponent(0.5))

// Add common view
let shaderView = Shader.at(frame: originView.frame, color: UIColor.blue.withAlphaComponent(0.3))

// Add common view array
let shaderView = Shader.at(frames: [originView.frame, originView2.frame], color: UIColor.black.withAlphaComponent(0.5))

// Add common view and cornerRadius
let shaderView = Shader.at(frame: originView.frame, cornerRadius: 50, color: UIColor.black.withAlphaComponent(0.5))

self.view.addSubview(shaderView)
```

## References
#### Please tell me or make pull request if you use this library in your application :) 

## Author
[younatics 🇰🇷](https://twitter.com/younatics)

## License
Shader is available under the MIT license. See the LICENSE file for more info.
