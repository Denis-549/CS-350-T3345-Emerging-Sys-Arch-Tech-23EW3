# CS-350-T3345-Emerging-Sys-Arch-Tech-23EW3
CS-350 Final Project 
Summarize the project and what problem it was solving.
The purpose of the ‘Morse Code’ Project was to design a synchronous state machine that creates a pattern of blinking lights from the LEDs on a CC32xx board. This pattern was to contain a message in Morse code. When a button is pressed, the Morse code message of the blinking LEDs would change. Code was created that initializes the timer and uses it to drive the state machine.

**What did you do particularly well?**
Being able to develop code for all of the specified functionality that successfully implemented functionality of both the state machine and the button change was a great achievement. 

**Where could you improve?**
I paid much attention on the code accurately reflecting the state machine documentation, rather than for it to have perfect functionality, hence the code could have been simplified further to have the inputs in the transition arc, rather than within if statements.

**What tools and/or resources are you adding to your support network?**
Using both CCS, as well as the experience in programming the MCU. Being that I had no prior experience with using CCS or programming a smart ‘thermostat’ I think these alone will give me reason to continue to explore the field of emerging systems architecture and technology. 

**What skills from this project will be particularly transferable to other projects and/or course work?**
Much of the skills in understanding code structure, timer and interrupt drivers, as well as my understanding of embedded systems, will be needed and/or transferable to other course work and projects.

**How did you make this project maintainable, readable, and adaptable?**
Compartmentalizing my code, adding inline comments as needed and keeping code clean and easy to follow whenever possible. This will allow for edits to be done relatively easily to obtain the desired output.

**Thermostat Project**

**Summarize the project and what problem it was solving.

For this project, the goal was to develop a thermostat that sends data to a client’s server software over Wi-Fi, but first goal was to create a prototype of the low-level thermostat functionality working. For the prototype, TMP006 temperature sensor was used to read the room temperature (via I2C), an LED to indicate the output to the thermostat where LED on = heat on (via GPIO), two buttons to increase and decrease the set temperature (via GPIO interrupt), and the UART to simulate the data being sent to the server.

**What did you do particularly well?**
Creating the code that used interrupt to detect button presses, which involved two steps, the detection of the button presses and then using the result to run an action. There was a lot of troubleshooting and trying of various methods involved, but I think the process of creating the code as per the specifications was relatively well done. 


**Where could you improve?**
Understanding how and or when exactly to refresh and run or debug. There seemed to be a lot of loss of connection or ‘communication’ between CCS and the launchpad which let to me spending a lot of time trying to figure out whether it was a configuration issue or a functionality one. 

**What tools and/or resources are you adding to your support network?**
CCS again is  a relatively new tool to me so that is a new addition to my list of IDE’s. Paying attention to or reading the header files of the drivers in use is also very helpful.

**What skills from this project will be particularly transferable to other projects and/or course work?**
Understanding how code woks in embedded systems and how code enables peripherals to work or perform tasks is a skill that will be transferable to future projects o courses.

**How did you make this project maintainable, readable, and adaptable?**
A clean, well commented, logically put together code that is easy to follow was my approach throughout this project. I added a lot of inline comments to explain lines of code, variables, functionality, loops, etc. 
