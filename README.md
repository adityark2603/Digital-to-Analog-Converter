# Digital-to-Analog-Converter
A 4-bit R-2R Ladder Digital-to-Analog Converter (DAC) is a simple yet efficient way to convert digital signals into analog voltages using only two resistor values: R and 2R, and optionally an op-amp for buffering and summing.

## Basic working
1. The 4-bit DAC takes 4 digital inputs: 
𝐷3
,
𝐷2
,
𝐷1
,
𝐷0
(MSB to LSB).
2. These inputs are binary (either 0 or 1).
3. The R-2R resistor ladder converts this binary code into a corresponding analog voltage.
4. An op-amp is used as a summing amplifier to produce a stable output and isolate the ladder from the load.

   ![image](https://github.com/user-attachments/assets/82be9d12-bd2b-45cd-a568-6ae4018822f8)

## Schematic Specifications 
