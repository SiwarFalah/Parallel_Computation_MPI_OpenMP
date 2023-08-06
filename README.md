# Parallel_Computation_MPI_OpenMP

This is a parallel program that calculates the maximum value of a given mathematical function for an array of numbers using OpenMP and MPI
To run this program on terminal:

Enter this line : sudo apt-get install libopenmpi-dev

make - mpicc -fopenmp main.c functions.c -o histogram -lm

make run - mpirun -np 2 ./histogram <input.txt 10000

Note: For change the number of threads in the program you need to change the variable NUM_THREADS that in file functions.h
