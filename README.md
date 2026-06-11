## PYTHON PROGRAMMING MODULE 3
## NAME: HARSHINI R
## REGISTER NUMBER: 212223220033
## Ex 01:  List Operations in Python: Sum of List Items
##  Aim
To write a Python program that calculates the **sum of all elements** in a list.

##  Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

##  Program
```
items=[153,147,124,102]
print(sum(items))
```

## Output

<img width="894" height="254" alt="604174434-af7836e2-028f-4d90-8a55-44f8c4df5e6a" src="https://github.com/user-attachments/assets/2e1d623b-6ae5-4ce9-8a7e-70a1eeaf7f19" />

## Result
Thus, the program was executed successfully.

# Ex 02: Regex in Python: Filter Words Without the Letter 'e'

##  Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

##  Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

##  Program
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```
## Output

<img width="897" height="287" alt="604175025-729356d3-d1e6-4ad7-a6e5-ac43f58134d3" src="https://github.com/user-attachments/assets/a3854b5d-4253-4147-b3e2-078806f50ae3" />

## Result
Thus, the program was executed successfully.

#  Ex 03: Strings-Remove Nth Index Character from a String

##  Aim
To write a Python program that accepts a string and removes the character at a specified index.

##  Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

##  Program
```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```

## Output

<img width="1048" height="260" alt="604175963-02c4b5ca-9d3e-46af-8c63-15d07b4774e0" src="https://github.com/user-attachments/assets/713c5df2-ca57-495b-a0c8-3c89b6834707" />


## Result
Thus, the program was executed successfully.


# Ex 04: Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program
```
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
## Output

<img width="1046" height="182" alt="604176186-a502843e-84df-4de3-bf72-a32e8809c2e5" src="https://github.com/user-attachments/assets/7edd1c44-2778-4d4a-827c-12554a12551b" />

## Result
Thus, the program was executed successfully.


# Ex 05: Tuple in Python: Check Element Existence

##  Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

##  Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

##  Program
```
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)
```
## Output

<img width="1047" height="296" alt="604176383-1ef118b9-eb02-456f-9f2c-6be1d5c79de9" src="https://github.com/user-attachments/assets/b8968ace-19cc-4487-97c9-0cbe8e72b6b9" />

## Result
Thus, the program was executed successfully.
