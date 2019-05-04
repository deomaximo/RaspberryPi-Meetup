#Welcome IoT Enthusiasts!

This is an exciting time we live in.  Working with IoT devices has never been so much easier.  With that said, we will be doing some very basic experiments with the Raspberry Pi.  I've placed some references for you to try. If you want to start early, you may try this on your own before we meet up.  Any problems you may have can be addressed at the meet up and in the common section and we'll try to answer the best we can.

##We will learn
+How to image a Linux OS
+How to connect it to WiFi
+Remote into the Pi using VNC and SSH shell
+Wire a circuit and run a simple C code to blink an LED and other simple projects
+Use the WiringPi

We hope to see you there.

We have a limit on seating so we may need to reserve the number of spots.

Please bring your PC, Mac or Linux laptop or you may have to share with someone which will be all right too.

Thanks,
-Pro

#REFERENCE MATERIALS:

This material: https://github.com/deomaximo/RaspberryPi-Meetup.git

Installing the Raspberry Pi OS:

https://www.raspberrypi.org/documentation/installation/installing-images/README.md
* If have your Raspbian OS ready, then you can use the 'rasp-config' to turn on the Wifi, VNC, SSH Shell and Remote GPIO.  Rename Pi to something unique that you can remember.  When you bring it the Meet-up and hook it up to the Wifi, we don't want duplicate names on the network.

https://www.raspberrypi.org/documentation/configuration/raspi-config.md

If you know the IP Address of your Pi and have managed to connect it to Wifi or an Ethernet

Download the VNC Viewer (version of your PC) to connect to your Pi 
https://www.realvnc.com/en/connect/download/viewer/windows/

Raspberry Pi Pin Outs
https://pinout.xyz/#

#Wiring Pi
http://wiringpi.com/
This is the GPIO utility that we will use for our experiment.  A basic copy is already built int your Raspbian OS.  Follow the instructions to update it.  This will also download the labs we will be using.

#Linux editor:
https://www.lifewire.com/beginners-guide-to-nano-editor-3859002

#SSH utility for Windows:
https://www.bitvise.com/ssh-client-download
Note that Linux and MacOS has their own SSH Shell utility built in.  SSH is the very best option for these labs simply because VNC Viewer might look different and may be harder to see.  SSH will create a remote terminal connection to your Pi, which you will be running even if you're using VNC Viewer.
