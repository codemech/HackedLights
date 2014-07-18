HackedLights
============

A project allowing an Android client to control a Sylvania Mosiac Light strand.

The Android client communicates to an Arduino over Ethernet which in turn sends out the appropriate IR codes to the Sylvania Mosiac light strand.

This project depends on the folowing libraries (that you must download): 
                    IRremote   https://github.com/shirriff/Arduino-IRremote
                    
A pre-built version of the Android Client can be installed using the provided APK file, which was built using the debug keystore.

All credit goes to nwmotogeek for the Client APK etc, all I did was modify the sketch (lightStrandServer.ino) to work with the ethernet library and an ethernet shield (since I did not own the Adafruit CC3000 wifi module the sketch was designed for). 


