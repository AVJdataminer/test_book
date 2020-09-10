# DRILLS 1 

1. Assign the sum of -10 and 2 to `a`.
2. Assign the absolute value of `a` to `b`.
3. Assign `b` minus 1 as `d`.
4. Print the result of `d`. What is the value? What type is this variable?



```python
a = -10 + 2
b = abs(a)
d = b - 1

print(d)
print(type(d))
```

    7
    <class 'int'>


# DRILL 2

1. Create a list containing the values `North`, `East`, `South` and `West`.  
2. What is the result of the below?

```
len(['Monday','Tuesday','Wednesday','Thursday','Friday',['Saturday','Sunday']])
```


```python
directions = ['North','East','South','West']
print(directions)

print(len(['Monday','Tuesday','Wednesday','Thursday','Friday',['Saturday','Sunday']]))
```

    ['North', 'East', 'South', 'West']
    6


# DRILL 3

1. What do you expect to be the result of the following? Run the code and see how you did.

```
my_week = (['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday'])
my_week.sort()
print(my_week)
```

2. Pass the `clear()` method to `my_week` from above. Re-print `my_week`. What happens?


```python
my_week = (['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday'])
my_week.sort()
print(my_week)
```

    ['Friday', 'Monday', 'Saturday', 'Sunday', 'Thursday', 'Tuesday', 'Wednesday']



```python
my_week.clear()
print(my_week)
```

    []


## Drill little 1

Practice some more slicing below:


```python
my_list = [7,12,5,10,9]

# Get the first through third elements
print(my_list[0:3])

# Get the third-last to second-last elements
print(my_list[-3:-1])

# Get the second through last elements
print(my_list[1:5])

```

    [7, 12, 5]
    [5, 10]
    [12, 5, 10, 9]


## DRILL little 2

Practice slicing lists below. 

These operations will work the same regardless of whether your list contains floats, strings, or other data types.


```python
this_list = ["Slicing","works","on","lists","of","strings","identically"]

# Get the third to final elements
print(this_list[2:])


# Get everything up to the fourth element
print(this_list[:4])


# Get everything starting with the second-last element
print(this_list[-2:])
```

    ['on', 'lists', 'of', 'strings', 'identically']
    ['Slicing', 'works', 'on', 'lists']
    ['strings', 'identically']




## Drill little 3

The `factorial()` function from `math` will take the factorial of a number `X`.

Find the factorial of 10 using this function.


```python
import math

math.factorial(10)
```



    3628800



# Drill 4

Install the `seaborn` package.


```python
#!pip install seaborn
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MzAzMDE2XX0=
-->