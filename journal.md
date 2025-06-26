---
title: "X-70 HOTAS"
author: "@Scalar"
description: "A throttle and joystick HOTAS system for flight sims."
created_at: "2025-06-16"
---

# June 16th- spent 4 hours planning. 
I spent most of today setting my goals for the project. In summary, I want to make a HOTAS system that resembles the X-56 HOTAS by Logitech, since I like its design. 

_Aims for CAD design_
- X and Y moving body, detect position via hall effect sensors
- Ergonomic flight stick
- Analog trigger spring mechanisms

_Aims for electronics_
- Force feedback
- Use FreeJoy and any STM32F103 ("Blue Pill"). This removes the need for software. 
- Hall effect (Trigger, X-Y axis sensing)
- 2 Hat switches
- 5 buttons, 3 top, 2 sides. 
- One trigger switch. 
- OLED display
- RGB panel on back of body (backlight will be viewable.

_X-56 HOTAS By Logitech_

![image](https://github.com/user-attachments/assets/8391991c-c408-4dea-9342-47d88dbdc711)

  
# June 17th- Spent 8 hours modelling flight stick.

- Designed pitch and roll mechanism, as well as the pitch mechanism holders. 
- Used Revolute feature (for the first time) to test movement in the Y axis, then the X axis. 
- Stick moves 18 degrees in the Y axis (along the longer side of the assembly), moves 15 degrees in the other X axis. 
- These are very good values- they are within or exceed the values of existing flight sticks. I am very happy that it worked and didnt require a bunch of trial and error. 
- I then tested movement in both axes to see if there are any conflicts. 
- According to the program, there should not be any problems when moving in both axes. Since I recently got a 3d printer, I will be able to prototype this before submission. 
- Sizing appears to be just right.
- Next, I will do some research on what specific hall effect sensor to use and where to place it. 
- Parts used for this iteration: 5x11x5 bearings, m5 screws, M3 by 7 max screws

_Image of the flight stick assembly that will be housed within the base._

![image](https://github.com/user-attachments/assets/118a3032-863b-4adc-beba-3a4ecb55e757)

# June 18th (early morning)- Spent 4 hours modelling. 

- Focused on designing the joystick itself. I started this part of the design process thinking it would take a lot of trial and error but if anything, it took a lot of thought to ensure that the parts would actually be ergonomic and fit real world dimensions.
- Used images of the X-56 as reference (didnt copy obviously) to base design off.
- Pretty happy with the result, I will do some more refining later as I alter the design for buttons and wiring. I am not completely satisfied with it, but I think that with some polishing it can look even closer to the Logitech X-56 that I am modelling it after. 
- One issue that was particularly annoying was the fact that it was difficult to simply make a shell of the outer design using the built in mode, so I will need to do it manually. 

![Screenshot 2025-06-18 152430](https://github.com/user-attachments/assets/90831db2-b497-4572-a511-8507b115e62f)
![Screenshot 2025-06-18 152437](https://github.com/user-attachments/assets/9efcb7ef-1b0a-4a72-bbda-8dc92de15e4b)

# June 18th (Evening)- Spent 5 hours modelling throttle.

- My aim for today was to finish the throttle design, and although I am pretty close to completion, I was unable to finish it completely. 
- To take a break from the joystick, I transitioned to working on the throttle design. 

_Aims for throttle_:
- RGB Lighting for Button Lettering, RGB backlight (back panel) 
- Various customizable switches
- System to add resistance to the throttle lever
- Split throttle design.

So far, I have completed the mechanism for the throttle- the position will be sensed by a potentiometer, and the throttle itself will move a total of 80 degrees if no future designs collide or interfere with it. It has been designed with tight tolerances with the hope that it would create some friction between the moving parts. My alternative method to add resistance to the throttle lever movement is two C-clamps that will compress the throttle lever body and increase the amount of friction it experiences. **It will be essential to print the parts in a very specific orientation so that the parts do not give the impression that they are 3d printed when moved.**

_Rough preview of the throttle body._

![image](https://github.com/user-attachments/assets/bdc15427-2ef7-4efe-bafa-80576de4d901)

# June 20th

Got busy with some assignments and the last day of school yesterday. With that out of the way now, I have a couple of changes that I would like to make to the project goals. Inspired by the turtle beach throttle, I have decided to add a rotary switch that can control flaps, a switch to control landing gear and a large LCD to show data. I may also add an oled display to the throttle as done in the turtle Beach throttle.

# June 24th- 6 hours worked 

Got some good progress done today. Firstly, I got a lot of progress in the throttle body design, and I am very happy with how it turned out. I have added a rotating knob that can be customized for various uses, and intend on adding a hat switch and some other switches in a bit. However, it probably doesnt look as good right now because I havent added the final touches to the appearance. 

![image](https://github.com/user-attachments/assets/8ce89e6f-b4d9-473f-8585-e2a95e146b34)


I also started resaerching IO options and arranged the layout for the IO on the throttle top shield. I will be using a variety of ~2cm toggle switches, a rotating switch, and **a flap setting lever**. This lever is going to be one of the most used parts on the throttle, so it is essential that I get it right.  

![image](https://github.com/user-attachments/assets/0a9fcdc6-da57-4854-a1c9-71503073a66d)

# June 25th and 26th- 2 Hours spent
