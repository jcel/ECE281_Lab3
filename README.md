ECE281_Lab3
===========

#Lab 3
##Moore and Mealy Elevator Machines

####Completed Sections
Moore Elevator
Mealy Elevator
Prime Number Elevator
LED Moving Lights

####Incomplete Sections
Two Elevators
Input Elevator

####Bug Reports
The biggest problem I had was understanding exactly what the program was attempting to accomplish, and what wanted
to go where.  The other major problem was that I had no idea what the 7-segment display was and what I should pass
to it.  After figuring out what they all did, I had no errors more major than a dropped semicolon.

####Design Process

######Moore Elevator
Once I figured out what was going on in the circuit, the elevator design was simple.  I just implemented the design
I already had within the code, and put the required signals where they were supposed to go.  The only major change
I needed to implement was the addition of an additional output to hold the 10's place for the SSEG.

######Mealy Elevator
This was really similar to the Moore Elevator in that the only major addition was an additional output to hold the
10's place.  There was some minor additions I needed to make to handle more floors as well.

######Prime Numbers
This was simple.  All I did was change the outputs to mirror the first few prime numbers.

######LED Movement
This was also simple.  I just needed to add an additional 8-bit output to control the LED's and have them move
according to what floor it was on.

####Code Critique

######Bad Code
######Good Code
