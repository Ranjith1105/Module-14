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
from collections import deque


d = deque()


d.append(input())
d.append(input())
d.append(input())


d.popleft()


print("The deque after deletion is :")
print(d)
```

### OUTPUT
<img width="760" height="251" alt="image" src="https://github.com/user-attachments/assets/40716665-d60f-40f3-b03a-0c32b946ec63" />


### RESULT
Thus the python program for to delete elements at FRONT END of deque using a collection built-in function has been implemented and executed successfully.
