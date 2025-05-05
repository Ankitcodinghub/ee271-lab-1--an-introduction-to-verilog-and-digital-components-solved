# ee271-lab-1--an-introduction-to-verilog-and-digital-components-solved
**TO GET THIS SOLUTION VISIT:** [EE271 Lab 1- An Introduction to Verilog and Digital Components Solved](https://www.ankitcodinghub.com/product/ee271-lab-1-an-introduction-to-verilog-and-digital-components-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99220&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE271  Lab 1- An Introduction to Verilog and Digital Components Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
EE 271, Lab 1

An Introduction to Verilog and Digital Components

</div>
</div>
<div class="layoutArea">
<div class="column">
Lab Objectives

</div>
</div>
<div class="layoutArea">
<div class="column">
Read the whole lab first before starting on any work. The first lab for EE 271 will introduce you to the DE1-SoC Development board and Quartus Prime edition version 17. Both components are very important for all future labs so please pay attention and do not rush through this first lab.

If you have any questions at any point please ask; you don’t want to damage any of the expensive hardware that is provided to you.

Laboratory Design Kits

The design kits contain the resources you need to complete the labs. You are responsible for your lab kit and we expect that you will return the kit in good working order with all pieces intact. The kit includes:

<ul>
<li>The Terasic DE1-SoC Development Board (the “DE1”) with UW Proto board attached on the top. The green Proto board has a white solder-less breadboard on it.</li>
<li>A black power cord for powering the DE1.</li>
<li>A grey USB cable for hooking the DE1 to a host computer.</li>
<li>LED matrix board that may be used for the final project.</li>
<li>TTL chips (in case needed for the final project)
Altera/Terasic DE1-SoC Development Board
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The picture above is a diagram of the DE1 with most of the major components highlighted. Take note of the large FPGA (Field Programmable Gate Array) that is in the middle of the board. Think of it like a universal logic unit that all the devices can talk to.

The following picture shows how to connect the board to your computer.

You will need to use the black power cord to power the board. Plug the cord into an outlet and into the “Power DC Jack” socket just above the red on/off button. The grey USB cable is used to connect the “USB Blaster II” to the computer.

Using Quartus Software

The designs in this class will be done through the Quartus software. You can install the software for free by going to https://fpgasoftware.intel.com/?edition=lite , download the free web edition and install it. Note that you will have to register to be able to download the software.

First, make sure you Select Edition “Lite” and Select Release “17.0”, then download the 5.8 GB tar file under the “Combined files” tab. Extract the tar file using a program like 7-zip and run the QuartusLiteSetup-17.0-windows.exe file. When it asks for the components to install, make sure you select each of these:

<ul>
<li>Quartus Prime Lite Edition (Free)</li>
<li>Devices: Cyclone V</li>
<li>ModelSim: Intel FPGA Starter Edition (Free)
When the software is done, make sure to install the USB blaster driver. Run Quartus next, and if asked about licensing just run the software (we use the free version, so no license required).

Assigned Tasks

Task 1: Creating a schematic diagram and simulating a fulladder in Quartus

The objective of this task is to see how circuits are constructed at the hardware level using logic gates. However, instead of physically building a circuit on a breadboard and test its functionality, we will do this in Quartus. In this task you will follow two video tutorials on creating a schematic diagram for a full adder circuit and simulate it with timing diagrams. Please note that these tutorials
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
were created using an older version of Quartus and so to adjust to version 17.0, you will need to follow the document called “schematic-tutorial” on canvas which includes the links to the video tutorials. Also note that this will be the only time we will use these tutorials and they are meant to replace what you would have done if you wired the full adder circuit and tested it in the lab. In this course we will be writing Verilog code to implement designs and will use ModelSim for simulation.

Task 2: Implementing and simulating the full adder using SystemVerilog and ModelSim

You should come to realize from task 1 that it is a tedious task to build circuits physically on breadboards especially as designs become more complicated. In this task we will do the same task we did in task1 but using Verilog and ModelSim.

For this task, you should follow along a series of video tutorials that will walk you through the steps of creating your first design using SystemVerilog and simulating the design in ModelSim. For your reference, the source code used in the tutorials is in the appendix of this document.

Please follow the tutorials in the following order:

<ol>
<li>Launch the Quartus Prime software.</li>
<li>Create a project from scratch. Please follow the steps in the following videos and use the
same project name as in the video https://youtu.be/iLbmSTG7bpA
</li>
<li>Implement the full adder using SystemVerilog and simulate it using ModelSim. Please
follow the following video: https://youtu.be/BcvclrqZ2fc

Please note that in the video when it refers to compiling the project for the first time, it may give you a compilation error. If you run the video for few more seconds it ’ll tell you

about setting the top level modules so that the program compiles.

• After you successfully simulate the full adder, save a screenshot of the simulation. You can do that by going to File-&gt;Export-&gt;image and then save the image. You will need to include this image in your lab report as a proof that you went over the tutorials.
</li>
<li>Mapping a SystemVerilog design to an FPGA. Please follow the steps in the following video and save an image of the simulation. https://youtu.be/mnZt2iNNfp4</li>
<li>Loading the design onto the FPGA. Please follow the steps in the following video and test your full adder on the DE1_SoC board and verify that it matches the truth table.
https://youtu.be/uMxA3VcS3f8
</li>
</ol>
After you are done with this task, close the current project before moving to the next task. You may quit Quartus at this point.

Task 3: Design a 4-bits adder

In the previous tasks, we created an adder that can add 3 bits. However, in reality, the numbers consist of multiple bits and therefore we want to extend our design accordingly. Your task is to use the “fullAdder” SystemVerilog module to extend the design to 4 bits numbers as shown in the following figure

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Figure 1. 4-bits Adder

To get started, you need to do the following:

1. Instead of creating a project from scratch, make a copy of the lab1 folder that was created in task 2 and call it “lab1a”. Launch quartus by double clicking on DE1_Soc.qpf file under the lab1a folder. If you followed all the steps of task 2, you should have two .sv files: DE1_SoC.sv and fullAdder.sv

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Create a new SystemVerilog file and call it fullAdder4. This module will instantiate the fullAdder module created in task 2. To help you get started, here’s a skeleton of fullAdder4 please modify it accordingly. Make the fullAdder4 module your top level entity and simulate it in ModelSim and save a picture of the simulation for your lab report.</li>
<li>Modify the DE1_SoC.sv such that you use 9 switches and 5 LEDs. SW0 is for Cin, SW4-SW1 for the 4-bits A and SW8-SW5 for B. The 5 LEDs should show Sum3-Sum0 and Cout. For better readability, show the output in the same order shown in Figure 1 from left to right (i.e Cout should be the left most LED and Sum0 is the right most LED).</li>
<li>Additionally, modify the assign statements for the HEX displays in the DE1_SoC.sv such that it displays the word “Adding”. As an example, to make HEX5 shows the letter ‘A’, all the segments need to be turned on except segment 3 (HEX5[3]). Figure 2 is from the DE1_SoC datasheet and shows the 7-segments display connections. The segments are active low which means that a value
of 0 is needed to turn on any segment.

Figure 2. HEX0 connections on the DE1_SoC board
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Accordingly, to display the letter ‘A’ on HEX5, the following statement can be used

assign HEX5 = 7’b0001000; //displays ‘A’ where all segments except 3 are turned on.

<ol start="5">
<li>Make DE1_SoC.sv your top level entity and simulate it in ModelSim and save a picture of the simulation for your lab report.</li>
<li>Load the program to the FPGA and test it.</li>
</ol>
Lab Demonstration and Submission Requirements

<ul>
<li>Submit a video demonstrating the 4-bits adder. Your video is expected to be around 1 minute. In the video demonstrate the functionality on the board using the switches and LEDs and the 7- segment display.</li>
<li>Submit a short lab report (about 3 pages and it’s ok if you go above 3 pages) that should include 3 main sections, detailed below.

Procedure

<ul>
<li>– &nbsp;Describe how you approached the problem and include any visuals (like block diagrams, truth tables, schematics, ..etc)
Results
</li>
<li>– &nbsp;Include a screenshot of the waveforms you created for task1</li>
<li>– &nbsp;Include screenshots of ModelSim results for task 3</li>
<li>– &nbsp;Describe what you tested in the simulation, and what the results in the screenshot show</li>
<li>– &nbsp;Give a brief overview of the finished project, compared to what was asked
Appendix
</li>
</ul>
</li>
</ul>
– Include screen shots for your code

– On Padlet, write about a problem you had in the lab and the fix to it, share a tip or trick you learned while working on the lab. You can also share an aha moment that you discovered while working on the lab. Avoid duplicating comments made by your classmates. NO videos for this padlet task, please use textual

comments. The link to the padlet is here

<ul>
<li>Submit the SystemVerilog files (files with extension .sv) of task 3. Make sure to follow the commenting guide provided. A significant amount of grade will depend on the commenting style.</li>
<li>Submit your report, video and programs to Canvas. .</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
1. FullAdder module

</div>
</div>
<div class="layoutArea">
<div class="column">
Appendix

Source code used in the videos

</div>
</div>
<div class="layoutArea">
<div class="column">
2. DE1_Soc module

</div>
</div>
</div>
