# OSHCamp-Bit-Serial-CPU

![image](https://github.com/monsonite/OSHCamp-Bit-Serial-CPU/assets/758847/e3bee932-bd6e-4558-b837-efdc5aa252cb)


Here I describe a bit serial CPU intended for a presentation and workshop session at OSHCamp 2024 on 24th and 25th August.

Each year, open source hardware enthusiasts gather in the picturesque town of Hebden Bridge, West Yorkshire for a long weekend of talks, discussions and practical hardware workshops.

I am proposing a bit-serial CPU kit, and a general presentation of bit serial computing.

MITE is a complete 8-bit computer implemented in fewer than 30 ICs. 

The aim is to create a small CPU that can interface to memory, GPIO, peripherals and sensors using the SPI interface.

MITE can be broken down into several sub-systems for clarification of its operation.

1. A clock generator and timing sequencer  - 3 ICs.
 
2. A Program Counter and SRAM memory Interface - 10 ICs

3. Instruction decoding logic - 2 ICs

4. An Accumulator shift register AC - 1 IC

5. A memory Bus shift register B - 1 IC
 
6. The bit serial ALU - 5 ICs.
 
7. Input and Output registers - 2 ICs.
 
In all, it is around 25 ICs.


The ALU uses bit serial arithmetic and is just 5 ICs. Compared to Marcel van Kervincks Gigatron 8-bit ALU which was 10 ICs. Extending to 16-bits does not add anymore ICs to the ALU.

MITE can easily be extended to 16-bits, with very few archtectural additions.


MITE has a bank of 8 registers, implemented in RAM - very much influenced by the Z80.
