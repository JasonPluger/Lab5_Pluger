####1st Program Operation
This program loads a value of 8 into the accumulator, adds one to the number in the accumulator, then outputs that number to output port 3. It then checks to see if the number in the accumulator is negative, i.e. if the MSB is a '1'. If the number is negative, it loops back up to the “add 1” part of the code and adds one to the value in the accumulator again. If it's not negative, it will proceed to the end of the program and loop forever.

####1st Program Instruction Cycles
I stepped through the simulation of the testbench file and took screenshots of each instruction being executed. See below for the screenshots. In each instance, I looked at the status of IRLd to determine when Fetch was being executed, the value of MEMSEL_L for Decode (which occured for one clock cycle after Fetch had completed), and what I looked at during Execute depended on what OpCode was being executed. An example of this is shown in the Jump Negative waveform (JN below). 
######LDAI
![LDAI](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform1_ldai.JPG?raw=true "Instruction 1")
######ADDI
![ADDI](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform2_addi.JPG?raw=true "Instruction 2")
######OUT
![OUT](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform3_out.JPG?raw=true "Instruction 3")
######JN
In this instruction, I circled the parts on the simulation that I looked at to determine which part - fetch, decode, execute - of the Instruction Cycle I was looking at.
![JN](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform4_jn.JPG?raw=true "Instruction 4")


####Answers to Questions:
Below is a picture of the questions sheet from Lab 5; I have filled it in with my answers.
![Questions](https://github.com/JasonPluger/Lab5_Pluger/blob/master/Questions.JPG?raw=true "Q/A")

####Part 2
My method of attack for completing part 2 of lab 5 consisted of writting out the instructions that I thought would make the program operate correctly on a piece of paper prior to actually coding it in the PRISM computer. Samples of my pseudo-code work are shown below. 
![Picture 1](urlHere ?raw=true "Picture 1")
![Picture 2](urlHere ?raw=true "Picture 2")

#####Commit History
Throughout the design process of Part 2, as I achieved each new piece of the program, I would save my progress up to that point. However, instead of saving new files each time, I would simply overwrite the same file, and therefore have only the final copy of my PRISM and ROM files committed to git.





  I meant to email a video of my Part 1 functionality to Dr. Neebel on the evening of 18 Apr, however I failed to do so. He did see my functionality video the following class period, Tues 22 Apr 14. 
  Dr. Neebel checked my PRISM Part 2 implementation on 24Apr14. 
  Dr. Neebel checked my FPGA implementation of my PRSIM Part 2 file on 24Apr14.





Documentation: 22Apr14: C3C Jonas helped me determine how to get the photos to show up in the README file instead of as links.
