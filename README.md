Task 1 – RISC-V Environment Setup

In this task, I set up the RISC-V development environment using GitHub Codespaces and verified the setup by compiling and running a reference RISC-V program.

What I did

First, I opened the vsd-riscv2 repository on GitHub and created a Codespace from it.
Once the Codespace started, I explored the repository and found the RISC-V reference program inside the Samples folder.

I then compiled the sample C program using the RISC-V GNU compiler. After successful compilation, I ran the generated executable using the Spike RISC-V simulator.

The program executed without errors, which confirmed that the environment was set up correctly.

Repository Used

https://github.com/vsdip/vsd-riscv2

TASK-1 Answers to Understanding Questions

Q1: Where is the RISC-V program located in the vsd-riscv2 repository?
A: In the Samples directory.

Q2: How is the program compiled and loaded into memory?
A: Compiled using the RISC-V GNU Toolchain (riscv64-unknown-elf-gcc) and loaded into memory via Spike using the Proxy Kernel (pk).

Q3: How does the RISC-V core access memory and memory-mapped IO?
A: The core accesses memory and memory-mapped IO using standard load (lw) and store (sw) instructions.

Q4: Where would a new FPGA IP block logically integrate in this system?
A: It would integrate onto the system bus.
