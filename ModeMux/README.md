The Mode Mux (Mode Multiplexer) is a digital circuit that selects between multiple data sources or operational modes based on a control input.
It is often used to:

1.Switch between test mode and normal operation

2.Select functional modes in ALUs, data paths, or communication blocks

3.Dynamically choose data from different sources

This repository includes:

1.RTL design files (Verilog/SystemVerilog)

2.Testbench to verify mode switching behavior

3.Instructions to run simulations and view waveforms

How It Works:
1.mode_select input chooses which data input to route to the output.

2.On change of mode_select, the output immediately reflects the selected input.

3.Can be purely combinational, or synchronous if registered.
