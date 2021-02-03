# JDK目录
| 目录 | 说明 |
| -- | -- |
| bin | 存放JDK的工具命令。javac和java就在此目录 |
| conf | 存放JDK的配置文件 |
| include | 存放平台特定头文件 |
| jmods | 存放JDK的各个模块 |
| legal | 存放JDK各模块的授权文档 |
| lib | 存放JDK的一些补充JAR包 |

# DOS命令
| 命令 | 作用 |
| -- | -- |
|`d:`| 切换盘符 |
| `dir` | 查看当前路径下的内容 |
| `cd foldname` | 进入当前路径中的`foldname`文件夹 |
| `cd fold1\fold2\...` | 进入多级目录 |
| `cd \` | 回退到盘符目录 |
| `cd ..` | 回退到上一级目录 |

# 数据类型
| 数据类型 | 关键字 | 内存占用 | 取值范围 |
| -- | -- | -- | -- |
| 整数 | `byte` | 1 | -128 ~ 127 |
| 整数 | `short` | 2 | -32768 ~ 32767 |
| 整数 | `int` | 4 | $-2^{31}$ ~ $2^{31}-1$ |
| 整数 | `long` | 8 | $-2^{63}$ ~ $2^{63}-1$ |
| 浮点数 | `float` | 4 | 负数：$-3.402823 \times 10^{38}$ ~ $-1.401298 \times 10^{-45}$ <br> 正数：$1.401298 \times 10^{-45}$ ~ $3.402823 \times 10^{38}$ |
|  | `double` | 8 | 负数：$-1.797693 \times 10^{308}$ ~ $-4.900000 \times 10^{-324}$ <br> 正数：$4.900000 \times 10^{-324}$ ~ $1.797693 \times 10^{308}$ |
| 字符 | `char` | 2 | 0 ~ 65535 |
| 布尔 | `boolean` | 1 | true, false |

定义变量并赋值
```java
// type para_name = para_value
byte b = 10;
short s = 5;
int i = 3;
long l_num = 1000000L;
float f = 3.14115F;
double d = 3.1415;
char c = 'hello';
boolean b = true;
```
默认的的整数是`int`，默认的小数是`double`，所以在表示`long`类型的时整数是需要加`L`后缀，表示`float`类型需要加`F`后缀。

自动类型转换
```java
double d = 2;
// d = 2.0
```
强制类型转换
```java
int k = (int)8.8
// k = 8
```