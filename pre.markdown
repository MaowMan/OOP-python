# 先備知識

1. 輸入輸出

``` python

print("Hello World")

n = int(input("please input a number"))
print(n * n)

```

2. 變數

``` python

number = int("25")

print(number + 7)

string = str(25)

print(string + "7")

boolean = True

```

3. 流程控制

```python

statement_1 = True

statement_2 = False

if statement_1 and statement_2 :
    print("All true")
elif statement_2 or statement_2 :
    print("Some true)
else:
    print("None true")

```

4. 迴圈

```python

for i in range(1,50,7):
    print(i)


statement = True

while statement :
    print("Yes")


```

5. 函式

```python

def square(n):
    return n*n

def fib(n):
    if n==0 or n==1:
        return 1
    else:
        return fib(n-1) + fib (n-2) 

print(square(5))

print(fib(20))

```

6. 陣列

```python

array = [1,2,3,4,5]

array.append(6)

array.append("END")

array.append([])

print(array[1:-1])

print(len(array))

array.reverse()

array.sort()

```

7. 捕捉錯誤

```python

array=[1,4,3,6,7]

n=int(input())

try:
    print(array[n])
except(IndexError):
    print("Array out of range")

```

8. 引用

```python
import tkinter

from tkinter import *

import tkinter as tk
```



