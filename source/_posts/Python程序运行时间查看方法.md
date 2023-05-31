---
title: Python程序运行时间查看方法
date: 2023-05-30 10:23:00
author: 培根请加蛋
img: 
top: true
hide: false
cover: true
coverImg: 
toc: true
mathjax: true
summary: Python程序运行时间查看方法
categories: Python
tags:
  - Python
---

time包查看程序运行时间

```python
import time

start_time = time.time()  # 记录程序开始运行时间
for i in range(10000000):
    pass
end_time = time.time()  # 记录程序结束运行时间
print('cost %f s' % (end_time - start_time))
```

输出

```python
>>> cost 0.179781 s
```

