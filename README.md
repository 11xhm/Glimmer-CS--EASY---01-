### 第一个程序

1. Q:高级计算机语言与低级计算机语言，各有什么优劣，你更喜欢哪一类计算机语言？

     A:高级语言通常使用接近自然语言的语法，代码易于理解，在库的帮助下，开发效率更高。但需要编译才能运行，略显麻烦。低级语言难学难用，但某些领域内作用显著。我个人而言更喜欢高级语言。

2. Q:尝试解读`hello.c`中每一行的内容。

   A:，这里的意思是将名为 “stdio.h” 的头文件包含到当前的 C 语言源文件中。这个头文件通常包含了输入输出函数（如 printf、scanf 等）的声明。

3. Q:删去该程序的哪一行不会影响运行结果

   A: return 0

4. Q: int类型是计算机存储什么元素的方式？为什么main函数要使用int进行声明/定义？

   A:`int`类型是用于存储整数的一种数据类型。C 和 C++ 等编程语言中，规定`main`函数的返回值类型为`int`是一种广泛接受的标准和约定。这样做使得不同的编译器和开发环境都有一个统一的规范来遵循，便于程序的可移植性和互操作性。（这个我是真不太知道）![f2df90882f9eb011d483d977019b47d5](C:\Users\13956\Desktop\f2df90882f9eb011d483d977019b47d5.png)

### 基础语法运用

*修改后：*

\#include <stdio.h>

int main() {

  int code;

  printf("Show me your code,please.");

  while(1){

​    scanf("%d",&code);

​    if(code >= 100000 && code <= 999999)

​    {

​    printf("I am super hacker!");

​    return 0;

​    }

​    else {

​      printf("Fake code!");

​       }

  

}

  return 0;

}

### 课后题

![13fb8d0155c9dd5e4a9afa8a8bcf1d73](C:\Users\13956\Desktop\13fb8d0155c9dd5e4a9afa8a8bcf1d73.png)