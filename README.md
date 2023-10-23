# CS350EmergingSystemsArchitecturesAndTechnologies

## Summarize the project and what problem it was solving.
For this project, we were asked to develop code to run on a microcontroller with GPIO, UART, I2C, and Timer capabilities. We were supposed to develop a prototype for a smart thermostat. The system would interface with temperature sensors via I2C. The user is able to interact with two buttons to adjust the setpoint temperature. If the setpoint temperature was higher than the current room temperature, an LED light would turn on to indicate heating. If the setpoint temperature gets lower than the current room temperature, the LED light should turn off to indicate that the heater is off. The code was also supposed to implement a task scheduler to execute tasks at specific times throughout each time period cycle. 

## What did you do particularly well?
For this project, I found the light controls were the easiest to implement, so I like to think I did that well. I also kept my code as neat as possible. 

 ## Where could you improve?
I got a bit confused when it came to the Timer functionality. Although my project works as it should, I would like to become more familiar with how to set up the timer in a way that’s more modular. 

## What tool and/or resources are you adding to your support network?
I was pleased to learn about the “Open Declaration” option in Code Composer Studio. It was very helpful in situations like this where I was not familiar with certain functions. 

## What skills from this project will be particularly transferable to other projects and/or course work?
This was my first time implementing a timer and a task scheduler into my code, and I think this project was a good learning experience to expand on my current coding knowledge. I also think my knowledge on working with embedded systems will be useful in my future projects. 

## How did you make this project maintainable, readable, and adaptable?
I tried to keep the code as modular and neat as possible. I used helpful variable and function names, and added comments that could explain what my code was doing. Keeping the format consistent is important to me, so I made sure to do that as well. 

