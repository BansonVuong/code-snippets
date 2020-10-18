---
title: list_to_tuple
tags: list,tuple,intermediate
---

Decapitalizes the first letter of a string.

- Capitalize the first letter of each word in the string.

```py
import random
def list_to_tuple(l):
    t = ()
    for i in l:
        t.append(i)
    return t
```

```py
list_to_tuple([1,2,3,4]) #(1,2,3,4)
```
