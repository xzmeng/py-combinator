PyCombinator
============
A tiny interpreter implement call expression and  
lambda expression on numbers, with Python syntax

```python
➜  py-combinator python3 repl.py
> mul(add(3, 4), sub(5, 6))
-7
> (lambda x: lambda y: truediv(x, y))(3)(4)
0.75
> (lambda x: lambda y: truediv(x, y))(3)(0)
ZeroDivisionError: division by zero
```