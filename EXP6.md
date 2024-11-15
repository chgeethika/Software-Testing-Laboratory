# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE: 20/10/2024                                                                          
### REGISTER NUMBER : 212221040032
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:
```
def Palindrome(string):
    for i in range(0, len(string) // 2):
        if string[i] != string[len(string) - i - 1]:
            return False
    return True

s = input("Enter a string: ")
c = 1
for i in s:
    if not i.isalpha():
        c = 0
        break  
if c == 0:
    print("Enter a valid string")
else:
    answer = Palindrome(s)
    if answer:
        print("The given string is a palindrome")
    else:
        print("The given string is not a palindrome")
```












### Output:

![Screenshot (712)](https://github.com/user-attachments/assets/37869275-5501-4d74-8af3-c04548ed9295)




### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
