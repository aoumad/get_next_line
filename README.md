# get_next_line
 Get Next Line is a project at 42. It is a function that reads a file and allows you to read a line ending with a newline character from a file descriptor. When you call the function again on the same file, it grabs the next line.

## The Challenge 
This project asked us to create a function in C allowing us to read line by line from a file descriptor. We could not use EOF as a stopping condition within our code. Our function had to behave well with a buffer size of 1, as well as a buffer size of 5000, and any buffer in between. Global variables, for loops, and functions longer than 25 lines were forbidden. We were permitted to use only read, malloc and free from the libc. Extra credit was given if we used a single static variable and/or if our function could handle multiple file descriptors. 

## Learning objectives 
This project allowed me to gain a deeper understanding of allocations, whether they happen on the stack memory or in the heap memory, the manipulation and the life cycle of a buffer, and the unexpected complexity implied in the use of one or many static variables.

## Usage
This function is to be used in coordination with my previous project [Libft](https://github.com/aoumad/42_Libft), a library of C functions written from scratch. It has now been added to the libft. In order to test this funtion out, please follow the usage instructions from the repositary. 
