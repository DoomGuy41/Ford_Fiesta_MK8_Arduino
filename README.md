# Ford_Fiesta_MK8_Arduino
Sketchs for the 2017-202X Ford Fiesta cluster.

![sticker](https://user-images.githubusercontent.com/50769444/213868594-2f3691b8-ee1e-498c-816d-09e9d7061a24.png)

Can code and can frame came from InfoX, github repo : https://github.com/InfoX1337/xConnect-hardware/tree/fordMK8
All credit for the can research mainly go to him.

This repo will include everything i found/Made for the mk8 cluster.
There is a Static sketch you can use to test your setup

# Connecting the cluster

You will need a 12v DC power supply, 
An arduino with a mcp2515 or SeedStudio can bus shield
If you want to use the menu keys (you will want at least the ok key to clear the message on the screen )

Pinout : 

Pin 2 : Fuel level return

Pin 3 : Ground

Pin 8 : 12V DC

Pin 10; Fuel Level

PIN 12 : HS CAN HIGH

PIN 13 : HS CAN LOW


Connect a 180 ohm resistor between fuel level and fuel level return to max the fuel gauge, it's not controlled by canbus.

