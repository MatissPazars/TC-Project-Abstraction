# TC-Project-Abstraction

This is an dedicated repository just for the TC project of building of demonstrating how an computer is actually able to go from simple literal 1s and 0s to the full modern application and use, such as this own website, Minecraft, understand code from modern programming languages and so on. 

Everyone has heard of the famous saying "computers are just 1s and 0s" or "A computer is just a bunch of transistors", but ... what does that actually MEAN?? 
Its easier to say than explain because if you would to ask most, they coudnt actually fully explain. Thus, here we will try to do just that - get to the full modern computer JUST from those same 1s and 0s and transistors. 

## LAYER I.
It is said that a transistor is a switch. But what does that actually mean? In reality - a transistor works like this: it has 3 pins - emitter (E), base (B), collector (C). If B is powered, E emits power. In an NPN-type transistor, base has to be connected to VCC and it will then be combined with C to be emitted as E, whilst in an NPN transistor B is connected to GND and C is divided into B and E. In both types, B is allowed to be much lower than C, this multiple difference is referred to as Beta (β). 

## LAYER II.
But where do those switches come into play? well - in logic gates. a transistor, just from what we found out about its workings in layer I is capable of building logic gates, or - expressions of logic. 
<img width="1480" height="551" alt="image" src="https://github.com/user-attachments/assets/68ee7e9a-3fc2-4f7e-b7b9-c9ba5afddfa5" />
In the image above (a screenshot from the video game CRUMBS), as you can see - the YES / BUFFER, NOT, AND, OR gates are constructed just by using 5 components: wires, resistors, buttons, LEDs and transistors. even though there is zero code or even a microcontroller 
attached, we are able to manipulate the LEDs output just by switching the buttons. and we can do so in many types, like for example the LED being on if EITHER of the 2 buttons is ON (this is the OR gate), or only if BOTH are on (this is the AND gate). 
