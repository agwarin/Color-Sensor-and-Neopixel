# Color-Sensor-and-Neopixel
Adafruit Color Sensor with Neopixel LED Strip 

## How to Wire the LED Strip

Connect jumpers from:
* 5v -> 5V (red wire)
* GND -> GND (black wire)
* Dout -> 1 (Digital) (blue wire)


![alt text](https://code.nikiselken.com/img/LEDstrip_Uno.png "Wiring Diagram")


## How to Wire the Color Sensor

Connect jumpers from:
* 5v -> 5V (red wire)
* GND -> GND (black wire)
* SDA -> SDA (orange wire)
* SCL -> SCL (white wire)

![alt text](https://code.nikiselken.com/img/colorsensor_LED.png "Wiring Diagram")

Download this code: https://github.com/agwarin/Color-Sensor-and-Neopixel/blob/master/colorsensor_LEDstrip.ino

Remmber to add these two libraries via the library manager: 
Adafruit_TCS34725.h
Adafruit_NeoPixel.h

![alt text](https://code.nikiselken.com/img/arduinolib.png "Arduino LIbrary")
