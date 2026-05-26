# Electrical wiring:


## Wiring diagrams:

## Main ESP32 hub wiring :
This is the wiring of the ESP32, which is going to act as the access point for all the other ESP clients. The MAX9841 module is connected to this because this hub is going to be activated whenever a specific clap pattern is detected. The servos that are seen to be connected with this ESP32 are here because this ESP32 is going to control the windows of our smart home. Whenever rain is detected through the weather monitoring system, the weather monitoring system will let the hub know about the rain, then the hub will shut all of the windows down. 

![1000019545](https://stasis.hackclub-assets.com/images/1778652293434-dqcpsy.jpg)

## Safety protocols (smoke, gas leakage and fire protection):
This particular ESP32 is dedicated for ensuring safety, which is, in this case, safety from smoke, gas leakage (LPG gas from the kitchen), and last but not least fire protection. One of the MQ-2 sensors seen here is for detecting smoke that is caused before the fire incident even occurs and the other MQ-2 sensor is here to detect LPG gas leakage. And one of the fire sensors is for detecting direct fire accidents and the other is to check if our stove is turned on or off. 



![1000019544](https://stasis.hackclub-assets.com/images/1778652389294-p0ibzd.jpg)

## Plant Monitoring System:
This system looks a bit different than the others because there is a relay included here. This is a 5 V relay module that is going to drive the water pump for us. The water pumps draw more currents than the ESP can provide it with so we are going to be using a relay to provide the power needed for the water pump. The ESP32 is going to activate the relay, which means we still have full control over our motor pump, except for its speed, of course. It just sends digital signals across the relay to turn the water pump on whenever the sensor detects that the soil moisture level is low. 

![1000019542](https://stasis.hackclub-assets.com/images/1778652611592-n4q81s.jpg)

## Security System (Invasion Prevention):
In here we can see another ESP32, which is dedicated to the security system for our smart home, which basically prevents our home from being intruded. 
I've designed this system with extra security:
- with one PIR motion sensor which has a long range and a wide angle of detection field
- and the other system is the laser security system which mainly can detect anyone crossing the laser along a straight line


We can cover our whole home with this laser system by using mirrors at 90 degrees or whatever angle we need the light to reflect to. 
![1000019543](https://stasis.hackclub-assets.com/images/1778652787888-n35im0.jpg)

## Weather Station:
This weather station is capable of detecting three types of data from the environment, which are:
- temperature
- humidity
- the presence of rain
 But to get this data we only need two sets of sensors:
1. The famous DHT22 sensor, which can detect the amount of humidity in the air (air moisture). It also detects the temperature of the environment.
2. The rain sensor, which uses a sensor panel that measures the electrical conductivity between two poles of the sensor and then decides, based on the data, if it is raining or not.
 
![1000019541](https://stasis.hackclub-assets.com/images/1778652952024-ektnmg.jpg)

---


