# dht22 Sensor
reading temperature and humidity using a dht22 sensor with Raspberry Pi 4

Add the following to /boot/config.txt
```
[all]
dtoverlay=dht11,gpiopin=21
```
GPIO Connection
```
5v = GPIO 2
GND = GPIO 6
DATA = GPIO 21
```
