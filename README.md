# LeetCode_Python_Learning_Notes
Learning Notes from doing exercises in LeetCode



## 9/4/2022

To **replace** *nums* with *extra*, where *nums* and *extra* are arrays.

The following line:

```python
nums[:] = extra
```

Is faster and memory usage less than:

```python
for i in range(n):
    nums[i] = extra[i]
```



**Syntax ** for two variables with two values:

```python
start, count = 0, 0
```



**Syntax** Want to reverse a string by slicing? Try this:

```
word_reversed = word[::-1]
```

