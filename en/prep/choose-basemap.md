# Choose the Right Map

Flight Planning requires clear Satellite Map. As the data available for different map providers varies, users can choose the map in Altizure app based on their on needs.

在地图上规划航线需要有清晰的卫星地图。由于地图服务商提供的数据各有不同，app 内置了多种地图以供选择。

* iOS: Apple Map, Google Map
* Android: Gaode Map, Google Map

## Ways to swtich between different maps

* **iOS:** Click the gear icon in the top-right corner. Choose a map in the popup window.

* **Android:** Click the menu icon (three-dots icon) on the top-right and enter "Map Settings". Choose a map in the popup window.

## FAQ

1. **Map is not displayed on the screen**

    First, please check the internet connection. As Altizure app does not have 
    
    首先需要检查网络连接，因为 app 没有内置地图数据，需要自动从地图服务商下载并缓存后才能显示。没有网络时，地图会加载缓存的地图数据。缓存空间有限，只有最近浏览过的一部分才会被缓存。

    如果网络通畅但没有卫星数据，则可能是因为地图提供商没有提供这个区域的卫星图。一般苹果地图和高德地图只提供城市和部分郊区的数据，乡村和偏远地区的数据常有缺失。谷歌地图的数据最为全面，更新更频繁，建议在苹果和高德没有数据的时候尝试谷歌地图。

2. **谷歌地图无法使用，打开后一片空白**

    受我国的法规和网络限制，谷歌地图的服务器在国内无法直接连接，因此 app 内不能直接加载谷歌的地图数据。必要时请使用一些网络代理手段来连接。

    很抱歉，受法律限制，相关教程和服务我们不能直接提供。

3. **Android 设备上选择谷歌地图后，提示需要安装/升级谷歌服务，地图一片空白**

    这是由于 Android 设备上的谷歌地图需要使用谷歌服务套件。国内手机厂商很少会内置谷歌服务套件，所以使用者需要自行安装谷歌服务框架（Google Services Framework）与谷歌服务套件（Google Play services）。

    安装方法可能会根据手机型号有所不同，某些安装方法可能对手机产生不理影响。请参考网络媒体或手机品牌的社区里的教程谨慎安装。例如:

    * [ifanr: 如何才能享用 Google 全套服务？](http://www.ifanr.com/app/693456)

---

Last modified at {{ file.mtime }}