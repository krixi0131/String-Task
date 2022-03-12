# String-Task
```python
a=str(input())
mu=["A", "O", "Y", "E", "U", "I","a","o","y","e","u","i"]
for i in range(len(a)):
    if a[i] not in mu:
        if ord(a[i])<97:
            print("."+chr(ord(a[i])+32),end="")
        else:
            print("."+a[i],end="")
```            
