The Byte Streamer is a digital circuit that takes parallel data words (usually 8 bits = 1 byte) and streams them out sequentially, either bit‑by‑bit or byte‑by‑byte.
It’s useful in:

1.UART transmitters

2.SPI/I2C data engines

3.Packet generators

4.Streaming data into communication cores

This repository contains:

1.RTL design files (Verilog / SystemVerilog)

2.Testbench files to verify functionality

3.Instructions to simulate and view waveforms

 How It Works:
1.On load/start, module loads the input byte.

2.Starts streaming bits or bytes each clock cycle.

3.Asserts done or ready when streaming is complete.

4.Can be restarted with new data on the next load.
