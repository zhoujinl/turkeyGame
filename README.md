![turkeyGame](https://github.com/zhoujinl/turkeyGame/blob/master/turkey.jpg?raw=true "我是好斗的小火鸡")  



# whoami
>模拟六合彩游戏  
游戏规则：摇号，从 1-49 个号码中，选出特码。  
假设当前赔率为X，即本金Y，得X倍数的奖金 Y*X。  
为提供中奖的概率，每次压住为Z个Y，本程序计算如何在有限的资金下，尽可能的分配每次的押注成本Y,以提高中奖概率  
为模拟真实的游戏，现假设X 为 48，Y为10，每次押注Z为13.  
```
params: python calc.py -h   
```
# 三大变量：
1. 准确率
2. 每期下注策略
3. 何时止盈止损

# 如何提高准确性
机器学习算法，提供下一期开奖号码

# 最重要
**赌博违法**  
**做个遵纪守法好公民**  
 

# TODO
* 完善下注策略、止盈止损
* 根据以往数据，推算最佳下注策略
