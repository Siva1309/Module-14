
# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
import collections
a=input()
b=input()
c=input()
de=collections.deque([a,b,c])
de.popleft()
print("The deque after deletion is :")
print(de)
```

### OUTPUT
![Screenshot (260)](https://github.com/user-attachments/assets/4741e820-b131-4817-99b7-f8e156bd09d8)


### RESULT
Thus the python program is initialised and executed successfully.
