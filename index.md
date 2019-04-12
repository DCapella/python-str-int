## Python String to Integer

### [HackerRank](www.hackerrank.com)

> Read a string, S, and print its integer value; if S cannot be converted to an integer, print Bad String.

It's pretty straight forward.

### Code

* Try print(int(s))

```Python
try:
  print(int(S))
```

* Except print("Bad String")

```Python
try:
  print(int(S))
except:
  print("Bad String")
```

### Final Code

```Python
#!/bin/python3

import sys


S = input().strip()

try:
  print(int(S))
except:
  print("Bad String")
```

### Conclusion
It's always good to practice a try-except.
