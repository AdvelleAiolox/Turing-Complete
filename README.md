# Turing-Complete
Turing Complete solution

图灵完备，从与非门开始构建CPU

[Basic Logic 基本逻辑门](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Basic-Logic)

[Arithmetic 运算器](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Arithmetic)

[Memory 存储器](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Memory)

[CPU Architecture CPU架构](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#CPU-Architecture)

[Programming 编程](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Programming)

[CPU Architecture 2 CPU架构2](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#CPU-Architecture-2)

[Functions 函数](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/README.md#Functions)

## Basic Logic

**Crude Awakening**

通路

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/Crude%20Awakening.JPG)

**NAND Gate**

与非门

Not AND，不全是即非

点左侧输入改变输入内容，观察输出并填写

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/NAND%20Gate.JPG)

**NOT Gate**

非门

真即假，假即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/NOT%20Gate.JPG)

**AND Gate**

与门

全是即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/AND%20Gate.JPG)

**NOR Gate**

或非门

Not OR，全非即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/NOR%20Gate.JPG)

**OR Gate**

或门

一真即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/OR%20Gate.JPG)

**Always On**

常通

常闭同理

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/Always%20On.JPG)

**Second Tick**

仅有输入1为真时为真

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

同或门

相同即真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Basic_Logic/XNOR%20Gate.JPG)


## Arithmetic

**Binary Racer**

二进制计算

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

有符号二进制计算

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

**Logic Engine**

逻辑引擎

有三个输入，第一个输入转化为二进制后由最低两位控制逻辑操作的选项，后两个输入代表输入1和输入2

当逻辑控制符为00时，输出输入1与输入2取或之后的答案

当逻辑控制符为01时，输出输入1与输入2取与非之后的答案

当逻辑控制符为10时，输出输入1与输入2取或非之后的答案

当逻辑控制符为11时，输出输入1与输入2取与之后的答案

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Arithmetic/Logic%20Engine.JPG)

上中下分为逻辑选择部分，取或部分，取与部分

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

奇偶判断器

在奇数轮为假，在偶数轮为真

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Odd%20Ticks.JPG)

注意上方延迟器有反转，输入为右端，输出为左端

**Bit Switch**

同异或

但是只有两个非门和两个开关

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

与门列用于选择存储器，左侧开关列为对应存储器是否输出的触发，右侧开关列为对应存储器是否保存的触发

**Counter**

计数器

有一个选择位及一个输入值，选择位为假，代表计数器加一，选择位为真，用输入值覆盖计数器的值

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Memory/Counter.JPG)

## CPU Architecture

**Arithmetic Engine**

算数引擎

在之前的逻辑引擎上加入加和减操作

有三个输入，第一个输入转化为二进制后由最低三位控制操作的选项，后两个输入代表输入1和输入2

当操作控制符为000时，输出输入1与输入2取或之后的答案

当操作控制符为001时，输出输入1与输入2取与非之后的答案

当操作控制符为010时，输出输入1与输入2取或非之后的答案

当操作控制符为011时，输出输入1与输入2取与之后的答案

当操作控制符为100时，输出输入1与输入2加运算之后的答案

当操作控制符为101时，输出输入1与输入2减运算（输入1减去输入2）之后的答案

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Arithmetic%20Engine.JPG)

上部进行操作选择，下部进行操作运算

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Arithmetic%20Engine%20s.JPG)

操作选择简化后版本

**Registers**

寄存器

这里原本应该有一个输入，但是我因为做过后面关卡所以输入是一个程序，但电路方面是一样的

一个字节八位，从低位起1，2，3位组合代表选择存储的寄存器地址，4，5，6位代表数据来源的寄存器地址

000代表寄存器0，001代表寄存器1，010代表寄存器2，011代表寄存器3，100代表寄存器4，101代表寄存器5，110在来源代表输入，在存储位置代表输出

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Registers.JPG)

**Component Factory**

元件工厂

本关卡不是一个关卡，只是可以开放自定义元件功能

元件按空格可以旋转，在一个方格块中只能有一个输入或者输出，否则会出现错误

**Instruction Decoder**

指令解码器

在有限的范围内绘制指令解码器

