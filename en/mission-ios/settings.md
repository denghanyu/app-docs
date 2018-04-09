# Mission Settings (for iOS)

## Flight Area & Flight Paths {#region}

In Altizure app, the green rectangle represents the area that will be captured and built into a 3D model. The gray semi-transparent polygon indicates the region that the aircraft will possibly fly over in the 5 flight missions automatically set by the app. When setting the flight area, users should keep it away from high-rise buildings or mountains, as well as No-Fly Zones. 

The white polyline on the map represents a flight route/ path with a white arrow at each end, indicating the start point and the end point of the route.

## Basic Settings {#basic}

**Mission Settings** panel:

![Basic Settings Panel](../../assets/mission-settings-basic-ios-eng.png)

### Flight Altitude {#altitude}

If we regard the altitude of the takeoff point as 0, you can set the Flight Altitude between 10m and 500m. For safety reasons, users should make sure that the flight altitude is higher than the obstacles within or around the flight area.

Note: The maximum flight altitude is also restricted to the **Maximum Flight Altitude** in DJI Go. So, before making flight plans, please check or revise relevant settings in DJI Go.

### Camera {#camera}

Different cameras have different angles of view (AOV). To ensure the image quality and photo-taking efficiency of a flight, users need to choose the right camera for their drones.

Note: Some cameras use different lens, e.g. Zenmuse X5S. The Camera List in Altizure app has only listed the default/ commonly-seen lenses. If you are using a lens with a different focal length, please choose the right camera and fill in relevant parameters.

### Resume Mission {#resume}

You can change the takeoff point by using this function.

When mapping large areas, a mission often requires more than one battery and somtimes, the mission might be interrupted midway due to unpredictable situations. Under such circumstances, users can skip the parts that have already captured by adjusting the Percentage in Resume setting.

How to use it: 

如何使用：注意观察航线上白色箭头的位置，然后调整这个选项。可以发现，进度条滑动时，表示航线起点的白色箭头会沿着航线前行方向跳动，略过的部分也会变得黯淡虚化。在下一次执行任务时，飞机就会前往调整后的起点，不再执行略过部分。

在飞机执行任务期间，软件会随着任务的进行自动调整这个数值，同时地图上白色箭头也会随之跳动，这就表示软件已经将任务进度保存下来，以便下次继续执行。

## Advanced Settings {#advanced}

### On Signal Lost {#signal-loss}

Sometimes, the remote controller signal might be interrupted during flight mission. This option is to set aircraft behavior in Signal Lost. In order to meet the needs of different users, we have provided the following two options:
有时飞机执行任务的过程中会出现信号中断的情况，这个选项就是用于设置飞机在中断信号后的行为。为了满足各类使用者的需要，我们提供了两种选项：

* Stop the mission when the drone loses its signal (default)
* Continue the mission when the drone loses its signal (dangerous, not recommended)


如果使用者没有特殊的需求，应当将这个设置保持为默认选项，即“终止任务”。需要启用这个选项的任务请务必详细阅读这个选项下方的警告，以及我们在教程 [飞行安全](../faqs/safety.md) 里关于信号丢失或电量低时的说明。

### Forward Overlap & Side Overlap {#overlap}

**Overlap** is the amount by which one photograph includes the area covered by another photograph, and is expressed as a percentage. 
Forward Overlap: Overlap area between photos along the same flight line.
Side Overlap: Overlap area between photos on adjacent flight lines.

---

Last modified at {{ file.mtime }}
