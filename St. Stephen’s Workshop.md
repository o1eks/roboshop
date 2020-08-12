# St. Stephen’s Workshop
## Document Links
1. [**General Information**](#gen-info)
2. [**Materials**](#materials)
3. [**Setup**](#materials)
4. [**Outline**](#outline)
5. [**Arduino Cheat Sheet**](#arduino-cheat-sheet)



<br />

##<a name="gen-info"></a>General Information
- Date: **April 5th**
- Time: **4:00 - 6:45 PM**
- Students: **20-25 kids**
- Space: **one big room**
- Program Managers: **Latasha Scott and Emily DeMazza**
- Main Contact: **Jeremy Kazanjian-Amory**

<br>

##<a name="materials"></a>Materials
- 5 Duck Tapes
- 2 packs of latter size paper
- One roll of string


<br>
##<a name="setup"></a>Setup
- Have 4-5 Chromebook’s + my Mac with installed libraries in online accounts 
- Break into groups of 4
- Materials for Kids (info papers)

<br>

##<a name="outline"></a>Outline
#### 1. Introduction (4:00 - 4:05)
Tell kids about Northeastern, about us, what our majors are and what is the main topic of today.

#### 2. Ice Breaker (4:05 - 4:15)
```
YOU HAVE
1 string attached to a roll of tape with 6 other students
1 target

TASK 
Work with your team to land the roll of tape as close to the bullseye (red dot) in the center of the target as you can

RESTRICTIONS
You must hold on to your string for the entire time
You must only hold your own string
You must not touch the tape
You must not touch the target

ADDITIONAL CHALLENGE
Try to beat your old score!
```

#### 3. Presentation (4:15 - 4:30)
Describe the engineering design process and how it should be used.

Problem -> Brainstorm -> Eliminate -> Develop -> Test -> Repeat

#### 4. Design Challenge (4:30 - 5:00)
```
YOU HAVE
Paper - 10 letter pages
Tape - 12"
String - 3 foot

TASK
Build a structure that will hold/support a cup as far from the table as possible in direction of the table plane.

RESTRICTIONS
Structure should be connected to the table top at least at one point.
You are not allowd to connect you structure to the floor and/or other objects.

CLARIFICATIONS
You can tape the cup

ADITIONAL CHALLANGE
How many pennies can you cup hold?

WINNING:
The team that puts a cup as far a possible from the table and supports as many pennies as possible.
```

#### 5. Presentation (5:00 - 5:15)
(intro to robotics and programming)

#### 6. Activity (5:15 - 5:30)
Program A Northeastern Student

#### 7. Robots Programming (5:30 - 6:00)
- Show the robots
- Explain the task to perform
- Write the program using pre-made functions
- Test code by running robots

#### 8. Design Robots (6:00 - 6:35)
- Modify the robot physically
- Extra: make it dance in the end!

#### 9. Reflection (6:35 - 6:45)
##### Questions for kids:
- What do you think engineers do? 
- How can the engineering process be applied in everyday life?
- What was the hardest part of today? The easiest? The most fun?

<br>


#<a name="arduino-cheat-sheet"></a>Arduino Cheat Sheet
The following functions are provided by the arduino library to be used by everyone:

## Functions:
`Robot()` - Creates a robot. Do not worry too much about what this means, just be sure to have it before your setup.

`begin()` - Turns on the robot. This should be at the top of your setup.

`moveForward(time_in_seconds)` - Moves the robot forward for the specified number of seconds.

`moveBackward(time_in_seconds)` - Moves the robot backward for the specified number of seconds.

`turnLeft(time_in_seconds)` - Turns the robot left for the specified number of seconds.

`turnRight(time_in_seconds)` - Turns the robot right for the specified number of seconds.

`stop()` - Makes the robot stop driving.

`wait(time_in_seconds)` - Makes your robot wait for the amount of time you told it to. Be careful because the robot will not be able to do anything during this time!

`blink()` - Lights up a small blue light on the robot's RedBoard.

`say(message)` - Makes the robot talk to the computer. Great for debugging!

## Examples:

To see examples, go to `File > Examples > Examples From Custom Libraries > Robot`

If you are using the web editor you can see the examples in `examples > libraries`


## Troubleshooting:
If you are having trouble, get a Northeastern student to help you!

Issue: Robot isn't moving when it is told to

Solution: Check your wiring! Either something fell out or you have things plugged in to the wrong place.

Issue: Code doesnt even run!

Solution: Make sure you have added the robot library to your project!


## Notes to Northeastern Students:
Remember that the pins must be configured to match the list below:
<table>
<tr><td>left wheel</td><td>11</td></tr>
<tr><td>right wheel</td><td>10</td></tr>
<tr><td>lift</td><td>9</td></tr>
<tr><td>button</td><td>6</td></tr>
</table>

Also remember that you are allowed to only use the pins you absolutely need, so non-CSTO sites are allowed to not have anything attached to pin 6 or pin 9.

If you or a student are having trouble getting the liibrary started, be sure to download the most up to date version and place it in the arduino libraries folder.

The libraries folder can be accessed by going to `Sketch > Include Library > Add .ZIP Library` and then selecting the ZIP file holding the library (probably in the downloads folder)

If you are using arduino online, the same thing can be achieved by going to the library tab and uploading the .ZIP as a custom library.

The most up to date download will be live 
[on my GitHub.](http://github.com/gracefullemming/sl-arduino-lib)
Once there, you can click the green clone or download button, and then download the .ZIP file

-------
This library and all related material was created by Caleb Trevino, and is not sponsored, endorsed, nor maintained by Northeastern University, Northeastern University College of Engineering, or Northeastern University Service Learning.





