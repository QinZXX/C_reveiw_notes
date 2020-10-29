## C语言编译过程

简单介绍：

预处理，编译，汇编，链接。

```bash
gcc -E hello.c -o hello.i  1.预处理
gcc -S hello.i -o hello.s  2.编译
gcc -c hello.s -o hello.o  3.汇编
gcc hello.o -o hello_elf   4.链接
```

#### 1.预处理：

将源文件中的 头文件展开，宏展开。

生成的是`.i` 文件

#### 2.编译：

将预处理后的`.i`文件生成`.s`汇编文件

#### 3.汇编

将`.s`汇编文件生成`.o`目标文件

#### 4.链接:

将`.o`文件链接成目标文件

