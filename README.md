# Motion and Smoke detectionn IoT Project
This is an IoT Project that I have undertaken as an intern for Navtat Solutions
This is a collection of complete code used in interfacing Arduino/NodeMCU/ESP8266 with various sensors

The basic templates are taken from the Arduino IDE and are modified for various IoT, Robotics and mechanical projects. These projects are suitable for a home or apartment complex.

MQTT is the protocol used for communicating between the clients and sensors. Adafruit provides a free MQTT broker with impressive features to monitor, track and control your sensors and devices. Visit https://io.adafruit.com for more information.

Many of the methods used here require downloading and including the ESP8266Wifi, Adafruit_MQTT and Adafruit_MQTT_Client libraries in your Arduino IDE.

Contents
1. MQ Sensors - Uses the MQ series of gas sensors to detect and measure the quantity of smoke and impurities (depending on the model of the sensor) present in the air. This example uses the MQ-9 sensor but any sensor would work on making appropriate changes to the threshold value. 2.
2. PIR Motion Sensors - Uses the PIR motion sensor to detect motion in the terrace. Will send a signal to the cloud when motion is detected and subsequently, when it ends.
3. nodeMCU - The project uses the nodeMCU as the microcontroller
