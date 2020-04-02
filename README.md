# bounds_checking_function

#### 介绍
- 遵循C11 Annex K (Bounds-checking interfaces)的标准，选取并实现了常见的内存/字符串操作类的函数，如memcpy_s、strcpy_s等函数。
- 未来将分析C11 Annex K中的其他标准函数，如果有必要，将在该组织中实现。
- 处理边界检查函数的版本发布、更新以及维护。


####构建方法

- 编译步骤

1. 调整项目的构建脚本，将src下的.c文件作为新的编译单元参加编译。

2. 在编译选项中指定头文件目录（例如：在CFLAGS中添加 -Ipath_to_include）；

3. 根据实际使用场景编译生成静态库或共享库使用。

- 编译示例：
```
gcc -o memcpy_s.o src/memcpy_s.c -Iinclude
```











 




 



