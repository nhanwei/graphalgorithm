# graph algorithm

This is a study/exploration on 2 algorithms used to count frequency of distinct integers in a data stream.

Two different algorithms (queries) to find the frequency of distinct integers. 
Makes use of a counter matrix to keep track of the counts. 
Makes use of a finite field hash function to map the integer onto the counter matrix.
Simulated data from uniform and exponential distributions.

Performance varies. Depends on distribution of data, type of query, value of several parameters.
