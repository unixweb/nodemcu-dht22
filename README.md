# nodemcu-dht22

<img src="/NodeMCU-DHT22-Fritzing.png">

# Hardware Setup:

-  NodeMCU V3 <a href="http://amzn.to/2qlW5U8" target="_blank">- Link: NodeMCU V3</a>
-  DHT22  Sensor AM2302 <a href="http://amzn.to/2rUhpQr" target="_blank">- Link: DHT22 Sensor</a>

   This Sensor no need 1KOhm Resistor because is already installed on board

# Settings:

```
char* topic = "dht22";
char* server = "148.251.206.53";
char* hellotopic = "hello_topic";
```

You can change this setting in the Arduino Sketch with your parameters of MQTT-Server and Topic.

Have a look at this Article to find out your proper MQTT-Server <a href="https://blog.unixweb.de/public-mqtt-server-liste/" target="_blank">Public MQTT-Server List</a>

