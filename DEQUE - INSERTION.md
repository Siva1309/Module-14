# Exp.No:39  
## DEQUE - INSERTION

---

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

---

### PROGRAM  

```
import collections
a=int(input())
b=int(input())
c=int(input())
d=collections.deque([a,b,c])
d.append(14)
d.append(15)
print("The deque after appending at right is : ")
print(d)

```

### OUTPUT
![Screenshot (261)](https://github.com/user-attachments/assets/c7e96fbd-4afe-4dcd-b6af-53cedbcec71e)

### RESULT
Thus the python program is initialised and executed successfully.
