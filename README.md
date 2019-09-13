# C64-WiFi-Modem-User-Port
A NodeMCU (ESP8266) based WiFi modem for the C64's user port
This is a Wifi-Modem for the Commodore C64 Uperport, which is based on the ESP8266 (NodeMCU v3). It contains level shifters to 
translate between the NodeMCU 3.3V level and the User Port 5V level. This prevents stressing the User Port due to a level mismatch.

Further on, status LEDs and (in Rev. 1) a Reset switch is contained.


<img src="https://github.com/svenpetersen1965/C64-WiFi-Modem-User-Port/blob/master/Rev.%200/pictures/2286_-_C64_WiFi_Modem_v0.JPG" width="300" alt="C64 Wifi modem">

The wiring follows the instruction on https://1200baud.wordpress.com/2017/03/04/build-your-own-9600-baud-c64-wifi-modem-for-20/ 

The firmware, required for the NodeMCU, can be obtained from the same website. Please follow the setup procedure described there.