# 256-bit-SRAM
256-BIT SRAM Memory System was designed using 6T cell using 45nm technology on Cadence Virtuoso schematic editor.

It was designed such that parameters like area can be minimized while working at the maximum possible frequency. 
The individual components are the building blocks of the SRAM, so careful consideration of Flip flop, MUX, decoder 
was given in order to maximize robustness, reduce glitches and area. 
Read and trip voltages were measured for different pull up, access and pull down transistor sizes. 

There are multiple types of SRAMs being used now a days like Asynchronous, synchronous, special and non- volatile SRAMs. 
We have designed a synchronous SRAM. In this the read and write cycles are synchronized with the clock signal so it can
be used for fast applications.The address, control and data signals are controlled by the clock signal. 
Synchronous SRAM is widely used for Cache and other applications requiring burst transfers.

Read margin of 23% and Write margin of 41.9% was achieved while glitches were kept as low as 8mV.
Maximum frequency achieved is 1.5GHz & it works on supply of as low as 780mV.
The area of 6-T SRAM cell was less than 1um2 which led to the area efficient deisgn.