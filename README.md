# Binary-ASCII-to-Morse-Code

## Description
SystemVerilog code for DE-10 Lite FPGA that converts the binary value of mutliple switches using ASCII into the corresponding letter. Letter is then displayed using hex displays, and played using LED and buzzer if a button is pressed.

## Dependencies
This program requires an DE-10 Lite board, and the Quartus Prime application to set pins to the corresponding inputs and outputs. 

## Usage Instructions
1. Plug in DE-10 Lite FPGA into computer. 
2. Create new project in Quartus.
3. Add code file into Quartus and make top-priority.
4. Compile file in Quartus. 
5. Send program to board using USB blaster and Quartus. 
6. Switches are used to create binary value, with Up position = 1, down position = 0.
7. While displaying Morse code on displays, can press button to play Morse code on LED and buzzer.
