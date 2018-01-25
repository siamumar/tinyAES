# tinyAES

AES implementation from [tinyAES on OpenCores](https://opencores.org/project,tiny_aes) except for the sbox. 

Sbox is implemented by logic operations, instead of tables, following [Circuit Minimization Work](http://cs-www.cs.yale.edu/homes/peralta/CircuitStuff/CMT.html) by Dr. Rene Peralta. This can be helpful to optimize the usage of BRAMs on FPGA. 
