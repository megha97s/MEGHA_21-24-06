# D Latch using Pass Transmission Gate
D-latch using pass transmission gate is designed using 28nm CMOS technology by using Synopsys Custom Compiler


# Table of Content 
- ABSTRACT 
- INTRODUCTION
- TOOLS USED
- CIRCUIT DESIGN
- NETLIST
- ACKNOWLEDGEMENT 
- REFERENCE 


## ABSTRACT

The latch is a level-sensitive device and it is transparent when the clock is high if it is a positive level-sensitive latch and when the clock is low it is called negative level-sensitive latch. In this paper we design and do analysis of D Latch ( positive level-sensitive latch ) using Pass Transmission Gate using 28nm technology. In latch the output (Q) is dependent only on the level of the clock (Clk). In this latch D is control the output (Q).

# INTRODUCTION

Latch is a type of electronic device used to store one bit of information. D Latch is used to capture or latch the logic level used to present the data line whenever clock input is high. If the data on the D line changes state while the clock pulse is high, then the output, Q, follows the input, D. When the CLK input falls to logic 0, the last state of the D input is trapped and held in the latch. DSCH was used to design and analyse the D-latch using transmission gates. The input is given by switch and clock is provided such that its duty cycle is 50%. Inverters are also used here to maintain the memory state as well as proper functioning of transmission gates using CMOS using clock.
![image](https://github.com/Hiteshprp/d_latch/blob/main/Images/d%20latch.png)

D-Latch consists of one input as D and other as clock with output Q and Q̅. Herre, output Q depends on input D means whenever clock is High then output Q takes value of D and whenever it is low its output Q maintains previous value of D which we usually say, Memory state.

# TOOL USED

- Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

- Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

- Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

# CIRCUIT DESIGN

The CMOS design for D-latch using pass transmission gate is shown as

- SCHEMATIC

![image](https://github.com/Hiteshprp/d_latch/blob/main/Images/Schematic.png)

- SYMBOL

![image](https://github.com/Hiteshprp/d_latch/blob/main/Images/symbol.png)                                                                                                                                                                                                                                                                                                                                                                               

- TESTBENCH SYMBOL

![image](https://github.com/Hiteshprp/d_latch/blob/main/Images/Schematic_symbol_tb.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                
- PRIMEWAVE WINDOW

![image](https://github.com/rahul-hebbar/XNOR_gate_using_synopsys/blob/main/images/testsuit_pathway.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                        
- TESTBENCH WAVEFORM

![image](https://github.com/Hiteshprp/d_latch/blob/main/Images/waveform.png)                                            

# NETLIST
The netlist of the above circuit has also been uploaded to the github repo with the file name - netlist.txt  

# AUTHOR
Hitesh, MTech VLSI and Embedded Systems , Defence Institute of Advanced Technology, Pune, Maharashtra

# ACKNOWLEDGEMENT 

- Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
- Synopsys, India
- VLSI System Design(VSD) Corporation Private Limited India
- Indian Institute of Technology, Hyderabad 
- Cloud Based Analog IC Design Hackathon
- Sameer Durgoji, NIT Karnataka
- Chinmay panda, IIT Hyderabad

# REFERENCES

- [2]	D-Latch AND D-FLIP FLOP (Introduction) : VLSI : Biotechnology and Biomedical Engineering : Amrita Vishwa Vidyapeetham Virtual Lab , https://vlab.amrita.edu/?sub=3&brch=66&sim=519&cnt=833
- [1]	STA-II TRANSMISSION GATE,D LATCH, DFF,SETUP &HOLD - VLSI- Physical Design For Freshers (physicaldesign4u.com), https://www.physicaldesign4u.com/2020/04/sta-ii-transmission-gated-latch-dffsetup.html
