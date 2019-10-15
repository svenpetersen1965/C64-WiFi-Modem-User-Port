# C64-WiFi-Modem-User-Port
A NodeMCU (ESP8266) based WiFi modem for the C64's user port
This is a Wifi-Modem for the Commodore C64 Uperport, which is based on the ESP8266 (NodeMCU v3). It contains level shifters to 
translate between the NodeMCU 3.3V level and the User Port 5V level. This prevents stressing the User Port due to a level mismatch.

Further on, status LEDs and (in Rev. 1) a Reset switch is contained.


<img src="https://github.com/svenpetersen1965/C64-WiFi-Modem-User-Port/blob/master/Rev.%200/pictures/2286_-_C64_WiFi_Modem_v0.JPG" width="300" alt="C64 Wifi modem">

About the NodeMCU v3: There is a version, which is wider. The version that work is WeMOS NodeMCU v3, which is about 25.4mm wide. You can compare it to this picture, please. The right one has the labeling of the pins parralel to the edge of the PCB. 

The wiring follows the instruction on https://1200baud.wordpress.com/2017/03/04/build-your-own-9600-baud-c64-wifi-modem-for-20/ 

The firmware, required for the NodeMCU, can be obtained from the same website. Please follow the setup procedure described there.

Now, the STL files for a 3D printed case are available for this project.

<img src="https://github.com/svenpetersen1965/C64-WiFi-Modem-User-Port/blob/master/Case/Rev.%200/pictures/2653_WiFiMod_Case.jpg" width="300" alt="C64 Wifi modem (case)">

There are three types of reset switch plungers for some common tact switch heights (4.3mm, 5mm and 7mm).
