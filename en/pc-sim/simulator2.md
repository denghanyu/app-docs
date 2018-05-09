# Learn how to use Altizure App in DJI Simulator? (Mavic, P4, Inspire 2, M600, etc.)

## Supported UAVs

* Spark
* Mavic Pro
* Phantom 4 \(4 / 4 Advanced / 4 Pro\)
* Inspire 2
* M600, M200, M210, etc.
* A3, N3, etc.

## Supported Platforms

* Windows
* macOS

### 1. Download and run DJI Assistant 2

Please go to DJI's product page. In the **SOFTWARE** section, download and install DJI Assistant 2 on your computer.

* [Download for Phantom 4](http://www.dji.com/phantom-4/info#downloads)
* [Download for Phantom 4 Pro](http://www.dji.com/phantom-4-pro/info#downloads)
* [Download for Inspire 2](http://www.dji.com/inspire-2/info#downloads)
* [Download for M600](http://www.dji.com/matrice600/info#downloads)
* [Download for Mavic Pro](http://www.dji.com/mavic/info#downloads)
* [Download for Inspire 2](http://www.dji.com/inspire-2/info#downloads)

![Download Assistant 2](../../assets/assistant2-download.jpg)

### 2. Connect your aircraft to computer

Open DJI Assistant 2. Then, open your aircraft with propellers detached. Use a USB cable to connect your aircraft and computer.

![Phantom 4 Series - USB](../../assets/pcsim-usb-phantom4.jpg)

![Mavic Pro USB](../../assets/pcsim-usb-mavic.JPG)

Below is the screenshot of DJI Assistant 2 when Phantom 4 is connected:

![Simulator when Phantom 4 is connected](../../assets/assistant2-phantom4.jpg)

### 3. Start simulator

Click **Simulator** in left panel. Enter the Latitude and Longitude near you. This will be the simulated location of your aircraft. Then, click **Start Simulating**.

![After starting simulator](../../assets/assistant2-simulator.jpg)

### 4. Try Altizure App

Connect your remote controller with Altizure app. In Altizure app, find the simulated location of your aircraft on the map in Altizure app, and start a new mission.

![Altizure app interface](../../assets/pcsim-altizureapp.jpg)

## Tips

* Here is a [DJI Guide](https://developer.dji.com/mobile-sdk/documentation/application-development-workflow/workflow-testing.html#aircraft-simulator)on using the simulator.
* Under the simulation mode, your aircraft will still take photos. So, after simulation, you may need to delete these photos to free up space in SD card.
* Scroll your mouse wheels to zoom in/out in simulator.
* Right click the simulator, select **Setup**, tick **Show Trace**, then you can see the flight path.

    ![flight path in simulator](../../assets/pcsim-trace.jpg)

---

Last modified at {{ file.mtime }}
