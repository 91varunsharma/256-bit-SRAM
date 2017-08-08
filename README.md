# 256-bit-SRAM
256-BIT SRAM Memory System was designed using 6T cell using 45nm technology on Cadence Virtuoso schematic editor.

It was designed such that parameters like area can be minimized while working at the maximum possible frequency. 
The individual components are the building blocks of the SRAM, so careful consideration of Flip flop, MUX, decoder 
was given in order to maximize robustness, reduce glitches and area of the cell. 
Read and trip voltages were measured for different pull up, access and pull down transistor sizes and optimum ratio was choosen. 

There are multiple types of SRAMs being used now a days like Asynchronous, synchronous, special and non- volatile SRAMs. 
We have designed a synchronous SRAM. In this the read and write cycles are synchronized with the clock signal so it can
be used for fast applications.The address, control and data signals are controlled by the clock signal. 
Synchronous SRAM is widely used for Cache and other applications requiring burst transfers.

Following Results were achieved:

**Read margin = 23%**

**Write margin = 41.9%**

**Glitches were as low as 8mV**

**Maximum frequency = 1.5GHz** 

**Power suppply as low as 780mV**

**Area of 6-T SRAM cell =0.96um2**
