# To-Do-List
The Fucntions of this:

1.Data Enter

2.Data display

3.Edit Data

4.Delete Data

5.Data Permanent Delete

6.Deleted data edit

7.Data Retrival

8.Congradulations on finishing your To-Do List

DATA ENTER:
```python
l1=[]
while(True):
  l1.append(input("Please Enter a Task: "))
  a=input("Do you want to stop adding tasks? Say Yes or No.(Case Sensitive): ")
  if (a=="Yes"):
    break
```

Display Data:
```python
print("These are your tasks:")
for i in range(len(l1)):
  print(l1[i])
```
