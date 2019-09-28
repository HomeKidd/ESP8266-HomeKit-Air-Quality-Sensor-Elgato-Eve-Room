# ESP8266 based  HomeKit Air Quality Sensor

------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/total?color=green)](https://github.com/HomeKidd/Homekit-WS2812B-controller/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>


For **Usage** please read the [Build Instructions](https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/wiki/Build-Instructions) Wiki page!<br/><br/>

**Basic information**

This project is based on ESP8266 modul, a cheap [DHT22](http://s.click.aliexpress.com/e/bfv69KpK) sensor and a [CO2 and VOC sensor](http://s.click.aliexpress.com/e/KJ7eKX6s) that can be found on AliExpress! **The sensor is the same that Elgato EVE Room has for indoor air quality monitoring!** 
</br>

<a href="http://s.click.aliexpress.com/e/KJ7eKX6s">
<img border="0" alt="" src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/raw/master/images/IAQ-CORE%20C.jpg" width="150">
</a> </br></br>

**Features:**
* Indoor Air Quality Index
* Indoor CO2
* Indoor VOC density
* Indoor Temperature (only in 3rd party apps thanks Apple)
* Indoor Humidity
* Sensor Fault detection


**Demo:**

<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/raw/master/images/Image_1.png" width="550"/> </br></br>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/raw/master/images/Image_2.png" width="550"/> </br></br>

<img border="0" alt="" src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/raw/master/images/pcb_front.png" width="350">
<img border="0" alt="" src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor/raw/master/images/pcb_back.png" width="350">

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2019 Apple Inc. All rights reserved.
