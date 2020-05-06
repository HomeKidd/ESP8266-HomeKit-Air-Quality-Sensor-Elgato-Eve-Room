# ESP8266 based  HomeKit Air Quality Sensor
ESP8266 based  HomeKit Air Quality Sensor using SHT3X for temperature and humidity measuring and AMS IAQ Core C for Co2 and VOC measureing.

------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/total?color=green)](https://github.com/HomeKidd/Homekit-WS2812B-controller/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>


For **Usage** please read the [Build Instructions](https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/wiki/Build-Instructions) Wiki page!<br/><br/>



**This HomeKit enabled sensor works the same as [Elgato EVE Room](https://www.evehome.com/en/eve-room)!** 


**Basic information**

**Features:**
* Indoor Air Quality Index
* Indoor CO2
* Indoor VOC density
* Indoor Temperature and Humidity measuring 
* Sensor Fault detection
* Support for **[SSD1306 OLED screen](https://s.click.aliexpress.com/e/_d7Bj0V3)** 
* Switching Temperature Display Units between Celsius and Fahrenheit
* Downloadable User Manual _(via Eve app)_
* Reset button 
* ~~Data history~~ (not reliable enough, so its beta)

**If you don't want to use OLED screen and SHT3X, please install the [latest 1.x.x release](https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/releases)!** 


This project is based on ESP8266 modul, a cheap [SHT3X](http://s.click.aliexpress.com/e/qAfJeXuk) temperature/humidity sensor, a [CO2 and VOC sensor](http://s.click.aliexpress.com/e/KJ7eKX6s) and SS1306 I2C bus [OLED Screen](http://s.click.aliexpress.com/e/ecIWJxcM) that can be found on AliExpress! **The sensor is the same that Elgato EVE Room has for indoor air quality monitoring!** 
</br>

<a href="http://s.click.aliexpress.com/e/KJ7eKX6s">
<img border="0" alt="" src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/raw/master/images/IAQ-CORE%20C.jpg" width="150">
</a> </br></br>




**Demo:**

<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/raw/master/images/homekid__iaq_mockup.JPG" width="550"/> </br>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/raw/master/images/Image_1.png" width="550"/> </br></br></br>


<img border="0" alt="" src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/raw/master/images/pcb_front.png" width="350">
<img border="0" alt="" src="https://github.com/HomeKidd/ESP8266-HomeKit-Air-Quality-Sensor-Elgato-Eve-Room/raw/master/images/pcb_back.png" width="350">

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2019 Apple Inc. All rights reserved.
