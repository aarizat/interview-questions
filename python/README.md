# Python Questions

1 - Mention the Built-in types in Python

2 - Difference between a list and a tuple.

3 - What is the best way to copy a list?

4 - After calling the function twice, what is the output? Why?
```
def default_list(L=[]):
    L.append(1)
    print(L)
```
5 - What is the output of this code?
```
a = [1, 2, 3]
b = a
a.append([4, 5])
print(b)
```
6 - Which of the following two implementations would you prefer? Why?
```
# First option

def print_numbers(a, b):
    for i in range(a, b+1):
        print(i)
```

```
# Second option

def print_numbers(a, b):
    nums = [i for i in range(a, b+1)]
    for i in nums:
        print(i)
```
> Note: The functions perform the same.

7 - what is a Lambda function ? 

8 - Explain the output of these two lines of code.

```
> round(1.5)
2
> round(2.5)
2
```
9 - What is a decorator? Write an example.

10 - What is generator and generator expresion? When would you use a generator?

11 - What is an iterator?

12 - What is the difference between a generator function and function?

13 - How does Python manage the memory?

14 - What is the GIL (Global Interpreter Lock)?

15 - How do you implement an Enumerador?

16 - What is a Context Manager? How do you implement a Context Manager ? What happen if occur an exception?

17 - Explain the output of this code.
```
> squares = (x ** 2 for x in range(1, 10))
> 4 in squares
True
> 4 in squares
False
```
