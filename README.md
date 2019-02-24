**put into operation a weather station** 
The parts of our example Wind / Rain Sensor Assembly, Argent Data Systems 80422
( windspeed, wind direction, rainfall, plastic box for our controller & body ) purchased 
by commonslabgr and they also feed us back with many of the information given below

also needed

**a nodemcu32 controller**

an analog to digital converter

**12-Bit ADC- 4 Channel with Gain Amplifier ADS1015**

and our sensors

**adafruit bme280 (temperature, barometric pressure and air humidity)**
**Light Sensor 70000 lux ID: 1143_0**
**SparkFun Soil Moisture Sensor**

all these data from controller will be visible by GNU/Linux system that runs the Domoticz server
in our example 
**raspberry pi (also need charger sd card and maybe a box)**

You will need one meter dupont cable per color (5 x 1m).

Both female and male pins. 
A tool to connect and cut 
or 
You can purchase ready made ones, 10-20 cm mix female & male to male & female

also an access point (simple router)  that nodemcu32, the raspberry and the users would all be connected to, in order to be able to check the weather info 

Step1

You need to flash the nodemcu32 controller with the ESPEASY firmware (https://www.letscontrolit.com/wiki/index.php/ESPEasy)
after that
**Restart ESP. WiFi AP "ESP_Easy_0" will appear, password: configesp** 

