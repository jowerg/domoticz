# Domoticz

Domoticz is a Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. Notifications/Alerts can be sent to any mobile device

## OpenZWave Library - BARRIER OPERATOR support
You will need to apply the patch implemented by @srirams as described on:
https://github.com/OpenZWave/open-zwave/issues/490

This functionality has only be tested using a Linear GD00Z-4 Garage Door Opener. Define your Garage Opener as a "Door Contact" Switch on Domoticz. 


## Multi platform: Linux/Windows/Embedded Devices

This system is designed to operate in various operating systems.
The user-interface is a scalable HTML5 web frontend, and is automatically adapted for Desktop and Mobile Devices.
Compatible with all recent browsers

Some Information
- Hardware: RFXCOM Transciever, Z-Wave, P1 Smart Meter, YouLess Meter, Pulse Counters, 1-Wire, Philips Hue and a lot more....
- Extended logging
- iPhone / Android / Windows 10 (Phone & Desktop) push notifications
- Auto Learning sensors/switches
- Manual creation of switch codes
- Share / Use external devices
- Designed for simplicity

# More information
* Website: http://www.domoticz.com
* Forum http://www.domoticz.com/forum
* Wiki http://www.domoticz.com/wiki

### Build Status

Status | Operating system
------------ | -------------
![image](https://travis-ci.org/domoticz/domoticz.svg?branch=master "Linux Build Status") | Linux x86_64
![image](https://ci.appveyor.com/api/projects/status/fskiwvjs1q7svwq9?svg=true "Windows Build Status") | Windows
