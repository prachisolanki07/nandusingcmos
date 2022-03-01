# CMOS Used As NAND Application
# Table of Content
- [ABSTRACT](https://github.com/prachisolanki07/nandusingcmos#abstract)
- [Introduction](https://github.com/prachisolanki07/nandusingcmos#introduction)
- [2- Input NAND Gate Using CMOS](https://github.com/prachisolanki07/nandusingcmos#2--input-nand-gate-using-cmos)
- [Tools Used](https://github.com/prachisolanki07/nandusingcmos#tools-used)
- [Author](https://github.com/prachisolanki07/nandusingcmos#author)
- [Design Approach](https://github.com/prachisolanki07/nandusingcmos#design-approach)
- [Acknowledgement](https://github.com/prachisolanki07/nandusingcmos#acknowledgement)
- [References]( https://github.com/prachisolanki07/nandusingcmos#references)


# Abstract
This paper gives an idea about CMOS used as a NAND Gate. CMOS gate designs enjoy over TTL is a much wider allowable range of power supply voltages. Whereas TTL gates are restricted to power supply (Vcc) voltages between 4.75 and 5.25 volts, CMOS gates are typically able to operate on any voltage between 3 and 15 volts.

# Introduction
Low power and area efficient technologies are the prime concern for VLSI system designers. Together with that, the high speed NAND gate that is made using CMOS have low power consumption indisputably become a very useful IC as it has many advantages over TTL.
In VLSI implementation, major problems are heat dissipation and power consumption. To solve this problem it is required to reduce power supply voltage, switching frequency and capacitance of transistor.
To summarize, this paper focused on some of the performance criteria considered in the designing and evaluation of this CMOS circuit while some are utilized for the ease of design, robustness, silicon area, delay and last but not the least power consumption.

# 2- Input NAND Gate Using CMOS
For the design of NAND Gate circuit with the CMOS technology; We need parallel connection of pMOS and series connection of nMOS with nMOS source tied directly or indirectly to ground and pMOS source tied directly or indirectly to Vdd. A basic CMOS structure of any 2-input NAND gate can be drawn as follows:
![cmos nand gate](https://user-images.githubusercontent.com/100673505/156164256-d2f56e09-694e-4036-beaf-58988b395893.png)

- CMOS Circuit Behaviors for All Logic Inputs
![TT](https://user-images.githubusercontent.com/100673505/156165810-bfdc3f00-3ee6-4a75-bacb-66732823b017.png)
- Truth Table
![truthtable](https://user-images.githubusercontent.com/100673505/156167363-37c2e10b-7a81-4470-a866-d6d8abd31925.png)

# Tools Used
- Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.
- Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.
- Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

# Design Approach
- SCHEMATIC:
 ![SCHEMATIC](https://user-images.githubusercontent.com/100673505/156152384-c328ed47-c517-4215-9986-8d78838295b3.png)
 
- 2 INPUT NAND GATE:
 ![2 input NAND Gate](https://user-images.githubusercontent.com/100673505/156152490-533cdad0-081d-43ba-a181-e230baf555c1.png)
 
- TRANSIENT ANALYSIS:
 ![Transient Analysis](https://user-images.githubusercontent.com/100673505/156152680-8523808b-4094-4b54-a9b7-e76d14c15a34.png)
 
- WAVE VIEW:
 ![WaveView](https://user-images.githubusercontent.com/100673505/156152734-f499fd4b-c800-4832-9363-c28cfc8cad8b.png)

# Author
Prachi Solanki, B.Tech Electronics and Communication Engineering, J.C. Bose University of Science and Technology,YMCA

# Acknowledgement
- [Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)
- [Cloud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Synopsys India](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Sameer Durgoji, NIT Karnataka](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Chinmay panda, IIT Hyderabad](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')

# References
-	Saradindu Panda, A.banerjee, B.maji and Dr. A.K. Mukhopadhyay,“Power and delay comparison in between different types of full addercircuits”, International Journal of advanced research in electrical,electronics and instrumentation engineering, volume 1, issue3.pp.168-172, 2012.
- https://www.allaboutcircuits.com
-	Swati Sharma and Rajesh Mehra, “Area and power efficient design ofXNOR-XOR logic using 65nm technology”, International Journal ofengineering and technical, pp.57-60, 2014
-	http://www.vlsifacts.com/
- Neil H.E.Weste, David Harris and Ayan Banaerjee, “CMOS VLSIdesign”. Pearson Education,Inc., pp. 11, Third Edition, 2005


