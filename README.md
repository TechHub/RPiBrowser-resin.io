# RPiBrowser-resin.io

This setup will start X window server and run Chromium browser opening the page that you will specify in the environmental variable `URL` on the Resin.io dashboard.

### Hardware you need:

 * [Raspberry-Pi 2](http://www.amazon.co.uk/dp/B00T2U7R7I)  
 * [Power Supply (2A)](http://www.amazon.co.uk/dp/B00LSEQMO0)
 * [MicroSDHC 8GB](http://www.amazon.co.uk/dp/B00M55C0VU)  
 * (optional) [Wifi USB dongle](http://www.amazon.co.uk/dp/B003MTTJOY)  
 * [HDMI cable](http://www.amazon.co.uk/dp/B00870ZHCQ) to connect it on the TV/screen

### Installation
Sign up to [Resin.io](https://resin.io) and create your first application with a name and select Raspberry-Pi 2 as device

Download the image for your device and follow the instruction to copy the image on the SD card  
[PiFiller](http://ivanx.com/raspberrypi/) (OS X)  
[Win32DiskImager](http://sourceforge.net/projects/win32diskimager/files/latest/download) (Windows)

Connect your RPi to the TV and turn it on, you will see Resin.io logo on the tv and a loading bar, that means that the device was correctly setup and it's booting correctly, now it's going to do some updates and later download your code into the device **make sure to not interrupt this operation**.

In your dashboard you will see the device after it's online and it will start downloading your code.

### Configuration
Go to resin.io and find your Application. Go into "Environment Variables". Set an ENV var with URL and use the URL that you want as the default URL. Then click "Show redefines", it might only show up after you've added more devices. Here you can set URL overrides that apply for specific devices.
