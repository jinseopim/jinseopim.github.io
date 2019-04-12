---
layout: post
title:  "첫번째 포스팅"
date: 2019-04-12 11:19:23 +0700
categories: [python, codefights]
---

#안녕

**첫번째 페이지야**


```python
def ReverseBit(x):
  x = bin(x).replace('0b', '')
  reverse_text = ''
  for l in range(len(x)-1, -1, -1):
      reverse_text = reverse_text + x[l]
  return int(reverse_text, 2)

>>> ReverseBit(234)
87
>>>
```

```r
aaaa <- data.frame
library(dplyr)
```
