FSW-Temperature-Field-Compressor
================================

综合论文训练，搅拌摩擦焊工件温度场仿真数据压缩器

编译和运行举例
--------------

```
$ make all
$ cd bin
$ ./ftfc -h # 获得帮助
$ make clean # 清除编译生成的文件
```

版本历史
--------

### 0.1.0

2020-02-10

1.	支持短参数`-hvi`。

2.	压缩Tecplot导出的单帧温度场数据。

### 0.2.0

2020-03-27

1.	压缩多帧温度场数据，输入格式是(x, y, z, T)，每个时间步的存储成单个文件。

2.	新增了用户定义文件`user_defined.hpp`，详见注释。

3.	新增了短参数`-c`。

4.	移除了短参数`-i`。

### 0.3.0

2020-03-29

1.	根据搅拌摩擦焊存在准稳态过程，改良压缩器。
