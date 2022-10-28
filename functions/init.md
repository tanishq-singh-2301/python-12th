# _**Functions**_

[**Lecture**](https://www.youtube.com/watch?v=xFWRG8bXZUA)

### _**1. Types of functions**_

1. **build in function**, like `input()`, `len()`, `int()`.
2. **user defined**
3. **module based**, like `sqrt()`, `plot()`.
    ```py
    import math
    ```

### _**2. Syntax**_

-   ### _**Example 1**_

    ```py
    def sayHello(name):
    	print("Hello ", name)

    # calling fun
    sayHello("Kaju")
    ```

-   ### _**Example 2**_

    ##### _**Defining**_

    -   here x, y are `parameters`, or
    -   `formal parameters` / `formal arguements`

    -   ```py
        def add(x, y):
        return x + y
        ```

    ##### _**Calling**_

    -   but here x, y are `arguements`, or
    -   `actual parameters` / `actual arguements`

    -   ```py
         print(add(3, 4)) # 7
        ```

### _**3. Default Values**_

```py
# void function
def myFun(name="kaju", age=17):
	print(name, age)

myFun("tanvii", 18)
myFun(age=19, name="aashi")
myFun(name="aashi", 18) # this is wrong
```

### _**4. Retrning Multiple Values**_

```py
def fun(a, b, c):
	return a*b, b*c, c*a # tuple

myTuple = fun(1, 2, 3)
t1, t2, t3 = fun(1, 2, 3)
```

_**Note**_

```py
def fun():
	print("adsf")

print(fun()) # none
```
