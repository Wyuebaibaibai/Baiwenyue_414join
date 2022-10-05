# Baiwenyue_414join
大家好，我叫**白文悦**，来自**数技1班**  
我如果加入414后想要***加强自己PS技能的学习，然后还想多欣赏一下数技专业的各个方面的作品***  
2.1  
我从班里另一个同学处获得了此代码，我已经理解了其工作原理  
方法叫做“comparefloat”就是'比较float大小'，float是浮点数。

需要输入一个命名为in的数组，数组就是高中学的数列，有顺序，从0号一直到n号。

代码中那位同学将数组in通过for循环誊写到另一个名为out的数组中，用于输出。

随后进行了do...while...语句，也就是先执行一遍A命令，检测一个bool是否为真，如果是真就重复A命令。
反之退出语句。

这里的A命令，首先设想了一个bool叫isCorrect并且初始为true，真。

随后遍历整个数组，如果有哪一项和前一项的大小不正确，就让他们互换，随后将设想的true的isCorrect，
改为否定及false。

while中使用isCorrect的反向，加了个！号，这样，当do中没有发现哪一项顺序不对，iscorrect就一直是true，
到了while中，反向的iscorrect就变成了false，因此通过，输出out数组。但是如果在do中发现有一项大小不对，
那么iscorrect立即变为false，并且中断遍历for，在while中！iscorrect为真，true，因此重复运行。  
![](https://github.com/Wyuebaibaibai/Baiwenyue_414join/blob/3626ca1e5e5151d995691fcfd507d30ebb1de110/1000.jfif)
