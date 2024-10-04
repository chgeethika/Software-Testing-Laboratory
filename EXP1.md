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
ii.) while…do
```
start = input("Enter a positive value for START: ")
end = input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")

```
iii.) switch
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    n = input('Enter a value for N: ')
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()

```
iv.) if else
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    try:
        a = int(a)
        b = int(b)
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()

```
v.) for
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")
iterate()

```















### Output:
![Screenshot (687)](https://github.com/user-attachments/assets/08289d18-a396-46ce-98c7-ac97023e1dd6)


![Screenshot (688)](https://github.com/user-attachments/assets/bdf5f81e-8b57-4180-9683-3f3b26033740)


![Screenshot (689)](https://github.com/user-attachments/assets/c4213d71-9949-4ae6-86da-812d558d1558)


![Screenshot (690)](https://github.com/user-attachments/assets/9634e933-793f-4f05-93ad-341a3954c131)

![Screenshot (691)](https://github.com/user-attachments/assets/e17c702b-fc3f-443e-ad1c-f0e4297a2519)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


