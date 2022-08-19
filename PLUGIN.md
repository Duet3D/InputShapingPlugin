# Input Shaping Plugin

## Overview
 
Input shaping describes a set of algorithms to reduce ringing frequencies that inevitably occur due to hardware factors in 3D printers. In order to isolate what frequencies affect a machine the most, an [accelerometer](https://docs.duet3d.com/en/User_manual/Connecting_hardware/Sensors_Accelerometer) may be used. This plugin visualises the ringing frequences, allows you to see the impact of various input shapers and fine tune them

## Plugin installation

Starting from DWC 3.4 the **Input Shaping plugin** can be installed to fine-tune input shaper parameters using an accelerometer.

To install the Input Shaping plugin, download the latest release version for your RepRapFirmware version as a .zip file, without unpacking it, and upload it using the `Upload&Start` button on DWC *without* unpacking the file first. After this, you should see the `Plugins` category with a new `Input Shaping` item in the main menu on the left:


![Plugin menu illustration](https://docs.duet3d.com/manual/inputshaping/menu.png)


Before you can start recording samples, you must have an accelerometer connected and configured (see also [M955](https://docs.duet3d.com/en/User_manual/Reference/Gcodes#m955-configure-accelerometer)). If you already know the frequencies you wish to cancel out, an accelerometer is not required.

## Documentation

Please see the [official docs](https://docs.duet3d.com/User_manual/Tuning/Input_shaping_plugin) for further information.
