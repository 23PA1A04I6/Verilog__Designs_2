The Dual Clock FIFO is a specialized First-In-First-Out memory buffer designed to safely transfer data between two asynchronous clock domains.
It is essential for:

1.Bridging data between slow and fast subsystems

2.Interfacing peripherals running on different clocks

3.SoC buses, UART, PCIe, and multi-clock FPGA systems

This repository includes:

1.RTL design files (Verilog/SystemVerilog)

2.Testbench to verify cross-clock behavior

3.Instructions to run simulations and view waveforms

 How It Works:
1.Data is written to the FIFO at wr_clk domain when wr_en=1 and full=0

2.Data is read from the FIFO at rd_clk domain when rd_en=1 and empty=0

3.Gray-coded read and write pointers cross clock domains to update status flags

4.full indicates no more space to write; empty indicates nothing to read
