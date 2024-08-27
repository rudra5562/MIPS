This project focuses on the design and implementation of a 32-bit, 5-stage pipelined, high-performance MIPS-based RISC core built on Harvard Architecture. The MIPS processor is structured using the MIPS Instruction Set Architecture (ISA) and is divided into three primary modules: the datapath unit, control unit, and hazard unit. 

The processor is tested to execute two specific programs: the calculation of the Greatest Common Divisor (GCD) of two numbers and the calculation of the factorial of a number. These programs are initially written in MIPS assembly language and then converted into machine code to be processed by the core.

The processor is designed using Verilog HDL, and its functionality is validated using the Vivado 2022.2 simulation tool. The project also involves a performance analysis, comparing the pipelined MIPS processor with a traditional single-cycle MIPS processor, highlighting the advantages in terms of speed and efficiency offered by pipelining.

This project serves as a comprehensive study of pipelined processing, hazard management, and the practical application of MIPS architecture in developing high-performance computing systems.
