collatz_problem
===============

A solution to the SPOJ problem PROBTNPO written for the Summer 2013 CS373 course at UT-Austin.
This implementation uses a meta cache which stores the precomputed values of max cycle lengths for 2000 subintervals from 1 to 1,000,000. Each subinterval is of equal length.
Using a meta-cache speeds up the execution time at the expense of memory.

Currently, this submission takes 0.09s on average to execute on SPOJ. 
