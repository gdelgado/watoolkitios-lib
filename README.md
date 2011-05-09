Windows Azure Toolkit for iOS (Library)
===

The Windows Azure Toolkit for iOS is a toolkit for developers to make it easy to access Windows Azure storage services from native iOS applications.  The toolkit can be used for both iPhone and iPad applications, developed using Objective-C and XCode.  

The toolkit works in two ways – the toolkit can be used to access Windows Azure storage directly, or alternatively, can go through a proxy server.  The proxy server code is the same code as used in the WP7 toolkit for Windows Azure (found here) and negates the need for the developer to store the Azure storage credentials locally on the device.  If you are planning to test using the proxy server, you’ll need to download and deploy the server controls [hosted](http://watoolkitwp7.codeplex.com/) on CodePlex.  

The Windows Azure Toolkit for iOS is made available as an open source product under the Apache License, Version 2.0.  

## Downloading the Library

To download the library, select a download package (e.g. v1.0.0).  The download zip contains binaries for iOS 4.3, targeted for both the simulator and devices.  Alternatively, you can download the source and compile your own version.  The project file has been designed to work with XCode 4.

## Using the Library in your application

To use the library in your own application, add a reference to the static library (libwatoolkitios.a) and reference the include folder on your header search path.  The walkthrough document at http://www.wadewegner.com/2011/05/windows-azure-toolkit-for-ios/ provides a more thorough example of creating a new XCode 4 project and adding references to the library.

## Using the Sample Application

The watoolkitios-samples project contains a working iPhone project sample to demonstrate the functionality of the library.  To use this, download the XCode 4 project and compile.  Before running, be sure to enter your Windows Azure storage account name and access key in RootViewController.m.  Your account name and access key can be obtained from the Windows Azure portal.

## Contact

For additional questions or feedback, please contact the [team](mailto:wwegner@microsoft.com).