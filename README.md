Hi there!

This little piece of software lets you control your SJ4000 Wifi Action Camera with an ESP8266.

Just turn on your Cam an let the ESP do the rest for you!

The sketch WIFI-Cam.ino starts a recording for approximately 5s and stops it later on.

The WIFI-Cam.bin (for 512k flash) is the the precompiled sketch you can flash on your esp8266 with esptool for example:
Linux:
sudo ./esptool -cp /dev/ttyUSB0 -cf WIFI-Cam.bin 
SSID of your Cam: SJ4000 	Passkey:123456789
It starts a recording for app. 5s and stops it later on

In future I will build a software which acts like a remote which you can wear on your wrist, like the remote for GoPro Cameras!.

Questions: Feel free to ask!

Big Thanks to charly_01 from :
http://metropolitanmonkey.com/forums/topic/fernbedienung-ohne-handy/
(German)
who had the original idea, which included an Arduino and an ESP8266.
I've just ported the idea to the ESP as a standalone piece of hardware.


Have fun and a good Day!
