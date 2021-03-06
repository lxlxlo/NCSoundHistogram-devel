# NCSoundHistogram

[![CI Status](http://img.shields.io/travis/Nikola Corlija/NCSoundHistogram.svg?style=flat)](https://travis-ci.org/Nikola Corlija/NCSoundHistogram)
[![Version](https://img.shields.io/cocoapods/v/NCSoundHistogram.svg?style=flat)](http://cocoapods.org/pods/NCSoundHistogram)
[![License](https://img.shields.io/cocoapods/l/NCSoundHistogram.svg?style=flat)](http://cocoapods.org/pods/NCSoundHistogram)
[![Platform](https://img.shields.io/cocoapods/p/NCSoundHistogram.svg?style=flat)](http://cocoapods.org/pods/NCSoundHistogram)

Based on: https://github.com/faviomob/FVSoundWaveDemo

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

Screenshot:

![alt tag](https://ibin.co/2iCJQ7ZnEzfU.png)

## Requirements

* iOS 8 sdk

## Installation

NCSoundHistogram is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "NCSoundHistogram"
```

## Usage

Objective-C
```objective-c
#import "NCSoundHistogram.h"

NCSoundHistogram *soundHistogramView = [[NCSoundHistogram alloc] initWithFrame:self.view.frame];
[self.view addSubview:soundHistogramView];

NSURL *url = [NSURL fileURLWithPath:[[NSBundle mainBundle] pathForResource:@"audio.m4a" ofType:nil]];
soundHistogramView.soundURL = url;

```

Swift
```Swift
import NCSoundHistogram

let soundHistogramView = NCSoundHistogram.init(frame: self.view.frame)
self.view.addSubview(soundHistogramView)

```

## License

NCSoundHistogram is available under the MIT license. See the LICENSE file for more info.
