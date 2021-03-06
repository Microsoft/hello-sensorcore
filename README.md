hello-sensorcore
================

Hello SensorCore is a getting started sample for Lumia SensorCore SDK. The sample shows how to initialise Step Counter API and to display the current Step Counter values. This sample is used as part of the Lumia SensorCore SDK's Quick Start guide, which provides step-by-step instructions for your first project utilizing Lumia SensorCore SDK.
 

1. Instructions
--------------------------------------------------------------------------------

Learn about the Lumia SensorCore SDK from the Lumia Developer's Library. The
example requires the Lumia SensorCore SDK's NuGet package but will retrieve it
automatically (if missing) on first build.

To build the application you need to have Windows 8.1 and Windows Phone SDK 8.1
installed.

Using the Windows Phone 8.1 SDK:

1. Open the SLN file: File > Open Project, select the file `HelloSensorCore.sln`
2. Remove the "AnyCPU" configuration (not supported by the Lumia SensorCore SDK)
or simply select ARM
3. Select the target 'Device'.
4. Press F5 to build the project and run it on the device.

Alternatively you can also build the example for the emulator (x86) in which case
the Steps will use simulated data.

Please see the official documentation for
deploying and testing applications on Windows Phone devices:
http://msdn.microsoft.com/en-us/library/gg588378%28v=vs.92%29.aspx

2. Version history
--------------------------------------------------------------------------------
* Version 1.1.0.3:
  * Updated to use latest Lumia SensorCore SDK 1.1 Preview
* Version 1.0.0.1: 
 * Some bug fixes made in this release.
* Version 1.0: The first release.

3. Downloads
---------

| Project | Release | Download |
| ------- | --------| -------- |
| Steps | v1.1.0.3 | [hello-sensorcore-1.1.0.3.zip](https://github.com/Microsoft/hello-sensorcore/archive/v1.1.0.3.zip) |
| Steps | v1.0.0.1 | [hello-sensorcore-1.0.0.1.zip](https://github.com/Microsoft/hello-sensorcore/archive/v1.0.0.1.zip) |
| Steps | v1.0 | [hello-sensorcore-1.0.zip](https://github.com/Microsoft/hello-sensorcore/archive/v1.0.zip) |

4. See also
--------------------------------------------------------------------------------

The projects listed below are exemplifying the usage of the SensorCore APIs

* Steps -  https://github.com/Microsoft/steps
* Places - https://github.com/Microsoft/places
* Tracks - https://github.com/Microsoft/tracks
* Activities - https://github.com/Microsoft/activities
* Recorder - https://github.com/Microsoft/recorder
