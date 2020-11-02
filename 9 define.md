## define

定义宏用define去定义

在预编译阶段进行替换。

#### 1.不带参宏

`#define PI 3.14`

注意：不要加分号

作用范围：从定义的地方到**本文件末尾**

如果想在**中间终止宏的定义范围，`#undef PI`可终止PI的作用**。

#### 2.带参宏

```c
#define S(a,b) a*b 
```

注意带参宏的形参 a和b 没有类型名
