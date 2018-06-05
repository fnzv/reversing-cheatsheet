# Reverse engineering cheatsheet


1) ltrace ./binary 
Executes the binary and show basic syscalls


2) strace -f ./binary
Executes the binary and shows some more advanced info about it


3) ldd ./binary
Shows libraries 


4) file binary
Info of the binary 


5) objdump -d binary
Disassembly of the binary, there are some interesting args such as: -s --section .comment,  -T .. many more


6) gdb / pwngdb
GDB disassembler


7) readelf -x .rodata binary
Static strings


8) strings binary
Display strings 


9) readelf -s binary
Display simbols
