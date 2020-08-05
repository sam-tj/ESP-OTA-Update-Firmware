# ESP OTA Update Firmware

Use this to upload your personal codes via ota updates. 

This is only the base firmware file, so you would need add the OTA commands to your new codes too.

This will create a WiFi access point through which you can connect the ESP to your local wifi router and then install the file via OTA from a URL. Here for demonstration GitHub is used to upload file to ESP (NodeMCU 1.0).

**ESP SSID :** ESP-OTA @ [192.168.4.1] *// can differ also, still fixing*

**ESP Password:** Open Connection thus not required.

**ESP config IP:** 192.168.4.1

**URL Allowed:** Only with SSL i.e. https

**URL Specification:** Use URL without "HTTPS://" *//adds this automatically*

**Serial Monitor:**  @ 115200  *//to track the process.*

Can follow steps from this tutorial, works for ESP too. https://link.medium.com/SGc23dBYH8 
.


.


.


.


.


.

Created using library by tzapu, can refer this https://github.com/tzapu/WiFiManager
