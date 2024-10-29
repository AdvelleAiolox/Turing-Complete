# Turing-Complete
Turing Complete solution

图灵完备，从NAND开始构建CPU

[Basic Logic 基本逻辑门](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Basic-Logic)

[Arithmetic 运算器](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Arithmetic)

[Memory 存储器](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Memory)

## Basic Logic

**Crude Awakening**

通路

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/Crude%20Awakening.JPG)

**NAND Gate**

谢费尔竖线，Not AND，不全是即非

点左侧输入改变输入内容，观察输出并填写

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/NAND%20Gate.JPG)

**NOT Gate**

非门，真即假，假即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/NOT%20Gate.JPG)

**AND Gate**

与门，全是即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/AND%20Gate.JPG)

**NOR Gate**

或非门，Not OR，全非即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/NOR%20Gate.JPG)

**OR Gate**

或门，一真即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/OR%20Gate.JPG)

**Always On**

常通

常闭同理

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/Always%20On.JPG)

**Second Tick**

仅有输入1时为真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/Second%20Tick.JPG)

**XOR Gate**

异或门

两者不同为真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/XOR%20Gate.JPG)

**Bigger OR Gate**

三个输入的或门

一真即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/Bigger%20OR%20Gate.JPG)

**Bigger AND Gate**

三个输入的与门

一假即假

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/Bigger%20AND%20Gate.JPG)

**XOR Gate**

同或门，相同即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/XNOR%20Gate.JPG)


## Arithmetic

**Binary Racer**

你有八个二进制位，并可以切换每个位的01值

系统会给出随机一个数，你需要切换对应位的01值使得二进制所表达的数值与之前给定的随机数一致


**Double Trouble**

大于等于两个真即为真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Double%20Trouble.JPG)


**Odd Number of Signals**

奇数真为真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Odd%20Number%20of%20Signals.JPG)

**Counting Signals**

计数器

统计输入信号的为真的数量

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Counting%20Signals.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Counting%20Signals_124.JPG)

电路解释

红色圈1判断是否为奇数，激活1项

红色圈4判断是否为4，激活4项

蓝色圈2判断是否大于等于2且不为4，激活2项

**Half Adder**

单位加数器

SUM输出此位答案，CAR输出是否进位

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Half%20Adder.JPG)

**Double the Number**

八位翻倍器

不考虑溢出，对输入数据进行乘二操作

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Double%20the%20Number.JPG)

**Full Adder**

三输入单位加数器

SUM输出此位答案，CAR输出是否进位

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Full%20Adder.JPG)

**Byte OR**

字节或

输入两个字节，对各个位进行或运算

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Byte%20OR.JPG)

**Byte NOT**

字节非

输入一个字节，对各个位进行非运算

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Byte%20NOT.JPG)

**Adding Bytes**

字节加数器

输入一个进位符和两个字节，对其进行加法运算，若有进位溢出，则输出进位符为真，否则为假

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Adding%20Bytes.JPG)

**Negative Numbers**

你有八个二进制位，并可以切换每个位的01值，但这次最高位不代表128而是代表-128

系统会给出随机一个数，你需要切换对应位的01值使得二进制所表达的数值与之前给定的随机数一致


**Signed Negator**

有符号数取负

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Signed%20Negator.JPG)

**1 Bit Decoder**

单位解码器

输入假，选择输出1，输入真，选择输出2

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/1%20Bit%20Decoder.JPG)

**3 Bit Decoder**

三位解码器

以三位二进制数来看输入，选择对应的输出

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/3%20Bit%20Decoder.JPG)

## Memory

**Circular Dependency**

循环

需要用两个及以上的元件构成循环电路

任意两个元件首尾相连并构成环即可

**Delayed Lines**

延迟

延迟两次之后依据输入顺序输出

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Delayed%20Lines.JPG)

**Odd Ticks**

奇偶计数器

在奇数轮为假，在偶数轮为真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Odd%20Ticks.JPG)

注意上方延迟器有反转，输入为右端，输出为左端

**Bit Switch**

同异或，但是只有两个非门和两个开关

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Bit%20Switch.JPG)

**Bit Inverter**

位反转器

输入1为需做反转的数，输入2为是否需要反转

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Bit%20Inverter.JPG)

**Input Selector**

输入选择器

选择位为假代表选择输出输入1，选择位为真代表选择输出输入位2

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Input%20Selector.JPG)

**The Bus**

汇流

有两个选择位，及两个输入，第一个选择位代表选择的数据来自哪个输入，假代表输入1，真代表输入2

第二个选择位代表数据以哪个输出口输出，假代表选择输出1，真代表选择输出2

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/The%20Bus.JPG)

**Saving Gracefully**

单位存储器

有一个选择位及一个单位输入，若选择位为假，不保存输入数据，若选择位为真，保存输入数据

输出始终为存储器内数据

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Saving%20Gracefully.JPG)

**Saving Bytes**

字节存储器

有一个选择位及一个字节输入，若选择位为假，不保存输入数据，若选择位为真，保存输入数据

输出始终为存储器内数据

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Saving%20Bytes.JPG)

**Little Box**

存储器选择

有四个选择位以及一个输入值，选择位分别代表是否要输出，是否要保存，后两位表示存储器的选择，第三位代表存储器编号第一位A或B，第四位代表存储器编号第二位0或1

本题使用空间极其有限

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Little%20Box.JPG)

**Counter**

计数器

有一个选择位及一个输入值，选择位为假，代表计数器加一，选择位为真，用输入值覆盖计数器的值

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Counter.JPG)


