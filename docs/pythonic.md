# 1 Python: dict 小技巧

注意：**Python 3 中的 `dict` 是有序的。**

## 1.1 别样的合并字典技巧

```python
x = {'a':1,'b':2}
y = dict(b=3, d=4)

d = {**x,**y}
print(d)
```

由输出结果可以看出：新的值会覆盖旧值。
