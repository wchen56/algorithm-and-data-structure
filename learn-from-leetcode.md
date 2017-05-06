### 461: Hamming Distance

To count 1s in the binary representation of a number n:

```python
def cnt(n):
  count = 0
  while n:
    n &= n - 1
    count += 1
  return count
```

[Here](http://www.cnblogs.com/graphics/archive/2010/06/21/1752421.html) is a blog introducing several ways to solve this problem.
