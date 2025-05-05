<h1>Home Security System Using Arduino Prototype</h1>

 ### [YouTube Demonstration](https://www.youtube.com/watch?v=a6iFQisk6Zk)

<h2>Description</h2>
My Senior Project is a prototype that utilizes an Arduino to build a home security system on Tinkercad. One of the arduino devices is programmed to prevent anyone from entering a home without authorization. There is a keypad door lock that requires a code for access and prevents unauthorized individuals from entering a home easily. I decided to make the password 12 characters long for security reasons, as it would be more difficult for burglars to crack. There is a red LED light that indicates the security system is active, and if you enter the passcode incorrectly, the LED light would stay red, and you would hear a buzzer beep in a low tone. In addition, the LCD screen will display “Wrong Code”. On the other hand,  if you enter the passcode correctly,  the other LED light, which is green, would light up and the buzzer would beep in a higher tone, indicating that the code is correct. The LCD screen would display “Door is Open” and later give you a countdown to when the door would close again. Once the door is closed, the entire system repeats and the LED light switches back to red. The other arduino device is programmed to have  a motion detection alarm that would help with intrusion detection. A motion detection alarm can alert homeowners to any movements outside of their home, helping detect potential intruders before they can get close and cause harm or theft. For this prototype, I coded the arduino to have a green light if an object is further than 60 inches, yellow light if an object is within 12 and 60 inches, and red light if an object is less than 12 inches away. The buzzer with the yellow light would beep at a slower rate compared to the red light. Overall, a home security system with a motion detection alarm and a keypad door deters intruders from attempting to break-in. Burglars are more likely to target homes without a visible security system because it is easier to break into and pose less risk of getting caught.

<br />


<h2>Languages</h2>

- <b>C/C++</b> 

<h2>Platforms Used </h2>

- <b>Tinkercad</b>

<h2>Project walk-through:</h2>

<p align="center">
Initial Setup: <br/>
<img src="https://i.imgur.com/C9SixFV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
System Activating:  <br/>
<img src="https://i.imgur.com/yqJz11z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wrong Code Entered (LED Light Stays Red and Door Remains Closed): <br/>
<img src="https://i.imgur.com/nNFuJ1O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Correct Code Entered (Door Opens and LED Light Turns Green):  <br/>
<img src="https://i.imgur.com/rtZpDd7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Countdown For Door:  <br/>
<img src="https://i.imgur.com/c8m4uAR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Distance Sensor Green Light (Object Is Further Than 60 Inches):  <br/>
<img src="https://i.imgur.com/olfK7NM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Distance Sensor Yellow Light (Object Is Between 12 and 60 Inches):  <br/>
<img src="https://i.imgur.com/DmqEBgH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Distance Sensor Red Light (Object Is Less Than 12 Inches Away):  <br/>
<img src="https://i.imgur.com/5lhserO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
