# HDL-language
1_Operation

We've designed a digital calculator using VHDL, a special language for describing how digital circuits work. 
This calculator can handle four main operations: addition, subtraction, division, and multiplication. Think of it 
like a digital math machine with buttons. Each operation corresponds to a button: addition is like pressing one button, s
ubtraction is another, division is a third (but it won't divide by zero), and multiplication is the fourth. The calculator takes two sets 
of numbers, each with 8 switches that can be either on or off .

2_Three bits counter

This counter counts upward, starting from zero and going up to seven. It's designed to work 
with a clock signal (clk) that synchronizes its actions, and a reset signal (reset) that can bring the count back to zero when needed. 
The count itself is represented by a sequence of three bits, which means it can represent numbers from 0 to 7. The counter follows a clock's 
rhythm and increases by one each time the clock's rising edge occurs. When it reaches the value 7, it wraps around back to 0 to continue counting. 
If the reset signal is activated, the counter is immediately reset to 0, ready to start counting again from scratch.

3_ 4-1 Multiplexer
You can choose which light you want to turn on using two buttons (Select). 
The chosen light's status shows up on a screen (Output). Pressing the buttons changes the active light. For example, pressing "00" turns 
on the first light, and so on. It's like a basic version of how we make choices using switches.

4_ Decoder
when you press "Button A," the TV understands this as a request to turn on the gaming console. When you press "Button B," 
it turns on the DVD player. If you press both "Button A" and "Button B" together, the TV gets the idea to power up the streaming device. 
And if you don't press any buttons, all the devices remain off. 

5_Finite State Machine

The Finite_State_Machine entity has inputs for the clock (clk), reset (reset), and an external input signal (input), as well as an output signal (output).
Inside the architecture, the FSM has four states: S0, S1, S2, and S3. The FSM transitions between these states based on the current state and the input signal. 
When the FSM reaches state S3, the output signal is set to '1', and in all other states, it's set to '0'. FSMs are widely used in digital design for tasks like 
control units in microprocessors, protocol handling, and more, making them a critical concept in hardware description and digital systems design.
