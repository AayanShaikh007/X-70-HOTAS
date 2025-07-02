# X-70 HOTAS
A throttle and joystick HOTAS system designed from the ground up. Modelled after the X-56 HOTAS. 

The X-70 HOTAS is a flight control system designed for use in flight sims and space sims. HOTAS stands for Hands on Throttle and Stick, and they are used to control planes in flight simulators just like how Airbus pilots and fighter pilots use a joystick to control the plane's movements. I designed both the throttle and the joystick in this project, down to the very mechanism that their motion relies on. The X-70 is highly customizable and has a bunch of useful features that increase realism, including landing gear and flap change levers, various customizable switches, and a touchscreen display that can be customized to activate more features and display data. 

I was motivated to make this project mainly by my own interest in flight sims but also due to the fact that there arent many HOTAS systems on the market right now that have a comparable amount of features for a reasonable price. For instance, the Turtle Beach VelocityOne flightdeck goes for around $500 CAD, which isnt very affordable. There is a lack of a affordable mid series detached HOTAS system that is still capable and reliable. 

## Software
I intend on using FreeJoy, a open source software to configure and run the joystick and throttle. It should allow me to easily configure the parts and make it much easier to debug issues and reduce workload since I wouldnt have to make a entire software just for the hotas. 

Freejoy: https://github.com/FreeJoy-Team/FreeJoy 


# BOM 
| Item                        | Amount | Bought? | Cost (CAD) | Total Cost | Notes                            | Link                                                  |
|-----------------------------|--------|---------|------------|-------------|----------------------------------|-------------------------------------------------------|
| Bluepill Microcontroller    | 2      | n       | 5.65       | 11.3        |                                  | [Link](https://www.aliexpress.com/item/1005004918334754.html) |
| usb c to a cables           | 2      | n       | 2.86       | 5.72        |                                  | [Link](https://www.aliexpress.com/item/1005007504310983.html) |
| toggle switches             | 6      | n       | 4.10       | 24.6        |                                  | [Link](https://www.aliexpress.com/item/1005001315963290.html) |
| potentiometers (7mm thread) | 5      | n       | 2.53       | 12.65       | cheapest option                  | [Link](https://www.aliexpress.com/item/1005005661105692.html) |
| rotary encoders (7mm thread)| 6      | n       | 4.83       | 28.98       | looking for alternatives         | [Link](https://www.aliexpress.com/item/1005007737001031.html) |
| large momentary switch      | 1      | n       | 6.63       | 6.63        |                                  | [Link](https://aliexpress.com/item/4001169879232.html) |
| large latching switch       | 1      | n       | 6.76       | 6.76        |                                  | [Link](https://aliexpress.com/item/4001169879232.html) |
| mini joysticks              | 3      | n       | 2.17       | 6.51        | kinda small but should work      | [Link](https://www.aliexpress.com/item/1005007260466379.html) |
| large rgb metal button      | 2      | n       | 1.92       | 3.84        |                                  | [Link](https://www.aliexpress.com/item/4000830670631.html) |
| hat switches 8 way          | 3      | n       | 4.57       | 13.71       | should be able to print cap      | [Link](https://www.aliexpress.com/item/1005002969535551.html) |
| tricolor landing lights     | 3      | n       | 3.31       | 9.93        |                                  | [Link](https://www.aliexpress.com/item/1005006314855864.html) |
| Nextion Enhanced            | 1      | n       | 27.2       | 27.2        | lots of models, shipping will vary | [Link](https://www.aliexpress.com/item/4001240732911.html) |
| 5x11x5 bearings             | 2      | n       | 1.38       | 2.76        |                                  | [Link](https://www.aliexpress.com/item/1005006224445582.html) |
| m5x22 max screws            | 4      | n       | 0.51       | 2.03        | different size                   | [Link](https://www.aliexpress.com/item/1005005879037174.html) |
| M3x0.5 by 7 max screws      | 6      | n       | 1.38       | 1.38        |                                  | [Link](https://www.aliexpress.com/item/1005004527586307.html) |
| m5 by 30 max screws         | 8      | n       | 0.42       | 3.36        | different size                   | [Link](https://www.aliexpress.com/item/1005005879037174.html) |
| springs                     | 4      | n       | 5.01       | 5.01        |                                  | [Link](https://www.aliexpress.com/item/1005006443579464.html) |
| hall effect sensors         | 2      | n       | 8.39       | 8.39        |                                  | [Link](https://www.aliexpress.com/item/1005008473344808.html) |
