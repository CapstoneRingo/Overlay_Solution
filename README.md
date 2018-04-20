# Overlay_Solution
This folder contains all the software to run the inspection system, and overlay machine for the Ringo Capstone Project. 

Each of the tests provide code that can be run in a unix terminal with the commands:

"sudo python"                        % This opens a python terminal \n
"from RINGO import *"                % Import the Ringo Library		\n	
"r = RINGO()"                        % Initialize a Ringo object (this includes the TinyG and the Numato GPIO) \n
"execfile('Test1_Homing.py')"        % This executes a test/program \n

To run other function other than the Test1_Homing.py file, just put the file name of the program in the the single quotes. To run the full system use the Test5_BackingRemoval.py. 


