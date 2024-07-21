# VSD_Squadron_mini_research_internship_Rohan
My project assignments for Squadron mini research internship Rohan by VLSI System Design

### Task1
Successfully launched virtual machine as instructed: https://forgefunder.com/~kunal/riscv_workshop.vdi

![Compiled c++ code](https://github.com/Rohan7Gupta/VSD_Squadron_mini_research_internship_Rohan/blob/main/images/Capture2.PNG)

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c

riscv64-unknown-elf-objdump -d sum1ton.o | less

riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c

![rv64i object file](https://github.com/Rohan7Gupta/VSD_Squadron_mini_research_internship_Rohan/blob/main/images/Capture.PNG)

