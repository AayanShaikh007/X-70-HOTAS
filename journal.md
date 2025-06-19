---
title: "X-70 HOTAS"
author: "@Scalar"
description: "A throttle and joystick HOTAS system for flight sims."
created_at: "2025-06-16"
---

# June 16th- spent 4 hours planning. 
I spent most of today setting my goals for the project. In summary, I want to make a HOTAS system that resembles the X-56 HOTAS by Logitech, since I like its design. 

Ideas for CAD design
- X and Y moving body, detect position via hall effect sensors
- Ergonomic flight stick
- Analog trigger spring mechanisms

Ideas for electronics
- Force feedback
- Use FreeJoy and any STM32F103 ("Blue Pill"). This removes the need for software. 
- Hall effect (Trigger, X-Y axis sensing)
- 2 Hat switches
- 5 buttons, 3 top, 2 sides. 
- One trigger switch. 
- OLED display
- RGB panel on back of body (backlight will be viewable.

X-56 HOTAS By Logitech
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



