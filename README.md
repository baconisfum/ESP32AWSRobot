# WebRover
ESP32-S1 AWS IOT MQTT Robot
This is a remote controlled ESP32 Rover car thingy that enables users to remotely control the robot from anywhere as long as WebRover has batteries and an internet connection.

# To recreate from code

## Hardware Component
1. Recreate WebRover using required electronic components and provided schematic.
2. Setup Arduino IDE to install the ESP32 board package.
3. Install these libraries: MQTT, arduinoJSON, and analogWrite ESP32.
4. Locate code in CPE400PA1. Fill out secrets.h with your device private key and device certificate generated at AWS IOT MQTT Things. 
5. Fill secrets.h with WiFi credentials and flash ESP32.

## AWS Amplify Component
# to do

## AWS Lambda Component
# work on this later
# 1. Create new lambda policy to publish to the AWS IOT MQTT topic dedicated to WebRover


