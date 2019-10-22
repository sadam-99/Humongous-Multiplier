Results and Conclusions:

We tested on different files from 1 digit to 1 million digits multiplication.
For example for multiplication of A (10^5) X B(10^5) took time of 900 seconds in single thread and in multi threading 
It took aapproximately 820 seconds.
For example for multiplication of A (10^6) X B(10^6) took time of 2 hours 27 minutes in single thread and in multi threading It took aapproximately 2 hours 23 minutes.



# main() function description-
        ## multiply() function call.
        ## opening of the files using fopen.
        ## calculating the multiplication of the 2 Numbers present in the text files
        ## writing the contents for all the files into the the output file.

# Names of Input Files-
        a.txt
        b.txt 
       

# Output File name-
        For Single Thread- c1.txt
        For Multi Thread-  c2.txt


# How to use the code:
        ## Compile for single thread:
                gcc prog1.c -o prog1.out
        ## Compile for multiple-Thread:
                gcc prog2.c -o prog2.out -lpthread
        ## Run :
                For Single Thread- c1.txt
                - ./prog1.out 
                For Multi-Thread-  c2.txt
                - ./prog2.out 
                

# Error Checking:
        ##  If the thread count less than 0 and greater than 100. Provide Default thread count to 8

# Some Details for Input and Output files for Results are also provided in description.txt
