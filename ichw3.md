在数据中任选一个数, 对其他所有数据作异或运算, 对于任意成对出现的数, 在对所有其它数据进行异或运算后, 应该输出1个真值, 则未输出1的数为单个的数.


在101个数中任选一个数, 对其他所有数进行异或运算，如果没有重复出现，则异或运算结果应该均为0，因此出现1的那个数为两个重复的数。


高速缓存存储器主要由以下的三个部件组成：
1. Cache存储体：存放由主存调入的指令与数据块。

2. 地址转换部件：建立目录表以实现主存地址到缓存地址的转换。

3. 替换部件：在缓存已满时按一定策略进行数据块替换，并修改地址转换部件。

工作原理：高速缓冲存储器通常由高速存储器、联想存储器、替换逻辑电路和相应的控制线路组成。中央处理器对主储存器的地址进行划分，高速存储器具有与主存储器相同的划分方法，但是行数比主存储器少。
联想存储器用于地址联想，有与高速存储器相同行数和列数的存储单元。当主存储器某一列某一行存储单元组调入高速存储器同一列某一空着的存储单元组时，与联想存储器对应位置的存储单元就记录调入的存储单元组在主存储器中的行号。
