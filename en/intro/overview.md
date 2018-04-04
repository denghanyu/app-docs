# Introduction

## Download Links {#installation}

For more details, please check [Altizure Official Website](https://www.altizure.com/mobile):

* iOS: Search "Altizure" in AppStore. Download and install. [Click here to download from AppStore](https://itunes.apple.com/app/id1018791616?mt=8). Or, your can download it by scanning the QR code. (You are recommended to use the smart phone camera in iOS 11):
        ![AppStore 二维码](../../assets/app-download-ios-appstore.png)
        
* Android: You can download it from Android App Store (e.g. Google Play) by searching "Altizure".

## Main Functions {#features}

### Flight Planning

* Automatic flight planning: Altizure app automatically creates five flight paths with the first one covering the vertical views and the other four the oblique views.
* Automatic adjustments in Camera Angles and automatic image-taking function.
* Save and upload mission function.
* Continued flights requiring more than one battery swap can resume correctly as Altizure app records flight status automatically.
* Adjustable settings in overlap, tilt Angle, etc.
* Possibility to choose between Return-to-Home and Continue the Mission in Signal Loss.
* 针对不同相机型号调整航线，可自定义相机型号
* Support Apple Map (iOS) and Gaode Map (Android)
* Support Google Map (You need to be able to connect to Google.)
* Support Coordinate Calibration (for Mainland China users)
* Support flight record export


Other Functions (only available for iOS):
* Support importing and displaying additional KML layers
* Support adding annotations on the map by entering GPS coordinate of the point
* Support adding Tile layers both online and offline.
* Suport customized camera settings.
* Allow adjusting settings in Flight Speed and the time between shots in the interval shot mode.
* Allow adjusting exposure settings in Altizure app.
* Support No-Fly-Zone display on map.
* Integrated flight simulator.


## Supported Smart Phones/ Tables & UAVs {#devices}

### Requirements on Smart Phone/ Tablet

* iOS: Must be iPhone, iPad or iPod with iOS 9.0 or above.
* Android: Must be smart phones/ tablets with Android 6.0 or above. (Do not support devices with Intel CPUs)

Note: Do not support DJI aricrafts with a Display controller, e.g. Phantom 4 Pro+.

### Supported UAVs

| UAVs | iOS (v4.0.0) | Android (v3.7.3) |
| ---  | :---: | :---: |
| Phantom 3 \(Pro / Advanced / 4K / Standard\) | ✔︎ | ✔︎ |
| Phantom 4 \(4 / 4 Adv / 4 Pro\) | ✔︎ | ✔︎ |
| Mavic Pro | ✔︎ | ✔︎ |
| Inspire 1 / 2 | ✔︎ | ✔︎ |
| M100, M600 series <sup>1</sup> | ✔︎ | ✔︎ |
| A2 / A3 + LB2 <sup>1</sup> | ✔︎ | ✔︎ |
| M200 系列 <sup>1</sup> | Testing | Testing  |
| N3 + LB2 <sup>1</sup> | Testing  | Testing  |
| Spark <sup>2</sup> | Not Supported Yet | Not Supported Yet |
| Mavic Air <sup>3</sup> | Not Supported Yet | Not Supported Yet |
| Phantom 3 SE <sup>4</sup> | Not Supported | Not Supported |
| Phantom 4 Pro+ (Includes Display) <sup>5</sup>| Not Supported | Not Supported |

Notes:

1. As there's no API for third-party cameras at the moment, Altizure App only supports DJI cameras. If you use Altizure app with a third-party camera, your drone may not be able to automatically take photos.
2. Spark does not support waypoint mission, which is required by Altizure app. The reason for this is unknown.
3. As this is a new model, DJI SDK cannot support this UAV at the moment. We need to wait for DJI's SDK updates and the updates in waypoint mission support.
4. DJI SDK is not (and probably will never be) fully compatible with Phantom 3 SE.
5. Altizure app does not support aircrafts with Display controller. It must be used on a remote controller without Display controller.

### Supported Cameras for Waypoint Missions {#cameras}

| Cameras | iOS (v4.0.0) | Android (v3.7.3) |
| ---  | :---: | :---: |
| Cameras carried by aircrafts of Phantom、Mavic、Spark series | ✔︎ | ✔︎ |
| Zenmuse X3, X4S, X5/X5R/X5S | ✔ ︎|✔︎ |
| Other cameras | Support adding additional camera components <sup>1</sup> | ✖︎ |
Note:
1. You can add camera parameters for flight planning and automatic flight. As there's no API for third-party cameras at the moment, your drone may not be able to automatically take photos if you use Altizure app with a third-party camera.


---

Last modified at {{ file.mtime }}