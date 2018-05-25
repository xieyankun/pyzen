# pyzen
python

"#" 是注释

每一行都是一个语句，当语句以冒号:结尾时，缩进的语句视为代码块。

# pass
作用：
- 空语句 do nothing
- 保证格式完整
- 保证语义完整

```python
if true:
    pass #do nothing
else:
    #do something
```

pass语句在函数中的作用

当你在编写一个程序时，执行语句部分思路还没有完成，这时你可以用pass语句来占位，也可以当做是一个标记，是要过后来完成的代码。比如下面这样：

```python
def iplaypython():
    pass
```
函数体部分暂时还没有完成，又不能空着不写内容，因此可以用pass来替代占个位置。

pass语句在循环中的作用