输入字节的最高两位代表操作种类，其中00代表即时操作，01代表计算，10代表复制，11代表判断，四个输出代表选中的操作

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Instruction%20Decoder.JPG)

**Calculations**

计算模块

在寄存器的基础上添加计算模块

这里原本应该有一个输入，但是我因为做过后面关卡所以输入是一个程序，但电路方面是一样的

可直接利用之前的指令解码器（DEC）

此关卡只考虑复制和计算操作，复制操作同寄存器关卡，计算操作时，由从低位起1，2，3位代表操作类型，可直接利用之前的算数引擎（ALU）

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Calculations.JPG)

需注意短路问题，可添加开关控制

**Conditions**

条件模块

在极其有限的范围内绘制一个条件判断模块

有两个输入，输入1的二进制最低三位代表判断的条件，其中000为常闭，001判断是否等于0，010判断是否小于0，011判断是否小于等于0，100为常通，101判断是否不等于0，110判断是否大于等于0，111判断是否大于0，输出代表判断结论真或假

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Conditions.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Conditions%2001.JPG)

电路解释

红色+-圈用于判断输入2是否小于0，蓝色0圈用于判断除了负位，输入2是否等于0，红色0圈用于判断输入2是否等于0

**Program**

程序

将输入改为由程序控制，程序由一个计数器控制，每次读取一字节

只需要给程序窗口连接计数器，并将计数器设置为1

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Program.JPG)

**Immediate Values**

即时值

在添加了计算模块的寄存器上再次添加即时值模块

可直接利用之前的指令解码器（DEC）

在即时操作时，直接将输入的数值存入寄存器0

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Immediate%20Values.JPG)

也需注意短路问题，可添加开关控制

**Turing Complete**

图灵完备机

在添加了计算模块和即时值模块的寄存器上再次添加条件模块

可直接利用之前的指令解码器（DEC）和条件模块（COND）

在条件操作时，比较寄存器3中的值与0的大小，如果为真，将寄存器0中的值赋予给计数器，使得程序可以跳转到值对应的指令

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture/Turing%20Complete.JPG)

也需注意短路问题，可添加开关控制

## Programming

**Add 5**

加五

更改程序框中的数据，达到给输入的数加5并输出的效果

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/ADD%205.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/ADD%205%201.JPG)

5，00000101，代表即时操作，将数值直接存储到寄存器0中

129，100000001，代表复制操作，将寄存器0中的数据复制到寄存器1中

178，10110010，代表复制操作，将输入中的数值存储到寄存器2中

68，01000100，代表运算，加操作，将寄存器1和寄存器2的数值相加，将答案存储到寄存器3中

158，10011110，代表复制操作，将寄存器3中的数值输出到输出中

**Calibrating Laser Cannons**

校准激光炮

实际为计算2π乘输入，并且π取3，所以实际为计算输入乘6，也可以理解为六个输入数值累加

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Calibrating%20Laser%20Cannons.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Calibrating%20Laser%20Cannons%201.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Calibrating%20Laser%20Cannons%202.JPG)

此关卡可以解锁操作命名，可以将对应的二进制操作用更容易理解的方式命名，具体操作含义参考之前的定义

**Spacial Invasion**

宇宙入侵

有一张图，里面有一堆可以动的星际老鼠，你可以操控一个机器人来杀掉这些星际老鼠，激光炮发射后如果还没消失就不能发射第二次

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Spacial%20Invasion%204.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Spacial%20Invasion%203.JPG)

机器人操作指令如图

我重点关注三个，前进（1），等待（3），发射激光炮（5）

实际操作找到最简单的方法是先发射机关炮破坏墙壁，然后前进，知道星际老鼠那行之前，然后开始判断机器人面前是否有老鼠，如果面前有老鼠（33，判断不等于0即可），则发射激光炮，如果没有老鼠（0），则等待（因为老鼠会自己动）

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Spacial%20Invasion.JPG)

这是依据操作暴力执行的程序（程序太长，不放了，一直都是同一个语句）

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Spacial%20Invasion%201.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Spacial%20Invasion%202.JPG)

这个是改进之后的程序，需要程序本身读取输入（机器人面前的物品数据（老鼠33，空白0）），再进行发射或者等待操作

