## 正式定义

对于所有实数$t\ge0$，函数的拉普拉斯变换是函数$F(s)$，定义为：
$$
F(s)=\int_{0}^{\infty}e^{-st}f(t)dt
$$

其中频率参数$s$是一个复数：

$s=\sigma + i\omega$ ,$\sigma$和$\omega$为实数

## 性质和定理

函数$f(t)$和$g(t)$的拉普拉斯变换分别是$F(s)$和$G(s)$:
$$
f(t)=\mathcal{L}^{-1}\{{F(s)}\}\\
g(t)=\mathcal{L}^{-1}\{{G(s)}\}
$$

<h4><center>拉普拉斯变换的简表 <center><h4> 

|     函数     |            时域            |                   S域                   |
| :----------: | :------------------------: | :-------------------------------------: |
| 单位脉冲信号 |        $\delta(t)$         |                   $1$                   |
| 单位阶跃信号 |           $u(t)$           |              $\frac{1}{s}$              |
| 延迟脉冲信号 |      $\delta(t-\tau)$      |              $e^{-\tau s}$              |
| 延迟阶跃信号 |        $u(t-\tau)$         |        $\frac{1}{s}e^{-\tau s}$         |
|   斜坡信号   |       $t\cdot u(t)$        |            $\frac{1}{s^{2}}$            |
|   $n$次幂    |        $t^{n}u(t)$         |          $\frac{n!}{s^{n+1}}$           |
|   指数衰减   | $e^{-\alpha t}\cdot u(t)$  |          $\frac{1}{s+\alpha}$           |
|   正弦函数   | $\sin(\omega t)\cdot u(t)$ | $\frac{\omega ^{2}}{s^{2}+\omega^{2}} $ |
|   余弦函数   | $\cos(\omega t)\cdot u(t)$ |    $\frac{s^{2}}{s^{2}+\omega^{2}}$     |

