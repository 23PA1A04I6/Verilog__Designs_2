The Bit Vault is a digital design module that securely stores and manages binary data.
It can act as:

1.A protected register or memory cell
2.A lockable / configurable data vault
3.A secure storage element in larger systems (e.g., cryptographic key storage)

This project includes:

1.RTL design files (Verilog / SystemVerilog)
2.Testbench files to verify functionality
3.Instructions to simulate and view waveforms

 How It Works:
1.load=1: data from input bus is stored into vault

2.lock=1: vault is locked; write attempts are ignored

3.reset=1: clears vault contents

4.enable=0: vault keeps current value
