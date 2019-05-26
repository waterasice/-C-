# 《C和指针》简介

本书提供与C语言编程相关的全面资源和深入讨论。本书通过对指针的基础知识和高级特性的探讨，帮助程序员把指针的强大功能融入到自己的程序中去。

全书共18章，覆盖了数据、语句、操作符和表达式、指针、函数、数组、字符串、结构和联合等几乎所有重要的C编程话题。书中给出了很多编程技巧和提示，每章后面有针对性很强的练习，附录部分则给出了部分练习的解答。

本书适合C语言初学者和初级C程序员阅读，也可作为计算机专业学生学习C语言的参考。

# 丛书信息

C和C++经典著作 (共5册), 这套丛书还有 《C专家编程》,《C陷阱与缺陷》,《C++沉思录》,《C++Templates中文版》

# 技巧与提示

## 快速上手

### 警告

- 在 scanf 函数的标量参数前未添加 & 字符
- 机械地把 printf 函数的格式代码照搬于 scanf 函数
- 在应该使用 && 操作符的地方误用了 & 操作符
- 误用 = 操作符而不是 == 操作符来测试相等性

### 提示

- 使用 #include 指令避免重复声明
- 使用 #define 指令给常量值取名
- 在 #include 文件中放置函数原型
- 在使用下标前先检查它们的值
- 在 while 或 if 表达式中蕴含赋值操作
- 如何编写一个空循环体（使用;）
- 始终要进行检查，确保数组不越界（编译器不会报错，建议使用小工具 cppcheck）