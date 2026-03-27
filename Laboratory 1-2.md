<div align="center">
  
**LAB 1-2: DELAY USING INSTRUCTIONS**
</div>

_EXERCISE 1:_  
a) Given the following program:  
.include "m324PAdef.inc" <br>
.org 00 <br>
&emsp; ldi r16,0x01 <br>
&emsp; out DDRA, r16 <br>
start: <br> 
&emsp; sbi PORTA,PINA0 <br>
&emsp; cbi PORTA, PINA0 <br>
&emsp; rjmp star <br>
Connect PA0 to a measurement channel on the TEST STATION block and measure the waveform on the oscilloscope.  
<img width="656" height="685" alt="image" src="https://github.com/user-attachments/assets/7b63dcd2-fdd4-4e89-9724-ea7d33035a65" />
<img width="1376" height="878" alt="image" src="https://github.com/user-attachments/assets/c4773db0-0b69-445b-af61-560a43bd5dde" />




