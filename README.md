# Python 从入门到放弃

## Python特点

1. Python是一门编程语言,它只是众多编程语言中的一种
2. 语法简洁、优雅、编写的程序容易阅读
3. 跨平台,可以运行在Windows、Linux以及MacOS
4. 易于学习。站在非计算机专业的角度来讲,如果把编程语言当做解决问题的工具, Python确实相较于C++、Java、JavaScript等语言要易于学习和掌握
5. 极为强大而丰富的标准库与第3三方库,比如电子邮件,比如图形GUl界面
6. Python是面向对象的语言

> Simple is better than complex.
> 简洁胜于复杂
>
> Now is better than never. Although never is often better than right now
> 做也许好过不做,但不假思索就动手还不如不做



### Python能做什么
1. 爬虫
2. 大数据与数据分析( Spark )
3. 自动化运维与自动化测试
4. Web开发: Flask、Django
5. 机器学习: Tensor Flow
6. 胶水语言:混合其他如C++、Java等来编程。能够把用其他语言制作的各种模块(尤其是C/C++ )很轻松地联结在一起





## 入门

> python 如何将a、b两个变量的值交换
> a,b=b,a

### Python的基本数据类型

1. 整数: int
2. 浮点数: float
3. 其他语言:单精度( float) , 双精度( double )
4. 其他语言: short, int, long

### Number

![image-20200815043744749](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815043744749.png)

![image-20200815043907558](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815043907558.png)

![image-20200815044029557](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815044029557.png)



#### Python 表示二进制 `0b` 开头，八进制 `0o`开头，十六进制`0x`开头

![image-20200815044447334](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815044447334.png)



![image-20200815045047958](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815045047958.png)

### bool 

![image-20200815045246628](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815045246628.png)

![image-20200815045413384](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815045413384.png)

![image-20200815045705878](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815045705878.png)

### complex

![image-20200815045816678](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815045816678.png)

### str

> 如何表示字符串?
> 单引号，双引号，三引号 

![image-20200815050003134](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815050003134.png)

![image-20200815050155431](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815050155431.png)

![image-20200815050304019](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815050304019.png)

![image-20200815050447345](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815050447345.png)

![image-20200815050601267](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815050601267.png)

#### 转义字符

> 特殊的字符
> 无法“看见”的字符
> 与语言本身语法有冲突的字符

![image-20200815050807125](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815050807125.png)

#### 字符串运算

![image-20200815051141931](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815051141931.png)


![image-20200815051525630](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815051525630.png)


![image-20200815052003488](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815052003488.png)


![image-20200815051853958](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815051853958.png)

### list

![image-20200815052206137](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815052206137.png)

![image-20200815052255095](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815052255095.png)

![image-20200815052958359](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815052958359.png)

### tuple

![image-20200815053244952](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815053244952.png)

![image-20200815053409662](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815053409662.png)

![image-20200815053601546](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815053601546.png)

> str，list，tuple 在 Python 中都属于序列

![image-20200815054103922](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815054103922.png)

![image-20200815054154364](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815054154364.png)



### set

![image-20200815054541540](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815054541540.png)

![image-20200815054722441](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815054722441.png)

![image-20200815054837494](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815054837494.png)

### dict

> dict 的 `key` 必须是不可变类型

![image-20200815055038241](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815055038241.png)

![image-20200815055423119](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815055423119.png)

![image-20200815055522661](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815055522661.png)



## 变量与运算符

### 变量

> 系统关键字不能用在变量名中，变量名字应该清晰规范

![image-20200815055951383](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815055951383.png)

> int str tuple (不可改变) 值类型，list set dict (可变) 引用类型

![image-20200815060356912](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815060356912.png)

![image-20200815060759583](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815060759583.png)

![image-20200815060953916](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815060953916.png)

![image-20200815061149933](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815061149933.png)

### 运算符

#### 算术运算符

| 运算符 | 描述                                            | 实例(以下假设变量： **a=10，b=20**)                |
| :----- | :---------------------------------------------- | :------------------------------------------------- |
| +      | 加 - 两个对象相加                               | a + b 输出结果 30                                  |
| -      | 减 - 得到负数或是一个数减去另一个数             | a - b 输出结果 -10                                 |
| *      | 乘 - 两个数相乘或是返回一个被重复若干次的字符串 | a * b 输出结果 200                                 |
| /      | 除 - x除以y                                     | b / a 输出结果 2                                   |
| %      | 取模 - 返回除法的余数                           | b % a 输出结果 0                                   |
| **     | 幂 - 返回x的y次幂                               | a**b 为10的20次方， 输出结果 100000000000000000000 |
| //     | 取整除 - 返回商的整数部分（**向下取整**）       | `>>> 9//2 4 >>> -9//2 -5`                          |

#### 比较运算符

