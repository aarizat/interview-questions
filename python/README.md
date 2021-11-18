# Python Questions :snake:

1 - Mention Python Data Types

* [Here](https://www.javatpoint.com/python-data-types) you can find info about it.

> It's highly recomended to know about what types are mutable and inmutables. That's why I'll incude some resources:

* [What are mutable and immutable objects in Python3?](https://www.educative.io/edpresso/what-are-mutable-and-immutable-objects-in-python3)
* [Mutable vs Immutable Objects in Python](https://www.freecodecamp.org/news/mutable-vs-immutable-objects-python/)


2 - Differences between a list and a tuple.

* Read this [post](https://stackabuse.com/lists-vs-tuples-in-python) to learn about these defferences

3 - What is the best way to copy a list?
* Talk about deep and shallow copy. Read this [post](https://www.programiz.com/python-programming/shallow-deep-copy)

4 - After calling this function twice, what is the output? Why?
``` py
>>> def default_list(L=[]):
>>>     L.append(1)
>>>     print(L)

>>> default_list()
# output ???
>>> default_list()
# output ???
```
* In order to understand this behavior, read this [post](https://docs.python-guide.org/writing/gotchas/)

5 - What is the output of this code?
``` py
>>> a = [1, 2, 3]
>>> b = a
>>> a.append([4, 5])
>>> print(b)
# output ???
```
6 - Which of the following two implementations would you prefer? Why?
``` py
# First option

>>> def print_numbers(a, b):
>>>     for i in range(a, b+1):
>>>         print(i)
```

``` py
# Second option

>>> def print_numbers(a, b):
>>>     nums = [i for i in range(a, b+1)]
>>>     for i in nums:
>>>         print(i)
```
> Note: The functions perform the same.

7 - what is a Lambda function ?

* In this article you can learn about [Lambda functions](https://realpython.com/python-lambda/)

8 - Explain the output of these two lines of code.

``` py
>>> round(1.5)
2
>>> round(2.5)
2
```
* Read about [round-bias](https://realpython.com/python-rounding/)

9 - What is a decorator? Write an example.

* [Decorators](https://www.programiz.com/python-programming/decorator)

10 - What is the output after executing the following code snippet:
``` py
>>> def func(num):
>>>     return lambda x: num + x

>>> print(func(2)(3))
# ouput ?
>>> print(func("x")("y") + "z")
# output ?
```

11 - What is generator and generator expresion? When would you use a generator?

* Learn about [generators](https://www.programiz.com/python-programming/generator)

12 - What is an iterator?

* [Python Iterators](https://www.programiz.com/python-programming/iterator)
* [The Iterator Protocol: How "For Loops" Work in Python](https://treyhunner.com/2016/12/python-iterator-protocol-how-for-loops-work/)

13 - What is the difference between a generator function and normal function?

14 - How does Python manage the memory?

* Read [here](https://realpython.com/python-memory-management/)

15 - What is the GIL (Global Interpreter Lock)?

* You can read this [post](https://realpython.com/python-gil/)
* I also recomend to watch this [video](https://www.youtube.com/watch?v=-VH2EvvOCzU)

16 - How do you implement an Enumerador?

* Read [this](https://docs.python.org/3/library/enum.html)

17 - What is a Context Manager? How do you implement a Context Manager ? What happen if occur an exception?

* Read about [Context Managers](https://realpython.com/python-with-statement/#creating-custom-context-managers)

18 - Explain the output of this code.
``` py
>>> numbers = [1, 2, 3, 5, 7]
>>> squares = (n**2 for n in numbers)
>>> 4 in squares
True
>>> 4 in squares
False
```
* Read this article in order to understand this output. [Loop better: A deeper look at iteration in Python](https://opensource.com/article/18/3/loop-better-deeper-look-iteration-python)

19 - How do you manage Python Exceptions ?
``` py
>>> try:
>>>     print(x)
>>> except:
>>>     print("An exception occurred")
```
> It's highly recommended that you learn to write user-defined exceptions.

* [Here](https://www.programiz.com/python-programming/user-defined-exception) you can learn about this topic.

20 - What are `*args` and `**kwargs` used in Python for?

* [Python *args and **kwargs](https://www.programiz.com/python-programming/args-and-kwargs#:~:text=*args%20and%20**kwargs%20are,to%20take%20variable%20length%20argument.&text=**kwargs%20passes%20variable%20number,kwargs%20make%20the%20function%20flexible.)

21 - How does Python implement concurrency an parallelism?

22 - How do you implement a coroutine in Python?
