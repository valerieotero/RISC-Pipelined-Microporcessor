# RISC-Pipelined-Microprocessor
Computer Architecture and Organization class project (ICOM4215) - Fall 2020

To run/test the instruction RAM, on a terminal write the following:

$ iverilog -o inst_mem_tb.vvp inst_mem_tb.v

$ vvp inst_mem_tb.vvp

After the second command, whatever input is on the "inst_input_file", the "inst_memcontent" file will show the output