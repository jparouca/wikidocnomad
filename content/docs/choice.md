---
title: Choice
weight: 1
type: docs
prev: /docs/
next: docs/result/
---

##### Also known as Either in some languages this monad offers you the possibility to choose one of two types to be hold by its instance.

Example:

```go {filename="main.go"}
public Choice<int, string> Choose(bool returnInt)
{
    if(returnInt)
        return 1;

    return "This is a Choice!";
}
```
