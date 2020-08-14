# Yann Herklotz

Hi! I’m currently a first year PhD student in the Circuits and Systems group at Imperial College London, supervised by [John Wickerson](https://johnwickerson.github.io/).

My research focuses on formalising the process of converting high-level programming language descriptions to correct hardware that is functionally equivalent to the input.  This process is called high-level synthesis (HLS), and allows software to be turned into custom accelerators automatically, which can then be placed on field-programmable gate arrays (FPGAs).  Work in progress on this project can be seen in the [Vericert](https://github.com/ymherklotz/vericert) repository

I have also worked on random testing for FPGA synthesis tools. [Verismith](https://github.com/ymherklotz/verismith) is a fuzzer that will randomly generate a Verilog design, pass it to the synthesis tool, and use an equivalence check to compare the output to the input.  If these differ, the design is automatically reduced until the bug is located.
