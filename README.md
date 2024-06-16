# OSHCamp-Bit-Serial-CPU

Here I describe a bit serial CPU intended for a presentation and workshop session at OSHCamp 2024 on 24th and 25th August.

Each year, open source hardware enthusiasts gather in the picturesque town of Hebden Bridge, West Yorkshire for a long weekend of talks, discussions and practical hardware workshops.

I am proposing a bit-serial CPU kit, and a general presentation of bit serial computing.

MITE is a complete 8-bit computer implemented in fewer than 30 ICs.

The ALU uses bit serial arithmetic and is just 5 ICs. Compared to Marcel van Kervincks Gigatron 8-bit ALU which was 10 ICs. Extending to 16-bits does not add anymore ICs to the ALU.

MITE can easily be extended to 16-bits, with very few archtectural additions.


MITE has a bank of 8 registers, implemented in RAM - very much influenced by the Z80.
