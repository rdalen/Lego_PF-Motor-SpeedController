## Lego Power Function (PF) Motor speed controller

I made my own versions of a speed controller for Lego PF motors after [this](https://www.toypro.com/nl/product/54279/power-controller-voor-lego-power-functions?gad_source=1&gad_campaignid=11441466193&gclid=CjwKCAjwravBBhBjEiwAIr30VCxSRBgGp-f_SLISsrgKkRwWOlxM40EZKS2sQz4RLvHa6dNschsDmRoCfCwQAvD_BwE) product.  
![Image](https://github.com/user-attachments/assets/9e3d2e8a-b6cb-4a86-9446-e1507b8d6cdc)

This module contains a commercial HW-70 PWM Motor Speed Controller Module.  
It is based on the well known NE555 timer-IC to make a PWM ouput signal.  
![Image](https://github.com/user-attachments/assets/246a8842-75a4-48c1-bdcb-1572a66c688f)  
![Image](https://github.com/user-attachments/assets/144847cf-f2c6-4271-a5c8-456ed3b9b372)

I bought a couple of these modules on AliExpress (for approx. 1€25 each) and made a small snapfit enclosure for it in FreeCad 
![Image](https://github.com/user-attachments/assets/31759234-456d-4af7-8029-7ed63e5ab469)

On AliExpress you can also buy the PF connector and wire to make a DIY Lego PF connection cable.  
When assembling the PF cable, remove the C1 and C2 contacts from the Bottom part of the connector
so that only 1 connector is required to connect both the battery box and the motor.  
![Image](https://github.com/user-attachments/assets/0d40d8c7-a8f0-4172-9ac3-674145432b49)

Because the output voltage cannot be reversed it is more suitable as an LED dimmer  
![Image](https://github.com/user-attachments/assets/ed3f1727-a2c3-4208-9fcc-59caea6877c4)

___
Below is a modified design where the motor can be changed direction using a DPDT switch.  
![Image](https://github.com/user-attachments/assets/1e96dd7b-d2d6-4f70-9284-a41b421fc728)

It fits in this larger snapfit enclosure
![Image](https://github.com/user-attachments/assets/e7473693-421f-427c-b7ac-a56a24c6cb52)

First of al the screw connector on the HW-70 Module is replaced by a header connector, after that all connections are soldered and tested  
![Image](https://github.com/user-attachments/assets/82504dd4-9452-4436-aa28-c76d377cdb24)

and mounted into the enclosure  
![Image](https://github.com/user-attachments/assets/daf7bcd2-0a5a-4f4c-8ba2-4b5ef4e62d98)

To make the stripes on the potentiometer scale, color in the lines with a black marker and wipe it clean with alcohol, leaving the stripes.  
![Image](https://github.com/user-attachments/assets/ec54525e-5fb4-407b-928f-b9bb997c7182)

___
I also made a [version](https://github.com/rdalen/Lego_PF-Motor-SpeedController_Neopixel-version) based on an Arduino ProMini (or clone) and has a DRV8833 Motor driver module, a Rotary encoder and a 16 LED Neopixel Ring as forward/reverse speedindicator

