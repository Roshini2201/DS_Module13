# EX1.C Implementation of Tower of Hanoi
## DATE:12.03.25
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. Start the program.  
2. Set the number of disks `n = 2`.  
3. Call the recursive function `TOH(n, 'A', 'B', 'C')` where `'A'` is the source rod, `'B'` is the destination rod, and `'C'` is the auxiliary rod.  
4. In the `TOH` function, if `n > 0`, recursively move `n-1` disks from source to auxiliary using destination as helper.  
5. Print the move of the current disk from source to destination.  
6. Recursively move `n-1` disks from auxiliary to destination using source as helper.  
7. End the program.

## Program:
```
Program to implement Tower of Hanoi
Developed by: ROSHINI S 
RegisterNumber: 212223240142

#include<stdio.h># EX1.C Implementation of Tower of Hanoi
## DATE:12.03.25
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. Start the program.  
2. Set the number of disks `n = 2`.  
3. Call the recursive function `TOH(n, 'A', 'B', 'C')` where `'A'` is the source rod, `'B'` is the destination rod, and `'C'` is the auxiliary rod.  
4. In the `TOH` function, if `n > 0`, recursively move `n-1` disks from source to auxiliary using destination as helper.  
5. Print the move of the current disk from source to destination.  
6. Recursively move `n-1` disks from auxiliary to destination using source as helper.  
7. End the program.

## Program:
```


## Output:
![image](https://github.com/user-attachments/assets/db211b62-e5f7-40b2-ab7f-39ae2f56877b)


## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
