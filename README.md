# Matrix-Completion
The matlab code is in the Matlab_code directory.
The verilog code is in the Verilog_code directory.

1) Run inputHDL.m on matlab to obtain the test vectors in floating point
2) Copy the input vectors output by matlab into there corresponding txt files for the formatter(written in C) to read.
3) Run the formatter, test_algo.cpp to obtain test vectors in Hexadecimal needed by verilog
4) Run tb_algo_new.v on NCSIM (Cadence) to obtain the results
5) The completed matrix is output at M_out.txt
6) To change the input matrices size and few constants, copy the value of m,n,r,logm,logn,logr,logmr,lognr,log10n,lambda from Matlab into there corresponding names in tb_algo_new.v
