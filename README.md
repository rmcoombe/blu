# Cordova sample app - cordova-plugin-bluetoothle
Visual Studio Tools for Apache Cordova combines the goodness of your favorite IDE with the ease of creating apps for multiple mobile operating systems, all in a simple to use workflow. One of the major pain points for our enterprise developers is the effort required to build apps for multiple platforms, while keeping costs and effort down. Visual Studio Tools for Apache Cordova allows developers to use HTML5 and JavaScript, along with their favorite open source framework libraries to build web applications.

Leveraging the Apache Cordova framework, we create packaged mobile apps that feel and behave like native device applications. What's great is that all this can be done completely from within Visual Studio, with full tooling support for building, debugging and packaging that our customers love. Our highlight features include attaching and debugging to the Android emulator and devices, plus, being able to build and simulate remotely for the iOS platform.

The cordova-plugin-bluetoothle sample lets you discover Bluetooth Low Energy (LE) devices that are around you, connect to a one, and then look at all of the information that you can obtain from that device such as signal strength, supported services, battery level and more.

You could use an app like this to find a lost device or to debug a device that isn't behaving as expected.

Our code performs these tasks.

* Initialize the BluetoothLE adapter.
* Scan for devices.
* Connect to a device.
* Show device services.
* Show service characteristics.

This sample has support for Android and Windows devices but there is no reason why this code could not be extended to support iOS devices as well. 

## Building and running the sample

You can run this sample with or without Visual Studio.

If you choose to use Visual Studio, you can download [VS Community 2015 in English](http://go.microsoft.com/fwlink/?LinkId=524433) (or [go here for other languages and editions](http://www.microsoft.com/click/services/Redirect2.ashx?CR_CC=200626830)). Don’t forget to check “Tools for Apache Cordova” during setup. After you have Visual Studio 2015 installed, you can open up the project in Visual Studio. In Visual Studio, choose File->New->Project from Existing Code. Then, choose the folder of this sample.

Press F5 and you're on your way! If you haven't already done so, consider taking a look at our landing page for more information (http://go.microsoft.com/fwlink/?LinkID=398477).

## Terms of use
By downloading and running this project, you agree to the license terms of the third party application software, Microsoft products, and components to be installed.

The third party software and products are provided to you by third parties. You are responsible for reading and accepting the relevant license terms for all software that will be installed. Microsoft grants you no rights to third party software.

## License
```
The MIT License (MIT)

Copyright (c) Microsoft Corporation

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Help us improve our samples
Help us improve out samples by sending us a pull-request or opening a [GitHub Issue](https://github.com/Microsoft/cordova-samples/issues/new)

## More Information
Email us at multidevicehybridapp@microsoft.com
