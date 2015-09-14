#Programming Assignment 2 – Sorting

###Due September 19, 2015 11:59pm

You are consulting for a small restaurant chain which wants to expand its locations nationwide. The company executives would like to start their expansion by placing locations in the most densely populated areas first. To assist them, you have been asked to produce a list of Census Tracts ordered by population density. You have been given a list of the approximately 74,000 Census Tracts in the United States. The name, area (in square kilometers), total population, and population density (in people per square kilometer) are given to you for each tract. Your job will be to write a program which reads this data, sorts the tracts by population density, and outputs all of this data sorted by population density (from smallest to largest).

###Input File Format

Each record of the input file is on a separate line. Each line contains (in this order) a name (string), an area in square kilometers (double), a population count (int), and a population density (double). A pipe ( | ) is used to separate the different attributes of each record. Below are three example records from the input file:
Census Tract 201, Autauga County, Alabama|9.84473419420788|1808|183.651479494869 Census Tract 202, Autauga County, Alabama|3.34583234555866|2355|703.860730836106 Census Tract 203, Autauga County, Alabama|5.35750339330735|3057|570.60159846447
You can download the input file from http://students.cse.unt.edu/~martyo/3110sum2015/pop_density.txt To download this file onto the CSE machines, enter the following command and the prompt:

***
wget http://students.cse.unt.edu/~martyo/3110sum2015/pop_density.txt
***
###Sorting Algorithm Requirements

For this assignment, you will implement two different sorting techniques and examine their performances: MergeSort and QuickSort. Do not use a C/C++ library for the sorting. You must write your own code to perform the sorting operations. For QuickSort, choose the pivot using the median-of-three approach. You must write a separate program for each of these two sorting techniques. Your programs should track and output the execution time for each sorting method. http://www.cplusplus.com/reference/ctime/clock/ provides a simple mechanism for timing code using clicks. Only time the sort routines, not the entire program.

###Program Input/Output Requirements

Your programs must use standard input with file redirection (similar to Programming Assignment 1). Each of your two programs must create a new file named pop_density_sorted.txt which contains the records from the input file sorted in ascending order of population density. The format of the output file must be identical to that of the input file. The only difference between the input file and output file will be the order of the records. In other words, each record must still contain the name, area, population count, and population density.

Each of your two programs must also print the number of clicks taken by the sorting procedure. Coding and Submission 

###Requirements

All programs must be written in C/C++. You must comment your code appropriately. Revisit the instructions for Programming Assignment 1 for commenting requirements. Your code must compile and execute properly on the CSE machines. If there are any special compilation instructions, include a file README.txt specifying the compilation procedure. Submit your programs to PROGRAM2 using the project command. Only submit the source code and README.txt file (if one exists). Do not submit the input or output files.
￼￼￼
