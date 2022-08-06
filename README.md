# ESP-32-Weather-Station
Weather station that can send data to you via wifi. Meausres temperature, pressure, humidity. Also detects Lightning.

I wanted a weather station that could send data to me over wifi. This is it, it uses a BME-280 Sensor for temperature, pressure, and humidity. It uses an AS3935 Franklin lightning detector and 100nH coil for lightning detection. I initially prototyped it using the Sparkfun breakouts for those sensors, and then integrated everything into a PCB. Whole system centeres around the ESP-32 WROOM 32D module. The Blynk platform is used to stream the data over wifi for now.

Here is the board rendered in Eagle:

![board](https://github.com/jshenns/ESP-32-Weather-Station/blob/main/WeatherBoard_1.1.png)

Here is the board IRL:

![board](https://github.com/jshenns/ESP-32-Weather-Station/blob/main/IMG_0197.jpg)
