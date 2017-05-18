---
title: Parrot Sequoia API
date: 2017-05-18 04:34:00 Z
---

I'm profiling a number of drone APIs lately and I came across some interesting APIs out of Parrot. Not all of them are drones, but I thought they were clean and simple examples of what IoT APIs can look like.

[The API for the Parrot Sequoia camera](http://developer.parrot.com/docs/sequoia/) can be controlled over USB, WIFI via an HTTP-API. The API allows you to change settings, calibrate the sensors, trigger image capture and manage internal memory.

Here are the paths for the device:

/capture: to get the Sequoia capture state, start and stop a capture
/config: to get and set the cameras configuration
/status: to get all informations about the Seuqoia physical state
/calibration: to get the calibration status, start and stop a calibration
/storage: to get informations about memory
/file: to get files and folders informations
/download: to download files
/delete: to delete files and folders
/version: to get serial number and software version
/wifi: to get the Sequoia SSID
/manualmode: to get and set ISO and exposure manually
/websocket: to use websocket notifications on asynchronous events

