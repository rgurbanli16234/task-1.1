# task-1.1
The built-in functions of Arduino to blink the LED are simple to use. Arduino constructs the main loop to send 5 volts to pin 13 which turns the LED on. Then the value of the pin is 13 to the digitalWrite function to send 0 volts to pin 13 which turns the LED off. The LED off command is followed by another 500ms break which completes the cycle of on and off commands.

Having the LED off for 500ms and on for 500ms during the 1000ms cycle total time for one on off cycle results in a blink of 1Hz. When you specify a pin and the state you want to use it in, the functions set all the complicated register settings and use it to perform the desired action.

Start Program
    ↓
Setup: Set pin 13 as OUTPUT
    ↓
Main Loop Starts
    ↓
Turn LED ON (5V)
    ↓
Wait 500 milliseconds
    ↓
Turn LED OFF (0V)
    ↓
Wait 500 milliseconds
    ↓
Repeat Loop
