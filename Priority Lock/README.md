The Priority Lock is a digital circuit that manages access to a shared resource among multiple requesters.
It ensures:

1.Only one request is granted at a time

2.Requests with higher priority are served first

3.Lower-priority requesters must wait until the lock is released

Applications include:

1.Bus arbitration in SoCs

2.Shared memory or peripheral access

3.Resource control in NoC (Network-on-Chip) or multi-master systems

This repository contains:

1.RTL design files (Verilog/SystemVerilog)

2.Testbench files to verify arbitration and locking behavior

3.Instructions to run simulations and view waveforms

