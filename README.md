# project1 birthday attack
#202100460119 于洁 密码21.1
## 实验思路 ：截取SM3的56-bit输出来实现生日攻击  
        1. 随机生成2**(n/2)个消息  
        2. 对2**(n/2)个消息计算hash值   
        3. 寻找碰撞并输出原像以及原像的hash值   
## 攻击原理
根据生日悖论，每个集合含有2^(n/2)个元素就可以以约1/2的概率找到一对碰撞
