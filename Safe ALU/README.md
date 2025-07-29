The Safe ALU is an enhanced Arithmetic Logic Unit designed for digital systems that require safe, reliable, and predictable operation.
It performs standard ALU operations (add, subtract, AND, OR, XOR, etc.) while adding:

1.Built‑in overflow and underflow detection

2.Invalid operation detection

3.Optional lock / enable signal to freeze outputs or disable computation

4.Synchronous reset

This makes it especially useful in:

1.Safety‑critical digital systems (e.g., automotive, avionics, medical devices)

2.FPGA / ASIC designs where safe fallback is needed

3.Secure computing cores

This repository includes:

1.RTL design files (Verilog / SystemVerilog)

2.Testbench files to verify correct and safe operation

3.Instructions to run simulations and view waveforms

