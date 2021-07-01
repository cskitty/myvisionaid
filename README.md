F# App for Object Detection, Voice Recognition, TTS using Flutter, TF Lite

## Install flutter

git clone https://github.com/flutter/flutter.git -b stable  
cd flutter  
flutter --version  
flutter precache

## Install

```
flutter packages get
```

## Install cocoapods

```
sudo gem install cocoapods
gem which cocoapods

```

## Check flutter environment

```
flutter docter

```

## Set up the library

```
flutter packages get

```

## Compile and install app on iPhone

```
 flutter run --release

```

## Install and Debug

open visual studio code  
install flutter plugin  
open visual_aid directory  
open lib/main.dart, click the run to install on iphone

## iPhone Setup

Open ios/Runner.xcworkspace in XCode
Runner->Targets->Signing&Capabilities
Select your personal team
Change Bundle Indentifier to yours

## Accept the iPhone Developer Profile

General->Device Management->Accept developer

## Models

- Object Detection
  - SSD MobileNet
  - Yolov2 Tiny
