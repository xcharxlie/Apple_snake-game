# Apple_snake-game

This is a verilog version of Apple-snake game which could be run on a 8*8 LED board attached on a DE1-SoC board. Controlling switches to change speed and also pressing buttons to adjust its moving direction to avoid collision with its own body. There's also a hex display board showing how many apples (scores) player got so far. Note that every movement or change could only achieved by one press at a time, so no matter how long the player holds the button, it will only be counted as one press. 
Clock-50 was used for simulation, but actually clock-15 was chosen in account of LED displaying effect.
