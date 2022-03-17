# 正文
1. 声明和定义的区别
---
## 1.声明和定义的区别
* 声明是用来告诉编译器变量的名称和类型，而不分配内存
* 定义是为了给变量分配内存，可以为变量赋初值

```CPP
extern int var; // 声明
extern int ble =10; // 定义
typedef int INT; // 声明
struct Node; // 声明
```
* 全局变量或静态变量初始值为0，局部变量初始化为随机值
* 在 C/C++ 中，变量的声明和定义区别并不大，定义和声明往往是同时发生

```CPP
int value ; //声明 + 定义

struct Node { //声明 + 定义
    int left;
    int right;
}; 
```