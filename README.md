## About this repository

This repository contains a proof of concept gaze detection Android app.

This work integrates code from the following open-source projects:
* [OpenCV](https://github.com/Itseez/opencv) the major open-source computer vision library.
* [Cambridge face tracker](https://github.com/TadasBaltrusaitis/CLM-framework): a Constrained Local Model (CLM) framework developed by Tadas Baltrušaitis from the University of Cambridge.
* [dlib](http://dlib.net/): a C++ library for machine learning.
* [dlib-android-app](https://github.com/tzutalin/dlib-android-app) integrates dlib library in Android.
* [Boost](https://github.com/DraXus/Boost-for-Android): a collection of C++ libraries.
* [Weka](https://github.com/rjmarsan/Weka-for-Android): the main library for machine learning algorithms.

### Here be dragons

This project is in a highly experimental state. We are not responsible for any damage that can happen to your device. Currently the app has been tested in the following devices:
* Nexus 10
* Samsung Galaxy Note 10.1

### Download

Note: Currently the APK only works for devices with ARMv7-a processor.

[gaze-detection.apk](demo/gaze-detection.apk)

### Install

Enable installation of apps from unknown sources in the settings of your device. Then open the APK file from your device to install it.

From command line: `$ adb install demo/gaze-detection.apk`

### Get the sources

`$ git clone https://github.com/DraXus/gaze-detection-android-app`

`$ git submodule update --init --recursive`

### Development

The project is ready to work in Android studio 1.5.

Requirements:
* Android SDK 23 (min API level is 18)
* Android NDK 10e

### License

See LICENSE file.
