Make a micro:bit game controller with a potentiometer
--------------------
In this assignment you will connect a potentiometer to the micro:bit with alligator clips. You will then modify your egg catching game (or make a new game or other program) to use the potentiometer as a  controller. Here's a program that reads input from a potentiometer and uses it to move where a pixel is displayed.
```python
# Add your Python code here. E.g.
from microbit import *


while True:
    display.clear()
    num = int(pin0.read_analog()/206) #the integer part of the reading/206 range 0 - 4
    x = 4 - num        #reverse the values to match the direction of the potentiometer
    display.set_pixel(x,2,9)
    sleep(100)
```

You will submit the code and a short video of your program running. You may find slides 105 - 108 of the [slide presentation](https://docs.google.com/presentation/d/1aiGcnPn8uoCJdX8p7_qoI3Hh3_KOhUtFeB3Byw0tacA/edit?usp=sharing) helpful in completing this assignment.
  
Extensions
----------
You can create an entirley new program that uses a potentiometer as a controller, it is not necessary to create a game.

Samples of Student Work
----------
*none yet!*
