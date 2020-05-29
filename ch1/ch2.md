## 基本逻辑门

基本逻辑门包括

- 与门

实现与的运算电路。若输入变量逻辑为A和B，则与门的输出结果Y可表示为

Y=A^B

只有A和B 两端都是高电平，输出才是高电平

- 或门

Y=A V B

只要A和B 两端有一个高电平的输出就是高电平

- 非门

Y=！A

若输入端为高端平输出端就是低电平，反之亦然

- 异或门

若输入相同是，输出为0，输出不同时输出为1

> 异或门电路是实现二进制加法的逻辑门电路，也叫半加器他是ALU部件的基本逻辑电路

- 与非门

Y=!(A^B)

先进行与运算在进行或运算，（先经过与门在经过非门）电路两端的状态很好判断这里就略了

- 或非门

Y=!(A V B)

先进行或运算在进行非运算（先经过或门在经过非门）

- 三态门

`三态门常用于为处理器的总线传输，三态门除了具有一般门电路的高低电平外，还具有处处阻抗的第三种状态，称为高阻态有称禁止态，实际是由使能端EN来控制`

![](http://m.qpic.cn/psc?/V13PUOHK2RFsMP/U3..NSiujzLMR7a*2QgXbRXQOUrVgx*4tYDtzKy7s6aP8YLxYOprOkHSY6yahemoB0UFZATMgvK1SBlaB9IgKg!!/b&bo=zgIaAgAAAAADB*Y!&rf=viewer_4)



## 链接

上一章：[第一章由于过于简单我把它总结成了大杂烩](https://github.com/youmingsama/Microcomputer-principle-and-interface-technology/blob/master/ch1/ch1.md)

下一章：[ASCLL](https://github.com/youmingsama/Microcomputer-principle-and-interface-technology/blob/master/ch1/ch3.md)

目录：[目录](https://github.com/youmingsama/Microcomputer-principle-and-interface-technology/blob/master/catalog/catalog.md)