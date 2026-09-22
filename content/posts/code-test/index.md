---
title: "代码高亮测试"
date: 2026-09-22
draft: false
description: "测试 Hugo + PaperMod 的代码高亮功能。"

tags:
  - Hugo
  - 编程
  - 代码高亮

categories:
  - 技术折腾
---

# 代码高亮测试

以后我的博客会记录很多代码，所以先测试一下代码高亮。

## Python

```python
def hello():
    print("Hello, Zhang Luchuan!")

hello()
```

## Bash

```bash
cd ~/my-blog
hugo server
git status
```

## C

```c
#include <stdio.h>

int main() {
    printf("Hello World!\n");
    return 0;
}
```

## JavaScript

```javascript
function hello(name) {
    console.log(`Hello, ${name}!`);
}

hello("Zhang Luchuan");
```

## JSON

```json
{
  "name": "张鲁川",
  "blog": "数字花园",
  "topics": [
    "信息安全",
    "AI",
    "Python"
  ]
}
```

## 图片测试

这是我的第一张博客图片：

{{< figure
    src="ER0A2518.JPG"
    alt="我的第一张博客图片"
    caption="我的第一张博客图片"
>}}