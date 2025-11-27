# WiFi: Get Your Creds Out <a href="https://www.ohioiot.com"><img src="https://www.ohioiot.com/images/logo.jpg" width="40" ></a>

## Overview

This code was generated in the YouTube video [ESP32 WiFi: Your Next-Level Library](https://www.youtube.com/watch?v=He9YtNsHtYU), the final video in a series on building a next-level WiFi library for ESP32 IoT developers.  👉 Subscribe to the [OhioIoT YouTube Channel](https://www.youtube.com/@OhioIoT?sub_confirmation=1) for more on All Things IoT: hardware, firmware, connectivity, cloud computing, and dev toolkit.


## Getting Started
```
git clone https://github.com/OhioIoT-ESP32-WiFi-Examples/Final-Checklist.git
```


### Getting Started - PlatformIO
This codebase is structrued as a fully ready PlatformIO project, so users can git pull and then immediately compile (after adding credentials).

- Change the WiFi credentials in *lib/creds/creds.h*.
- To turn off logging, delete/comment-out the `wifi_tools.log_events()` and `wifi_tools.log_status()` function calls.
- Compile and run


### Getting Started - Arduino IDE 

- Copy the *wifi_tools* folder, found in the *lib/* folder, to the *libraries/* folder in your Arduino folder (where Arduino stores all of your shared libraries.
- Copy the *checklist/* folder to your Arduino projects folder
- Edit the credentials in *checklist/creds.h*.

<image src="https://www.ohioiot.com/images/arduino_ide_friendly.png" width=60px ></image>


## About


<br>
*OhioIoT is an IoT platform designed for small-scale IoT projects.  For more, check out our website at [www.OhioIoT.com](https://www.ohioiot.com).*
