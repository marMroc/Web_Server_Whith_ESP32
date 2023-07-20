# Web_Server_Whith_ESP32
To access the source code, [Click Here](https://github.com/marMroc/Web_Server_Whith_ESP32/blob/main/Web_server_ESP32.ino)

# 📋 Index:
- [Summary](#id01)
- [Components](#id02)
- [Schematc Circuit](#id03)
- [Libraries](#id04)
- [Challenges](#id05)
- [Learnings](#id07)

## Summary: <a name="id01"></a>
This project involves using a web page to connect to the ESP32 and control the activation of the LEDs (turning them on or off).

## Components: <a name="id02"></a>
- Two Leds
- Two resistors 220 ohms
- One DOIT ESP32 Board - ESP32-WROOM-32D
- One Protoboard

## Schematc Circuit: 
<a name="id03"></a><img style="width:500px;" src="https://github.com/marMroc/Web_Server_Whith_ESP32/blob/main/Circuit_Design.png" >

## Challenges: <a name="id05"></a>
Setting up and establishing the Wi-Fi connection between the ESP32 and client devices, as well as handling HTTP requests and responses appropriately to control the LEDs.

## Learnings: <a name="id07"></a>
- Understanding how to set up and establish a Wi-Fi connection between the ESP32 and client devices, and configuring the SSID, password, IP address, gateway, and subnet.
- Learning how to use the WebServer library to handle HTTP requests and responses appropriately, allowing the control of LEDs through the web page.
- Understanding how to integrate HTML and CSS into the web page served by the ESP32 to create a user-friendly interface for controlling the LEDs.
