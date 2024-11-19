---
title: python lang logs
date: 2024-11-19T21:35:14.213Z
---
-------------------------//
-------------------------//25
---------------//15
-----//5




---------------//
-----//
-----//
-----//

-----//


---------------//
-----//
-----//
-----//
**bold**

-----//
/﻿/heap queue
https://docs.python.org/3/library/heapq.html

heapq.nlargest(n, iterable, key=None)

def heapsort(iterable):
    h = []
    for value in iterable:
        heappush(h, value)
    return [heappop(h) for i in range(len(h))]

heapsort([1, 3, 5, 7, 9, 2, 4, 6, 8, 0])


/﻿/
#﻿ Iterator vs Iterable
> https://www.w3schools.com/python/python_iterators.asp

`﻿``
mytuple = ("apple", "banana", "cherry")

for x in mytuple:
  print(x)
`﻿``

mystr = "banana"
myit = iter(mystr)

print(next(myit))



-------------------------//
-------------------------//
