### delegator.py
---
https://github.com/kennethreitz/delegator.py

```py
// tests/test_chain.py
import pytest
import delegator

def test_chain():
  c = delegator.chain("seq 4 | awk '{ print $0 \" test\"; }'")
  assert c.out == '1 test\n2 test\n3 test\n4 test\n'
```

```
```

```
```
