##### 微型计算机系统简介

- 微型计算机的组成部分

微处理器、存储器、输入输出、总线。

- 计算机中的数制

数码，基数，位权

eg 二进制

数码：0，1

基数：2

位权：2^i

数制之间的转换

- 略

##### 二进制的算术运算

数值宽度

- 字节
- 字
- 双字
- 四字

- 加减乘除运算

太简单略

##### 乘法在计算机中的运算机制

![](http://m.qpic.cn/psc?/V13PUOHK2RFsMP/U3..NSiujzLMR7a*2QgXbVD9TMldJcCFfHFNlTJT9gpQZbnZPBPcxdwT9kD7FZ1yw3bbkqFTDQ8NZ8jy7cIQdA!!/b&bo=7AL2AewC9gEDCSw!&rf=viewer_4)

##### 无符号数的表示范围

8 位的无符号二进制数

00000000~11111111 即 0~2^8

n 位无符号二进制数

0~2^n

##### 算术运算溢出

> 若两个 8 位的二进制数相加，最高位进位超出的 8 位二进制的取值范围，则最高位会被丢弃，这种情况称为溢出

有进位或者借位都可能导致溢出

**CF 位**：若最高位出现进位或者借位 CF 位置为 1

乘法一般不会产生溢出

除法当除数较小时可能产生溢出

##### 补码运算规则

![](http://m.qpic.cn/psc?/V13PUOHK2RFsMP/4pNOqgOvBLvj4yTC9qc55T.bNkxUc0jOh1a2QMwfNuhGRHYMf53WQjNd1OvYhIk5ntd5XBH1tyWyfL7zRmgaLG8jW*cnPVqAphzgT3G6*nw!/b&bo=yAL7AcgC.wEDKQw!&rf=viewer_4)

##### 带符号数的溢出

![](http://m.qpic.cn/psc?/V13PUOHK2RFsMP/4pNOqgOvBLvj4yTC9qc55TLwKINTFJOEvzT..2n8xX4wOS3jYgL5wAzJ6YKvh4MjWjdXWQuGhSU77GDMCZwIY*eafju4c8cFPrAq99tM0fU!/b&bo=ywKYAcsCmAEDGTw!&rf=viewer_4)

##### 判断带符号数的溢出

![](http://m.qpic.cn/psc?/V13PUOHK2RFsMP/4pNOqgOvBLvj4yTC9qc55T65mnYkXr3B9QojmGHTMy6RT*.GMx3hKnggk3PQX2o5.o0r7SyL76qZ4VVAeqj2h4llJEJIlRfTnO6Cvm2ksfI!/b&bo=sgLMAbICzAEDKQw!&rf=viewer_4)

ps 微型计算机中，如果运算结构溢出标志寄存器中的 OF 为将会置为 1 啦

##### 带符号数的范围

![](http://m.qpic.cn/psc?/V13PUOHK2RFsMP/4pNOqgOvBLvj4yTC9qc55dGwY5ZqsI2RyXeXJqj7o6VNVyNSTuzV1kl1yH6cKVVOVmrxo9C9KhtAI7EBNcx9Tc0dsKDvki*zF*WCvEsRVGo!/b&bo=DAKuAQwCrgEDGTw!&rf=viewer_4)

##### 基本逻辑运算与常用逻辑部件

计算机逻辑指的是输入与输出的一种因果关系，用 0 和 1 来表示，变量取值也只有两个 0 和 1 在逻辑代数中有与或非三种逻辑运算
