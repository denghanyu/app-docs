# Introduction

## Download Links {#installation}

For more details, please check [Altizure Official Website](https://www.altizure.com/mobile)：

* iOS: Search "Altizure" in AppStore. Download and install. [Click here to download from AppStore](https://itunes.apple.com/app/id1018791616?mt=8). Or, your can download it by scanning the QR code. (You are recommended to use the smart phone camera in iOS 11):
        ![AppStore 二维码](../../assets/app-download-ios-appstore.png)
        
* Android: You can download it from Android App Store (e.g. Google Play) by searching "Altizure".

## Main Functions {#features}

### Flight Planning

* Automatic flight planning: Altizure app automatically creates five flight paths with the first one covering the vertical views and the other four the oblique views.
* Automatic adjustments in Camera Angles and automatic image-taking function.
* Save and upload mission function.
* Continued flights requiring more than one battery swap can resume correctly as Altizure app records flight status automatically.
* Adjustable settings in overlap, tilt Angle, speed and the time between shots in the interval shot mode, etc.
* Possibility to choose between Return-to-Home and continue the mission in Signal Loss.







Support Apple and Google maps
Calibrate coordinates in Mainland China



* Can choose to Return-to-Home or continue the mission in Signal Loss
* Can choose different cameras and the app will automatically adjust the flight plans and relevant settings accordingly


* 可以同时规划一条正射航线与四条倾斜航线
* 自动调整云台角度，自主拍摄照片
* 支持任务保存与加载
* 自动记录飞行进度，支持换电续飞

* 支持重叠度、倾斜角等设置
* 可选择在丢失遥控信号后继续执行任务，或自动返航
* 针对不同相机型号调整航线，可自定义相机型号
* 支持苹果地图（iOS），高德地图 （Android）
* 支持谷歌地图（要求网络能连接到谷歌服务器）
* 支持中国大陆坐标纠偏
* 可导出飞行记录



iOS 版附加功能：

* 能够导入 KML 并在地图上显示
* 可以输入坐标点的经纬度，在地图上做标记
* 支持自定义瓦片图层，支持添加离线数据
* 支持添加自定义相机配置
* 允许调整飞行速度、拍照间隔等参数
* 支持在 app 内调整曝光设置
* 禁飞区显示
* 内置飞行模拟器

## 支持的手机/平板和无人机 {#devices}

### 手机/平板系统要求

* iOS: 运行 iOS 9.0 以上的 iPhone, iPad, iPod
* Android: 运行 Android 6.0 以上的手机或平板（不支持 Intel 芯片的设备）

注：不支持 DJI 官方屏幕，例如：Phantom 4 Pro+ 遥控上自带的屏幕

### 航线任务支持的无人机型号

| 型号 | iOS (v4.0.0) | Android (v3.7.3) |
| ---  | :---: | :---: |
| Phantom 3 \(Pro / Advanced / 4K / Standard\) | ✔︎ | ✔︎ |
| Phantom 4 \(4 / 4 Adv / 4 Pro\) | ✔︎ | ✔︎ |
| Mavic Pro | ✔︎ | ✔︎ |
| Inspire 1 / 2 | ✔︎ | ✔︎ |
| M100, M600 系列 （注1） | ✔︎ | ✔︎ |
| A2 / A3 + LB2 （注1） | ✔︎ | ✔︎ |
| M200 系列 （注1） | 未测试 | 未测试 |
| N3 + LB2 （注1） | 未测试 | 未测试 |
| Spark （注2） | 暂不支持 | 暂不支持 |
| Mavic Air （注3） | 暂不支持 | 暂不支持 |
| Phantom 3 SE （注4） | 不支持 | 不支持 |
| Phantom 4 Pro+ 带屏幕版 （注5） | 不支持 | 不支持 |

1. 由于缺少第三方相机的 API，目前只兼容大疆官方相机，使用第三方相机时 app 可能无法自动拍照。
2. 由于未知原因，Spark 暂时不支持航线任务。
3. 由于是新机型，DJI SDK 尚未支持此机型。需要等待 SDK 更新并支持航线任务。
4. 不能完美兼容此机型，因为 DJI SDK 不支持（可能永远不会支持） Phantom 3 SE。
5. 不支持在自带屏幕上使用 Altizure，需要使用不带屏幕的遥控。

### 航线任务支持的相机型号 {#cameras}

| 型号 | iOS (v4.0.0) | Android (v3.7.3) |
| ---  | :---: | :---: |
| Phantom、Mavic、Spark 系列自带相机 | ✔︎ | ✔︎ |
| 禅思 Zenmuse X3, X4S, X5/X5R/X5S | ✔ ︎|✔︎ |
| 其他相机 | 支持添加相机配置（注1）| ✖︎ |

1. 可以添加相机参数用于线路规划和自主飞行。但由于缺少第三方相机的 API，使用第三方相机飞行时 app 可能无法自动拍照。

---

该文档最后修改于 {{ file.mtime }}