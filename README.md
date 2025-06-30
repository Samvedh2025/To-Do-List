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
l2=[]
count=len(l1)
while(True):
  l1.append(input("Please Enter a Task: "))
  a=input("Do you want to stop adding tasks? Say Yes or No.(Case Sensitive): ")
  count=count+1
  l2.append(count)
  if (a=="Yes"):
    break
```

Display Data:
```python
print("These are your tasks:")
for i in range(len(l1)):
  print(str(l2[i]) + ".",l1[i])
```

Edit Data:
```python
b=input("What is the number of the task you want to edit? Just enter the number: ")
c=input("What do you want to change it to? please enter here: ")
b=int(b)
l1[b-1]= c
```
Deleting Data:
```python
b=input("What is the Number of the task you want to delete? Just enter the number: ")
b=int(b)
l1.pop(b-1)
```
