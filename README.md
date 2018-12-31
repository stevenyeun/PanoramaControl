# PanoControl
PanoramaControl is a windows forms based based control software for an automated pan/tilt panorama head.
PanoramaControl is running on a Windows based netbook. Via  a wireless connection (e.g. Bluetooth) position and camera(shutter)-commands
are sent the automated panorama head.  The automated panorama head is controlled by a microcontroller - currently an Arduino Mega is in use.
The Arduino Sketch PanoDuinoControl (another project of mine that can be found here on Github) is handling the communication with PanoControl.


Features:
-configuration of stitching parameters for various cameras/camera-lens-combinations (e.g. Sony A7, Lumix FZ200, Lumix FZ28)
-Adjustable timing, overlap parameters
-Configuration (new Cameras etc.) can be set in PanoControlConfig.xml
-Enter start- and end-positions for panorama acquisition
-start/stop/pause acquisition 
-Timelapse mode
-recording of exact shoot positions (based on position encoder readings) for import professional stitiching software
-wireless communication with microcontroller-based panorama head 
-can be extended to various acquisition modes (default: flat panorama for large gigapixel panoramas) .I didn't care much about spherical 
 panoramas (not very well implemented yet), but a proper implementation shouldn't be too difficult.
