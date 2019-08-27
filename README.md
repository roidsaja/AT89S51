# AT89S51
Managing ISR (interrupt service routine) using Machine Code. The AT89S51 is part of Intel MCS-51 and till now has been the fundamentals for learning Operating Systems. In particular, the 8051 series - family tree of AT89S51, this chip uses Harvard architecture rather than the standard x86. It can only execute code fetched from program memory and has no instruction to write into program memory.

### Reasons to study the 8051 ###
* One of the few microprocessors that are left with an ACC instruction set, known commonly among CISC based computers.
* Includes four banks of workable register sets (R0-R7), reduces the amount of time required to complete an ISR.
* Bit Level Boolean Operations. Allows user to carry out directly and efficiently on selected internal registers,ports and RAM locations. The 16 bytes (128 bits) of internal RAM locations 0x20-0x2F are addressable.
* You are communicating like how a machine communicates to us users goddamnit!
