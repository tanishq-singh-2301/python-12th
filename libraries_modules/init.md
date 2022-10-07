# _**Libraries and Modules**_

[**Lecture**](https://www.youtube.com/watch?v=5CwPxhieYMU)

### _**1. Some Modules**_

-   math.py
-   cmath.py
-   random.py
-   urlib.py
-   statistics.py

### _**Using a module**_

-   ```py
    import math
    print(math.sqrt(25)) # 5
    ```

-   ```py
    from math import sqrt, pow
    print(sqrt(36)) # 6
    ```

### **Custom Module** [**Demo**](/libraries_modules/module)

-   ```py
    # name.py

    def sayName(name="kaju"):
        print(name)
    ```

-   ```py
    # main.py

    import name # or
    from name import sayName

    name.sayName();
    sayName();

    # When you'll run this main.py, '__pycache_' will get generated
    ```

### **Custom Package** [**Demo**](/libraries_modules/package)

-   ```py
    # sound_custom/load.py
    def fun_load(name):
        return name
    ```

-   ```py
    # sound_custom/play.py
    def fun_play():
        return True
    ```

-   ```py
    # sound_custom/pause.py
    def fun_pause():
        return False
    ```

-   ```py
    # sound_custom/__init__.py, 'just create this file, no need to add anything idk why exactly'
    ```

-   ```py
    from sound_custom import load, pause, play

    print(load.fun_load("Kaju.mp3"))
    print(play.fun_play())
    print(pause.fun_pause())
    # When you'll run this main.py, '__pycache_' will get generated
    ```
