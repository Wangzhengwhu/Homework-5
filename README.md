# Homework-5
##选择书上的1.5 核子衰变模型
##背景  
核子衰变模型与人口增加模型同样可以用欧拉法来解决，但是本题并不是真正意义上的衰变模型，它是指核子A和核子B可以相互衰变，即A能变为B，B也能变为A
可以认为该过程为可逆过程，A B两者拥有相同的能量。因而，根据书上给出的2个微分方程，刷上的方程假定A B两核子的衰变常数是一样的。同样仿照人口模型，
根据书上的微分方程，通过调整参数的设定，我们可以给出一些结论。  
##数值解微分方程
按照书上给出的参数，先进行模拟，NA=100,NB=0,tau=1，t=10 dt=0.1  
[衰变程序](https://github.com/Wangzhengwhu/Homework-5/blob/master/%E6%A0%B8%E5%AD%90%E8%A1%B0%E5%8F%98%E6%A8%A1%E5%9E%8B.py)  
![衰变图像](https://github.com/Wangzhengwhu/Homework-5/blob/master/%E6%A0%B8%E5%AD%90%E8%A1%B0%E5%8F%98.png)  
从图中我们可以看出，当时间快接近4秒的时候，两者的区别在肉眼内不可分辨，根据趋势线推测，两者最终会达到一个动态平衡。
可以说这个衰变过程是一个稳定的衰变过程。  
接下来我们把总时间缩小，令t=3；t=1，继续上面的操作，结果如下图  
t=3s时的图像  
![衰变程序 t=3](https://github.com/Wangzhengwhu/Homework-5/blob/master/t%3D3.png)  
t=1s时的图像  
![衰变程序 t=1](https://github.com/Wangzhengwhu/Homework-5/blob/master/t%3D1.png)  
当时间越短的时候，我们越能看出前期衰变时候，A与B粒子数目的对比，它们的衰变符合指数分布，当t趋向于无穷时，它们两者达到平衡。




##致谢
感谢张爽同学提供的程序  

 

