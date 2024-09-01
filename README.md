# Antonio-ECEC-ECE2112-Experiment2
##### General summaries of each problem. see main code for a more detailed breakdown
## Normalization Problem
#### The code is fairly straight-forward. First, it creates 5x5 array named X with 25 elements (for the sake of simplicity and replication, i decided to just use the first 25 counting numbers as the element values as opposed to making a random by random array). Then, it gets the normalized value of X using the provided equation (note that I no longer assigned separate variables for the mean and the standard deviation. this is to prevent code clutter). Then finally, it saves the normalized X to X_normalized.npy
## Divisible by 3 Problem
#### This code too is fairly straight-forward. It first creates an array of the first 100 counting numbers. Then it squares each counting number. After this, it reshapes the array to a 10x10 array. Then, using a modulo argument, it finds the indeces that are divisible by three and returns the number to an array. This array is then saved to div_by_3.npy.
