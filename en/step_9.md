## List operations

You can apply an operation or function to all items in a list:

```
In[21]:= 2 * {1, 2, 3, 4, 5}

Out[21]: {2, 4, 6, 8, 10}

In[22]:= {1, 2, 3, 4, 5} ^ 2

Out[22]: {1, 4, 9, 16, 25}

In[23]:= Sqrt[{1, 2, 3, 4, 5}]

Out[23]: {1, Sqrt[2], Sqrt[3], 2, Sqrt[5]}
```

Note that in the last example the square roots of `1` and `4` were given exactly, as they yield integer value; however the square roots of `2`, `3` and `5`, which are irrational, are given symbolically.

