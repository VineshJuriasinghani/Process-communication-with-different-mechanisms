# Process-communication-with-different-mechanisms
In this Project I have implemented different types of inter-process communication mechanisms. 

Each mechanism have separate file with respect to each IPC & Numbers are input through the file, which have a list of numbers

⦁	In Message passing, first it takes message and number which will be sent to the receiver to print that message and search the entered number from text file and prints the location of that number in file and how many times it occurs in file.

⦁	In Named pipe, during executing sender will send the read array of inputs from text file to the receiver, and receiver sort the values of array and store them into the new text output file.

⦁	In ordinary pipe, first it takes a number in input and child process loads the contents of file into the array and write them into the buffer, after child process completes, parent process read the contents of array from the buffer and search the user entered number from that array and prints the location of that content in file, also how many times it is in file.

⦁	In shared memory, after creation of shared memory and it attachment with the process it takes a input from user to pass it to its second inter-process, after passing the second process will store all the contents of file in a array and search the user entered number from them rather it is in file or not, if it is present in file then it will print the location and occurrence of the number in file.
