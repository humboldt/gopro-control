GoPro Control
=============

GoPro Wifi controller inside the gopro

##How to:

1. [Click here to download this repo](https://github.com/KonradIT/gopro-control/archive/GoProControl.zip)
2. Unzip the GoProControl.zip file
3. Copy index.html and autoexec.ash to the root your GoPro SD card (where DCIM and MISC are)
4. Insert card back into the gopro, **turn wifi on first and then turn on the gopro**
5. You will see that the red front LED stays bright, wait till the led turns off
6. Then connect to the GoPro wifi with your device (computer/iPhone/raspberry pi/etc)
7. Go to 10.5.5.9:8080/live in your browser, type your wifi password and start controlling


#To Do:
[X] One Autoexec.ash for all, remove extra steps

[ ] Fix version.txt iframe to parse the Version/Model to show only appropriate options

[ ]	Preview 

[ ] Responsive

[ ] Show camera modes, resolutions, etc... 

~~[X] Make a dir in var/www or something that its not live or videos (both dirs are needed for the controller)~~

[ ] Write a tcp_tuner.sh version.



#Demo:

###Mac:
![Wifi Controller Interface](http://i.imgur.com/Bd86u0i.png)

---

###Ubuntu:
![interface on linux](http://i.imgur.com/rdDLCaS.png)
