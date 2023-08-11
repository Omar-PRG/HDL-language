# HDL-language
1_Operation

We've designed a digital calculator using VHDL, a special language for describing how digital circuits work. 
This calculator can handle four main operations: addition, subtraction, division, and multiplication. Think of it 
like a digital math machine with buttons. Each operation corresponds to a button: addition is like pressing one button, s
ubtraction is another, division is a third (but it won't divide by zero), and multiplication is the fourth. The calculator takes two sets 
of numbers, each with 8 switches that can be either on or off .

2_Three bits counter

This counter is like a digital tally system that counts upward, starting from zero and going up to seven. It's designed to work 
with a clock signal (clk) that synchronizes its actions, and a reset signal (reset) that can bring the count back to zero when needed. 
The count itself is represented by a sequence of three bits, which means it can represent numbers from 0 to 7. The counter follows a clock's 
rhythm and increases by one each time the clock's rising edge occurs. When it reaches the value 7, it wraps around back to 0 to continue counting. 
If the reset signal is activated, the counter is immediately reset to 0, ready to start counting again from scratch.

3_ 4-1 Multiplexer
Think of this as a switcher for four different lights. You can choose which light you want to turn on using two buttons (Select). 
The chosen light's status shows up on a screen (Output). Pressing the buttons changes the active light. For example, pressing "00" turns 
on the first light, and so on. It's like a basic version of how we make choices using switches.
