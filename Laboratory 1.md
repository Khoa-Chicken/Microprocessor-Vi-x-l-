**Lab 1 consists of:**
+ Lab 1-1
+ Lab 1-2

**Lab 1-1: I/O COMMUNICATION AND COMPUTATIONAL INSTRUCTIONS**

_EXERCISE 1:_

a) Connect one AVR port (e.g., PORT A) to a DIP switch. Connect another port (e.g., PORT B) to a bar LED.  
b) Write a program that continuously reads the state of the DIP Switch and outputs it to the LED. If the switch is OFF, the corresponding will turn off.  

**.ORG 0** <br>
LDI R16, 0X00 <br>
OUT DDRA, R16 <br>
LDI R16, 0XFF <br>
OUT PORTA, R16 <br>
LDI R16, 0XFF <br>
OUT DDRB, R16 <br>
**MAIN:** <br>
IN R17, PINA <br>
COM R17 <br>
OUT PORTB, R17 <br>
RJMP MAIN

_EXERCISE 2:_ 

