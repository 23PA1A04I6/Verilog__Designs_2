The Pulse Stretcher is a simple but important digital circuit used to:

1.Expand (stretch) a narrow or glitchy input pulse

2.Generate a wider pulse of predictable width

3.Help synchronize short asynchronous events into a clocked domain

It’s commonly used in:

1.Button debouncing

2.Edge detection circuits

3.Bridging asynchronous events into synchronous logic

4.Triggering counters or FSMs with guaranteed pulse width

This repository contains:

1.RTL design files (Verilog/SystemVerilog)

2.Testbench to verify correct stretching

3.Instructions to run simulations and see waveforms

How It Works:
1.Detects a narrow input pulse (e.g., 1 clock cycle)

2.Once detected, starts an internal counter

3.Keeps output high for N clock cycles (stretch width)

4.After the counter finishes, output returns low, ready for next pulse
