# Memory-Management-Simulation
Memory Management system simulation

The program is meant to do a comparative study of **paging system** and **non-paging** system, also performance of paging system's dependence of several parameters such as page-replacement algorithm(LRU,FIFO,random) , swap-space size, page size.

The entire code is divided into 3 sub modules  
 - [Data Generator](Code-Memory-Management-Simulator/data_generator.h) to simulate the data generation.
 - [Non-Paging System](non_paging_system.h) implements the contiguos allocation(variable partition) technique using first fit algorithm.
 - [Paging System](paging_system.h) implements paging system.

Lastly [main.cpp](main.cpp) integrates all these ,also several perfomance metrics like page hit/miss ratio, page replacement time,etc.


