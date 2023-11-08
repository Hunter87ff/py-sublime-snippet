# Documentation

In this documentation, `$1` represents the first tabbed input, all the way to `$n`. `$0` represents the last place you end up in after you’re done tabbing. If there are two `$n`, e.g. `$1 f($1)`, then that means a caret will be created at each of these locations. If you see `${2:$1}` then that means that you can input part of `$2` first, in this case `$1`, and then tab over to the whole expression, which in this case is `$2`.

To activate a snippet just type the trigger and then press tab button.

Although the snippets show up as having four spaces in the reference, in the actual snippet it will substitute it with your used setting.

## Table of Contents

- [Loops](#loops)
- [Utilities](#utilities)
- [Conditional Statements](#conditional)
- [Classes](#classes)
- [Lambda](#lambda)
- [Functions](#functions)

## Loops

A collection of loop auto completions.

**Trigger**: for

```py
for i in list_:
    #codes
```

**Trigger**: while

```py
while True:
    #do something

```

**Trigger**: range

```py
for i in range(count):
    #code
```


## Utilities

Utilities will be uploading day by day, not only basic python snippets but also for different libraries

**Trigger**: append

```py
list.append(element)
```

**Trigger**: try

```py
try:
    #code
except Exception as e:
    raise e
else:
    pass
```

**Trigger**: with

```py
with open("file", "r") as f:
    data = f.read()
```


## Conditional Statements

**Trigger**: if

```py
if True:
     #code 
```

**Trigger**: ifelse

```py
if True :
    #code

else :
    #code
```

**Trigger**: ifelif

```py
if True :
    #code

elif False :
    #code

else :
    #code


```

## Classes


**Trigger**: class

```py
class ClassName(object) :
    def __init__(self, arg):
        super(ClassName, self).__init__()
        self.arg = arg
    def function(param):
        #Code

```

**Trigger**: @classmethod

```py
    @classmethod
    def argument(cls):
        #code
        return cls.arg
```

**Trigger**: @staticmethod

```py
    @staticmethod
    def static_method(*args, **kwargs):
        #code
        return args
```

## Lambda

Snippets to insert Python3 lambdas of different flavours.

**Trigger**: lmax(lambda usage in max func)
```py
max(list_, key=lambda s: x['rating'])
```


**Trigger**: lmin(lambda usage in min func)
```py
min(list_, key=lambda s: x['rating'])
```


## Functions

**Trigger**: def

```py
def function_name(*args, **kwargs) :
    def
```

**Trigger**: async

```py
async def func(param1, param2):
    #await some_coroutine()
    #code
```
