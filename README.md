**Name:** Ethan Lee  
**Education:** University of Illinois Urbana-Champaign  
**Major:** Computer Engineering  
**Graduation Date:** May 2028

August 6, 2026

# async-fifo-uvm
Parameterized dual-clock Asynchronous FIFO with Gray-code CDC synchronizers and 2-stage flip-flop paths, verified using a full UVM testbench environment with 100% functional and code coverage. Seeing that most major semiconductor companies utilize UVM/SVA verification, I wanted to create a project that revolves around creating a UVM/SVA environment for a commonly used data structure in computer architecture. This is also a good way to become more familiar with how to cross different clock domains safely and minimize metastability. I chose the asynchronous FIFO for its relevance in SoC module communication, network communication, and clock domain bridging on FPGAs.

## Features
- **Dual-Clock Design:** Parameterized $16 \times 8$ SystemVerilog FIFO using Gray-code pointers and 2-stage synchronizers for safe Clock Domain Crossing (CDC)
