Program takes 50ms to run. 

The main time consumptions are the iterators to read the JSON records, and the for loops and nested for loops to read each record which contained a key word as well as all references from that record. 

Once the program gets the keyword, it will ask for the input file. If the file IS NOT A JSON IT WILL NOT WORK. This program works under the impression that each line == 1 single JSON record. After the program confirms the file is correct and acceptable, it stores each keyword acceptable based record in a linked list of JSON Objects, then prints out the name and reference ID.
