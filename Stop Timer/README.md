The Stop Timer is a digital circuit designed to measure elapsed time between start and stop events, similar to a digital stopwatch.
It’s useful in:

1.FPGA / ASIC labs to measure latency or delay

2.Timing events or pulses in digital systems

3.Creating stopwatch-like applications with start, stop, and reset

This repository contains:

1.RTL design files (Verilog/SystemVerilog)

2.Testbench to verify correct timing and control behavior

3.Instructions to simulate and view waveforms

 How It Works:
start=1: counter begins incrementing each clock cycle

stop=1: counter freezes; value represents elapsed time

reset=1: counter resets to zero

When stop=0 and start=0: counter remains paused
