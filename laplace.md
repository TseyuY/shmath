## 正式定义

对于所有实数<img src="http://chart.googleapis.com/chart?cht=tx&chl= $t\ge0$" style="border:none;">，函数的拉普拉斯变换是函数<img src="http://chart.googleapis.com/chart?cht=tx&chl= F(s)" style="border:none;">，定义为：

<img src="http://chart.googleapis.com/chart?cht=tx&chl= $$F(s)=\int_{0}^{\infty}e^{-st}f(t)dt$$" style="border:none;">

其中频率参数<img src="http://chart.googleapis.com/chart?cht=tx&chl= $s$" style="border:none;">是一个复数：<img src="http://latex.codecogs.com/gif.latex?{s=\sigma} +{i\omega}" />  ,<img src="http://chart.googleapis.com/chart?cht=tx&chl= $\sigma$" style="border:none;">和<img src="http://chart.googleapis.com/chart?cht=tx&chl= $\omega$" style="border:none;">为实数

## 性质和定理

tr

函数<img src="http://chart.googleapis.com/chart?cht=tx&chl= $f(t)$" style="border:none;"> 和<img src="http://chart.googleapis.com/chart?cht=tx&chl= $g(t)$" style="border:none;">的拉普拉斯变换分别是<img src="http://chart.googleapis.com/chart?cht=tx&chl= $F(s)$" style="border:none;">和<img src="http://chart.googleapis.com/chart?cht=tx&chl= $G(s)$" style="border:none;">:<img src="http://chart.googleapis.com/chart?cht=tx&chl= f(t)=\mathcal{L}^{-1}\{{F(s)}\}\\
g(t)=\mathcal{L}^{-1}\{{G(s)}\}" style="border:none;">


<h4><center>拉普拉斯变换的简表 <center><h4> 

|                          函数                          |                             时域                             |                             S域                              |
| :----------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                      单位脉冲信号                      | <img src="http://chart.googleapis.com/chart?cht=tx&chl= $\delta(t)$" style="border:none;"> | <img src="http://chart.googleapis.com/chart?cht=tx&chl= $1$" style="border:none;"> |
|                      单位阶跃信号                      | <img src="http://chart.googleapis.com/chart?cht=tx&chl= u(t)" style="border:none;"> | <img src="http://chart.googleapis.com/chart?cht=tx&chl= $\frac{1}{s}$ " style="border:none;"> |
|                      延迟脉冲信号                      | <img src="http://chart.googleapis.com/chart?cht=tx&chl= $\delta(t-\tau)$" style="border:none;"> | <img src="http://latex.codecogs.com/gif.latex?e^{-\tau {s}}" /> |
|                      延迟阶跃信号                      | <img src="http://chart.googleapis.com/chart?cht=tx&chl= $u(t-\tau)$" style="border:none;"> | <img src="http://latex.codecogs.com/gif.latex?\frac{1}{s}e^{-\tau{s}}" /> |
|                        斜坡信号                        | <img src="http://chart.googleapis.com/chart?cht=tx&chl= t\cdot {u(t)}" style="border:none;"> | <img src="http://chart.googleapis.com/chart?cht=tx&chl= \frac{1}{s^{2}}" style="border:none;"> |
| <img src="http://latex.codecogs.com/gif.latex?n"/>次幂 | <img src="http://chart.googleapis.com/chart?cht=tx&chl= $t^{n}u(t)$" style="border:none;"> | <img src="http://latex.codecogs.com/gif.latex?\frac{n!}{s^{n+1}}" /> |
|                        指数衰减                        | <img src="http://chart.googleapis.com/chart?cht=tx&chl= e^{-\alpha {t}}\cdot {u(t)}" style="border:none;"> | <img src="http://latex.codecogs.com/gif.latex?\frac{1}{s+\alpha}" /> |
|                        正弦函数                        | <img src="http://chart.googleapis.com/chart?cht=tx&chl= \sin(\omega {t})\cdot {u(t)}" style="border:none;"> | <img src="http://latex.codecogs.com/gif.latex?\frac{\omega ^{2}}{s^{2}+\omega^{2}} " /> |
|                        余弦函数                        | <img src="http://chart.googleapis.com/chart?cht=tx&chl= \cos(\omega {t})\cdot {u(t)}" style="border:none;"> | <img src="http://latex.codecogs.com/gif.latex?\frac{s^{2}}{s^{2}+\omega^{2}}" /> |

