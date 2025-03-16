# Kant MDM

A customized fork of Headwind MDM.

## Features

 - Enrollment to Android 7+ devices through scanning a QR-code
 - Work in "Application mode" without enrollment
 - Customize the mobile desktop design and available applications
 - Automatic deployment of applications through the web panel
 - Mobile device management: groups, configurations, device status
 - Setup the available mobile device capabilities (GPS, Wi-Fi, Bluetooth etc.)
 - Manage the automatic OS update mode on the mobile device
 - Extensible platform design allowing the custom plugin development
 - Collection of application logs in the web panel
 - Centralized configuration of corporate applications

## Quick start

Headwind MDM control panel is cross-platform (it is written in Java and uses Tomcat web server). However the best OS for the deployment of Headwind MDM control panel is Ubuntu Linux. 

 - Clone the project and build it (see BUILD.txt for details)
 - Install the web panel to the server by using the installer script
 - Open the web panel and follow the hints to generate a QR code
 - Perform the factory reset on your Android device, tap 7 times on the welcome screen
 - Follow the instructions to scan a QR code and enroll the mobile agent
 
## Contributing

Headwind MDM is a platform making corporate app development easier. We are happy to get more powerful plugins related to mobile device management. 

Please contact us on the [project website](https://h-mdm.com) if you'd like to:

 - develop a public plugin for Headwind MDM
 - suggest a feature
 - order the custom development
 - report a bug



