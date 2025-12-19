# VSD_FPGA_IP_DEVELOPMENTVSD Task 1 Submission
RISC-V Reference Program

Screenshot:![WhatsApp Image 2025-12-19 at 19 57 30](https://github.com/user-attachments/assets/a48bb472-05e0-4e8e-954c-29fbcea0798b)



VSDFPGA Lab

Screenshot:![WhatsApp Image 2025-12-19 at 19 57 30 (1)](https://github.com/user-attachments/assets/3b70a75e-6aa9-46b0-8076-702410301ee7)



Answers to Understanding Questions

Q1: Where is the RISC-V program located in the vsd-riscv2 repository?

A: In the Samples directory.

Q2: How is the program compiled and loaded into memory?

A: Compiled using the RISC-V GNU Toolchain (riscv64-unknown-elf-gcc) and loaded into memory via Spike using the Proxy Kernel (pk).

Q3: How does the RISC-V core access memory and memory-mapped IO?

A: The core accesses memory and memory-mapped IO using standard load (lw) and store (sw) instructions.

Q4: Where would a new FPGA IP block logically integrate in this system?

A: It would integrate onto the system bus.


Confirmation of Environment Used

GitHub Codespace only

Optional Confidence Task

Objective: Modify the C code and observe the change

Changes Made: Modified the print message and calculation limit in sum1ton.c<img width="1919" height="1011" alt="image" src="https://github.com/user-attachments/assets/eef6c246-3b35-4c3d-92b1-f2cc25721e78" />
