# ESP8266 Weather Station
The simplest weather station using ESP8266 & DHT11 sensor with Thingspeak integration.

### Components:

1. ESP8266 (NodeMCU)
2. DHT11

### Hardware Setup

Connect all components according to the circuit diagram.

### Circuit Diagram

![esp8266-dht11-diagram](./images/esp8266-dht11-diagram.png)

### NodeMCU v3 CH340 Pinout Diagram

![nodeMCU V3 pinout diagram](https://www.mischianti.org/wp-content/uploads/2021/10/NodeMcu-V3-CH340-Lua-ESP8266-pinout-mischianti-low-resolution.jpg)

### Software Setup

- For NodeMCU module, Install [CH340 Drivers](https://learn.sparkfun.com/tutorials/how-to-install-ch340-drivers/all#drivers-if-you-need-them). 

- Install [ESP8266 Addon](https://randomnerdtutorials.com/how-to-install-esp8266-board-arduino-ide/) in [Arduino IDE](https://www.arduino.cc/en/software)

- Clone this code and open the folder with Arduino IDE

- Copy `secrets.h.example` to `secrets.h` and put your configurations. You need to create an aacount in Thingspeak in order to push weather data. [follow this link](https://in.mathworks.com/help/thingspeak/collect-data-in-a-new-channel.html)

- Select the Board (NodeMCU 1.0)

- Upload the sketch 

### Visualize data on Thingspeak

https://thingspeak.com/channels/1160774

![channel](./images/channel.png)