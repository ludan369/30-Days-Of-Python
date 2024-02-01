## Python 基础

### Python 语法

一个Python脚本可以在Python交互式shell中编写，也可以使用代码编辑器进行编写。Python文件的扩展名是`.py`

### Python 缩进

缩进是文本中的空白部分。在许多编程语言中，缩进用来提高代码的可读性，但Python则使用缩进来创建代码块。相比之下，其他编程语言通常使用花括号{}来创建代码块。在Python代码编写中，一个常见的错误就是处理缩进不当。

![Indentation Error](../images/indentation.png)

### 注释

注释对于提高代码的可读性以及在代码中留下备注非常重要。Python不会执行代码中的注释部分。在Python中，任何以`#`开始的文本都是注释。

**示例: 单行注释**

```shell
    # This is the first comment
    # This is the second comment
    # Python is eating the world
```

**示例: 多行注释**

在Python中，多行注释以三重引号开始`"""`，但这不是官方推荐的注释方式。因为在某些情况下，三重引号内的内容是作为字符串的一部分被赋值给变量的，而不是作为注释。

```shell
"""This is multiline comment
multiline comment takes multiple lines.
python is eating the world
"""
```

### 数据类型

在Python中有许多种数据类型。先从最常见的几种开始学起。不同的数据类型将在本文的其他部分进行详细介绍。让我们来了解一下不同的数据类型，并熟悉它们。你现在不必完全理解它们。

#### Number

- [整数]Integer: Integer(negative, zero and positive) numbers
    Example:
    ... -3, -2, -1, 0, 1, 2, 3 ...
- [浮点数]Float: [小数]Decimal number
    Example
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex
    Example
    1 + j, 2 + 4j

#### String

字符串是由一个或多个字符组成的集合，用单引号或双引号包裹。如果一个字符串包含多行，则需使用三重引号。

**Example:**

```py
'Asabeneh'
'Finland'
'Python'
'I love teaching'
'I hope you are enjoying the first day of 30DaysOfPython Challenge'
```

#### Booleans

布尔类型的值只有`True`或是`False`两种，其中`T`和`F`需要大写。

**Example:**

```python
    True  #  Is the light on? If it is on, then the value is True
    False # Is the light on? If it is off, then the value is False
```

#### List

Python中的列表是一种有序集合，它允许存储不同数据类型的元素。这与JavaScript中的数组类似。

**Example:**

```py
[0, 1, 2, 3, 4, 5]  # 相同数据类型的一组数字
['Banana', 'Orange', 'Mango', 'Avocado'] # 相同数据类型的一组字符串[水果]
['Finland','Estonia', 'Sweden','Norway'] # 相同数据类型的一组字符串[国家]
['Banana', 10, False, 9.81] # 一个列表中包含不同的数据类型 - 字符串(string), 整数(integer), 布尔值(boolean) 和 浮点值(float)
```

#### Dictionary
