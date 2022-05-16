# TASBot
Building the hardware to talk to a NES

Using this shift register
https://www.ti.com/lit/ds/symlink/cd4021b.pdf

       --U--
 P8 --|     |-- VDD
 Q6 --|     |-- P7
 Q8 --|     |-- P6
 P4 --|     |-- P5
 P3 --|     |-- Q7
 P2 --|     |-- Serial In
 P1 --|     |-- Clock
VSS --|     |-- Parallel/Serial Control
       -----


Serial control to high to turn parallel input into serial output

VDD 5V


NES pinout
       __
  GND |0 \
  CLK |0 0| VCC
LATCH |0 0| D3
   D1 |0 0| D4
       ---

D1 is the gamepad


My NES pinout order is

gnd clk latch d1  vcc

Extension cable

white gnd
yellow clk
green latch
black d1
red vcc


old cable

white blue yellow brown red

