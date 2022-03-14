# Homework3

The homework is about implementing the linux commands using c programs. 

In this program i have used the homework2 program that is provided on the canvas. 

For -E, -e commands for this commands i have declared two more flags for -E and -e commands in flagargs structure. 

In the command line arguments if there is -e or -E by using the swithc case and optorg i changed the flags of e_flag and E_flag to value 1. 

And than declared an array to tokenized optarg to get the command linux command ex "ls -l" and passed this to the array of linux command. 

And neccessary arguments are passed to print function to check the conditions on the given arguments, For -E and -e i have concatinated the linux array and the file path and also " ". 

