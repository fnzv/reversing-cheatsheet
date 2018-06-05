# Reverse engineering cheatsheet


1) ltrace ./binary  <br>
Executes the binary and show libs trace<br><br>


2) strace -f ./binary<br>
Executes the binary and shows syscall trace<br><br>


3) ldd ./binary<br>
Shows libraries <br><br>


4) file binary<br>
Info of the binary <br><br>


5) objdump -d binary<br>
Disassembly of the binary, there are some interesting args such as: -s --section .comment,  -T .. many more<br><br>


6) gdb / pwngdb<br>
GDB disassembler<br><br>


7) readelf -x .rodata binary<br>
Static strings<br><br>


8) strings binary<br>
Display strings <br><br>


9) readelf -s binary<br>
Display simbols<br><br>
