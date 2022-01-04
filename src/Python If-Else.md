##**[Python If-Else](https://www.hackerrank.com/challenges/py-if-else/problem?isFullScreen=true&h_r=next-challenge&h_v=zen)**\
\

**Solution**
```python 3.0
#!/bin/python3

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())
    if (n%2==0) and (2<=n) and n<=5:
        print("Not Weird")
    elif (n%2==0) and (6<=n) and n<=20:
        print("Weird")
    elif (n%2==0) and n>20:
        print("Not Weird")
    elif n%2 !=0:
        print("Weird")
```