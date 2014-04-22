#####1st Program Operation
This program loads a value of 8 into the accumulator, adds one to the number in the accumulator, then outputs that number to output port 3. It then checks to see if the number in the accumulator is negative. If the number is negative, it loops back up to the “add 1” part of the code and adds one to the value in the accumulator again. If it's not negative, it will proceed to the end of the program and loop forever.

#####1st Program Instruction Cycles
I stepped through the simulation of the testbench file and took screenshots of each instruction being executed. See below for the screenshots.
######LDAI
[LDAI](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform1_ldai.JPG "Instruction 1")
######ADDI
[ADDI](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform2_addi.JPG "Instruction 2")
######OUT
[OUT](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform3_out.JPG "Instruction 3")
######JN
[JN](https://github.com/JasonPluger/Lab5_Pluger/blob/master/part1_waveform4_jn.JPG "Instruction 4")
