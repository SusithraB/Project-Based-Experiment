### Project-Based-Experiment

**AIM:**

To design and simulate the traffic light controller.

**SOFTWATE USED:**

Quartus II

**THEORY:**
	
     	Consider a controller for traffic at the intersection of three main roads.  

  ![image](https://github.com/naavaneetha/Project-Based-Experiment/assets/154305477/e3af03dd-a4de-4b21-af0a-a5a332a3e4b6)


 The traffic signal for all the three main roads have equal priority and they remain red by default.

 In state 00,the traffic signals remains red for first five counts and yellow of road1 turns on for the next four counts.

 In state 01, the green of road1 turns on for first five counts and yellow of road1 and road2 turns on for next four4 counts of this state.
 
 In state 10, the traffic signal of road1 comes back to the red and that of road2 goes to green for tee first five counts.For the next four counts the traffic signal of road2 and road3 remains yellow.


 In state 11, the traffic signal of road2 comes back to the red and that of road3 goes to green for the first five counts.For the next four counts the traffic signal of road3 turns to yellow

 At the end of four states,the traffic signal of all the three roads come back to red.

**Task Assigned**

From the HDL code given formulate the correct code  to divert the traffic to path 1 direction and disable the control in other directions (Assume user is at MR3 spot)

**Procedure**

1.	Type the program in Quartus software.
2.	Compile and run the program.
3.	Generate the RTL schematic and save the logic diagram.
4.	Create nodes for inputs and outputs to generate the timing diagram.
5.	For different input combinations generate the timing diagram
   
**Program:**
**Program to implement the given logic function and to verify its operations in quartus using Verilog programming**

**Developed by:SUSITHRA.B**
**RegisterNumber:212223220113**
![image](https://github.com/SusithraB/Project-Based-Experiment/assets/146347839/34c0d89d-897b-47ee-8973-7305b1084c37)
![image](https://github.com/SusithraB/Project-Based-Experiment/assets/146347839/2f946a32-c535-4320-b37d-42d15835966b)

**RTL Schematic**
![image](https://github.com/SusithraB/Project-Based-Experiment/assets/146347839/af3bbde8-edd3-4ad2-9321-74b60dad8d0d)

**Output Timing Waveform**
![image](https://github.com/SusithraB/Project-Based-Experiment/assets/146347839/0e58c0f0-5cd6-49b3-9d06-355987305f78)

**Result:**
Thus the program executed successfully