**Storage Cracker**

存储破解器

猜密码，猜高了会给你一个输出1

但是这关没有惩罚，我偷懒暴力从0开始+1输出，反正到了答案会自动停止执行 ：P

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Storage%20Cracker.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Storage%20Cracker.JPG)

**Masking Time**

掩蔽时间

外星人一周只有四天，周零，周一，周二，周三，你要依据输入来看这天是周几

实际就是输入与4取模

但是这关有操作次数限制，不能超过八次，如果用减操作直到小于4是不行的，所以我最后选择用输入与3（二进制11）取与操作保留输入数据二进制的最后两位

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Masking%20Time.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/Masking%20Time%201.JPG)

**The Maze**

迷宫

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/The%20Maze.JPG)

走迷宫，空白是0，墙是1，门是3，金币是8

我的策略是，先判断前面是不是门（3）(输入减3是否等于0)，如果是门，进行互动操作（4），进入门

如果不是门，再判断是不是墙（1）（输入减1是否等于0），如果是墙，则右转（2）

如果也不是墙，先前进一步（1），然后立刻左转（0）

如此重复直到进入门

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/The%20Maze%201.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/Programming/The%20Maze%202.JPG)

具体代码如上，判断后需要使用跳转（改变计数器数据）

## CPU Architecture 2

**XOR**

异或

本关卡通过编写程序达成

输入两个数，输出两个输入数值进行异或操作后的结果

在不能改变电路的情况下，考虑使用其他方式获得异或运算值，异或运算值也等于或运算的值减去与运算的值

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/XOR.JPG)

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/XOR%201.JPG)

**Byte Constant**

字节固定值

直接用电源激活8位转换器对应的位

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/Byte%20Constant.JPG)

其他数值只需要改变用电源激活的位置即可

**Byte XOR**

字节异或

输入两个字节，对各个位进行异或运算

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/Byte%20XOR.JPG)

**Equality**

等于

输入两个字节，对各个位进行同或运算，若所有位均为真则代表相等，否则则为不相等

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/Equality.JPG)

**Unsigned Less**

无符号小于

输入两个无符号字节（最高位代表+128），若输入1小于输入2，为真，否则为假

首先判断最高位的值，如果输入1最高位为0，输入2最高位为1，直接输出真

否则，看最高位的值是否相同，不相同为假

若相同时，对输入1进行取负操作（无符号也可取负，只是数值有问题，但不影响结论），将取负后的输入1与未取负的输入2相加，如果等于零，为假，否则，观察答案的最高位（第八位），若此位为假，或者进位符为真，则为真，否则为假

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/Unsigned%20Less.JPG)

**Unsigned Less**

有符号小于

输入两个有符号字节（最高位代表-128），若输入1小于输入2，为真，否则为假

首先判断最高位的值，如果输入1最高位为1，输入2最高位为0，直接输出真

否则，看最高位的值是否相同，不相同为假

若相同时，对输入1进行取负操作，将取负后的输入1与未取负的输入2相加，如果等于零，为假，否则，观察答案的最高位（第八位），若此位为假，或者进位符为真，则为真，否则为假

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/Signed%20Less.JPG)

**Wide Instructions**

宽指令

每轮都输入一个数，但在奇数轮时存储输入，在偶数轮时输出存储的数据和输入的数据

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/Wide%20Instructions.JPG)

用轮数与1进行与操作，若不等于0为奇数轮，进行存储，否则为偶数轮，进行输出

**Conditionals**

添加判断语句

![image](https://github.com/AdvelleAiolox/Turing-Complete/blob/main/Photos/CPU_Architecture_2/Conditionals.JPG)

## Functions

**Hex Racer**

二进制转十六进制计算

你有八个二进制位，并可以切换每个位的01值

系统会给出随机一个十六进制数，你需要切换对应位的01值使得二进制所表达的数值与之前给定的随机数一致

十六进制中0-1与十进制相同

大于等于10的数用字母表示

10=A

11=B

12=C

13=D

14=E

15=F

二进制中最高四位代表十六进制中最高的一位，二进制中最低四位代表十六进制中最低的一位

**Shift**

移位

