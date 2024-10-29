# Turing-Complete
Turing Complete solution

图灵完备，从NADA开始构建CPU

[基本逻辑门](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#basic-logic)

[运算器](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Arithmetic)


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
