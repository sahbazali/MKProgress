# MKProgress
An iOS Simple Swift Progress HUD 


![image](https://dl.dropboxusercontent.com/s/ljf5dsoyic2loci/pro_1.png)

## Requirements

- iOS 8+
- Swift 3.x.x
- Xcode 8.0+ 

## Installation

MKProgress is only available via [CocoaPods](http://cocoapods.org):

```ruby
pod 'MKProgress'
```
If you want to use the latest features of MKProgress use normal external source dependencies.

```ruby
pod 'MKProgress', :git => 'https://github.com/kamirana4/MKProgress.git'
```

This will pull the latest master branch everytime you do 'pod isntall'

## Usage

The included sample code shows how to use the Progress HUD. 

To display the Progress HUD:

```swift
import MKProgress

MKProgress.show()
```

To hide the Progress HUD:
```swift

MKProgress.hide()
```

## Customization

MKProgress can be customized via the following configurations:

```swift

MKProgress.config.width = 60.0
MKProgress.config.height = 60.0
MKProgress.config.activityIndicatorStyle = .white
MKProgress.config.activityIndicatorColor = .black
MKProgress.config.hudColor = .white
MKProgress.config.cornerRadius = 12.0
MKProgress.config.backgroundColor = UIColor.init(white: 0, alpha: 0.55)
MKProgress.config.preferredStatusBarStyle = .lightContent
MKProgress.config.prefersStatusBarHidden = false
```

## Licence

MKProgress is released under the MIT license. See LICENSE for details




