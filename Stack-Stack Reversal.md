# # Stack-Stack Reversal Program 🔁

This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

## 🎯 Aim

To write a Python program that reverses the values in a stack using standard stack operations.

## 📋 Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
```py

stack = []
  n=int(input())
  for i in range(n):
     value=int(input())
     stack.append(value)
  reverse= []
  while stack:
     reverse.append(stack.pop())
  print(reverse)
```
## 🧪 Sample Input and Output

<img width="496" height="282" alt="444800618-b66adf3b-f74c-4627-99a6-052cbf5ae78a" src="https://github.com/user-attachments/assets/3015d49f-8955-49ad-aa1e-bea58848089e" />

## Result
Thus, the program has been executed successfully.
