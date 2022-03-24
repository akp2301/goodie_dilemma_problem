# goodie_dilemma_problem #


## The problem: ##
- The problem I selected is to resolve a dilemma of distributing a few goodies among the employees in a company such that each employee gets one goodie in a scenario and we have to find the least difference between the goodie price distributed.

## The solution concept: ##
1. Here we first we read input file path and output file path(optional) as arguments from console. 
2. Then read the input file. 
3. After that split the string into key-value pair . The numeric value or price is put as its key. 
4. We need atleast 2 employees to find the difference , so check it
5. Then make the keys in the key value pair into a list and sort it.  
6. Then we have to go through each element and find the difference with the least value. 
7. And now we have the best least difference.
8. Then write the output into output file.


## To run the program ##
- Go to goodie-dilemma folder. cd goodie-dilemma/  
- Run python3 goodie_dilemma_solution.py -i <input_file_path> -o <output_filr_path> 
- Eg : python3 goodie_dilemma_solution.py -i sample_input2.txt -o output2.txt
