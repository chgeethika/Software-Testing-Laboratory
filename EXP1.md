# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:  20/09/2024                                                                          
### REGISTER NUMBER : 212221040032

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
i.do_while
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")
        display()

display()

```















### Output:







### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


