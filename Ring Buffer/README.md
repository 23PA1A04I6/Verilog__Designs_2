The Ring Buffer (also known as a circular buffer) is a fixed-size buffer that works as if the memory is connected end-to-end in a ring.
It efficiently stores and streams data between a producer and a consumer without needing complex memory management.

Common applications:

1.UART or SPI FIFO buffers

2.Audio/video streaming

3.Network packet buffers

4.Low-latency data pipelines in digital systems

This repository contains:

1.RTL design files (Verilog/SystemVerilog)

2.Testbench to verify functionality

3.Instructions to run simulations and view waveforms

How It Works:
1.Data is written at the write_ptr and read from the read_ptr.

2.When write_ptr reaches the buffer’s end, it wraps around to zero.

3.Similarly for read_ptr.

4.full flag indicates buffer can't accept new data.

5.empty flag indicates no data to read.