| 运算符 | 描述                                                         | 实例                                  |
| :----- | :----------------------------------------------------------- | :------------------------------------ |
| ==     | 等于 - 比较对象是否相等                                      | (a == b) 返回 False。                 |
| !=     | 不等于 - 比较两个对象是否不相等                              | (a != b) 返回 true.                   |
| <>     | 不等于 - 比较两个对象是否不相等。**python3 已废弃。**        | (a <> b) 返回 true。这个运算符类似 != |
| >      | 大于 - 返回x是否大于y                                        | (a > b) 返回 False。                  |
| <      | 小于 - 返回x是否小于y。所有比较运算符返回1表示真，返回0表示假。这分别与特殊的变量True和False等价。 | (a < b) 返回 true。                   |
| >=     | 大于等于 - 返回x是否大于等于y。                              | (a >= b) 返回 False。                 |
| <=     | 小于等于 - 返回x是否小于等于y。                              | (a <= b) 返回 true。                  |

#### 赋值运算符

| 运算符 | 描述             | 实例                                  |
| :----- | :--------------- | :------------------------------------ |
| =      | 简单的赋值运算符 | c = a + b 将 a + b 的运算结果赋值为 c |
| +=     | 加法赋值运算符   | c += a 等效于 c = c + a               |
| -=     | 减法赋值运算符   | c -= a 等效于 c = c - a               |
| *=     | 乘法赋值运算符   | c *= a 等效于 c = c * a               |
| /=     | 除法赋值运算符   | c /= a 等效于 c = c / a               |
| %=     | 取模赋值运算符   | c %= a 等效于 c = c % a               |
| **=    | 幂赋值运算符     | c \**= a 等效于 c = c \** a           |
| //=    | 取整除赋值运算符 | c //= a 等效于 c = c // a             |

#### 位运算符

按位运算符是把数字看作二进制来进行计算的。Python中的按位运算法则如下：

下表中变量 a 为 60，b 为 13，二进制格式如下：

```
  a = 0011 1100
  b = 0000 1101
-----------------
a&b = 0000 1100
a|b = 0011 1101
a^b = 0011 0001
 ~a = 1100 0011
```

| 运算符 | 描述                                                         | 实例                                                         |
| :----- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| &      | 按位与运算符：参与运算的两个值,如果两个相应位都为1,则该位的结果为1,否则为0 | (a & b) 输出结果 12 ，二进制解释： 0000 1100                 |
| \|     | 按位或运算符：只要对应的二个二进位有一个为1时，结果位就为1。 | (a \| b) 输出结果 61 ，二进制解释： 0011 1101                |
| ^      | 按位异或运算符：当两对应的二进位相异时，结果为1              | (a ^ b) 输出结果 49 ，二进制解释： 0011 0001                 |
| ~      | 按位取反运算符：对数据的每个二进制位取反,即把1变为0,把0变为1 。**~x** 类似于 **-x-1** | (~a ) 输出结果 -61 ，二进制解释： 1100 0011，在一个有符号二进制数的补码形式。 |
| <<     | 左移动运算符：运算数的各二进位全部左移若干位，由 **<<** 右边的数字指定了移动的位数，高位丢弃，低位补0。 | a << 2 输出结果 240 ，二进制解释： 1111 0000                 |
| >>     | 右移动运算符：把">>"左边的运算数的各二进位全部右移若干位，**>>** 右边的数字指定了移动的位数 | a >> 2 输出结果 15 ，二进制解释： 0000 1111                  |

#### 逻辑运算符

| 运算符 | 逻辑表达式 | 描述                                                         | 实例(变量 a 为 10, b为 20) |
| :----- | :--------- | :----------------------------------------------------------- | :------------------------- |
| and    | x and y    | 布尔"与" - 如果 x 为 False，x and y 返回 False，否则它返回 y 的计算值。 | (a and b) 返回 20。        |
| or     | x or y     | 布尔"或" - 如果 x 是非 0，它返回 x 的值，否则它返回 y 的计算值。 | (a or b) 返回 10。         |
| not    | not x      | 布尔"非" - 如果 x 为 True，返回 False 。如果 x 为 False，它返回 True。 | not(a and b) 返回 False    |

#### 成员运算符

| 运算符 | 描述                                                    | 实例                                              |
| :----- | :------------------------------------------------------ | :------------------------------------------------ |
| in     | 如果在指定的序列中找到值返回 True，否则返回 False。     | x 在 y 序列中 , 如果 x 在 y 序列中返回 True。     |
| not in | 如果在指定的序列中没有找到值返回 True，否则返回 False。 | x 不在 y 序列中 , 如果 x 不在 y 序列中返回 True。 |

#### 身份运算符



| 运算符 | 描述(身份运算符用于比较两个对象的存储单元)  | 实例( id() 函数用于获取对象内存地址 ) |
| :----- | :------------------------------------------ | :----------------------------------------------------------- |
| is     | is 是判断两个标识符是不是引用自一个对象     | **x is y**, 类似 **id(x) == id(y)** , 如果引用的是同一个对象则返回 True，否则返回 False |
| is not | is not 是判断两个标识符是不是引用自不同对象 | **x is not y** ， 类似 **id(a) != id(b)**。如果引用的不是同一个对象则返回结果 True，否则返回 False。 |

![image-20200815061514871](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815061514871.png)

![image-20200815062807850](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815062807850.png)

![image-20200815062827232](https://gitee.com/Mireal/PictureBed/raw/master/img/image-20200815062827232.png)

![image-20200815062910639](C:\Users\mrmir\AppData\Roaming\Typora\typora-user-images\image-20200815062910639.png)