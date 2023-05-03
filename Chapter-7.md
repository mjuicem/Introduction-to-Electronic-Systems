---
description: by mjuicem

---



### 复数的基本概念



**欧拉公式：** $$e^{j\varphi} = cos\varphi + jsin\varphi $$
$$e^{-j\varphi} = cos\varphi - jsin\varphi$$  



**复数：**$$z = a + bj$$

​			$$z^* = a - bj$$

​	$$a = Re[z]$$ ，  $$b = Im[z]$$



**复数的极坐标形式:** 

因为$$a = rcos\varphi$$，$$b = rsin\varphi$$

所以 $$z = r(cos\varphi + jsin\varphi)$$  



**复数的指数表达形式:**

$$z = r(cos\varphi + jsin\varphi ) = re^{j\varphi} = r\angle \varphi$$  

**复数的运算：**  

* 加法：$$z_1 = a_1 + b_1j$$ ，$$z_2 = a_2 + b_2j$$    => $$z_1 + z_2 = (a_1 + a_2) + (b_1 + b_2)j$$

*Tips*：当进行相量加法时，应用复数的正常形式进行运算

* 乘法：$$z_1 = r_1e^{j\varphi_1} = r_1\angle \varphi_1 $$，$$z_2 = r_2e^{j\varphi_2} = r_2\angle \varphi_2$$ => $$z1 * z2 = r_1r_2\angle \varphi_1 + \varphi_2$$

* 除法: $$\frac{z_1}{z_2} = \frac{r1}{r2}\angle \varphi_1 - \varphi_2$$





### 相量变换与反相量变换

正弦函数的**相量(phasor)**是含幅值和相位角的复数，欧拉公式给出了指数函数和三角函数的关系



**正弦电源：**$$v(t) = V_mcos(wt + \varphi) = Re[V_m(cos(wt+\varphi) + jsin(wt+\varphi))] = Re[V_me^{j(wt + \varphi)}]$$  

可以注意到$$V_me^{j\varphi}$$是一个既包含正弦函数幅值和相位角的复数，我们称这个复数为给定正弦函数的**相量**



**相量（Phasor)：**  **V** = $$V_me^{j\varphi}$$



**相量变换：**我们称$$P[V_mcos(wt+\varphi)]$$ 为$$V_mcos(wt + \varphi)$$的相量变换

其中$$P[V_mcos(wt+\varphi )] = V_me^{j\varphi} = V_m\angle \varphi$$



**反相量变换：**反相量变换即为相量变换的逆运算

$$P^{-1}[V_me^{j\varphi}] = V_mcos(wt + \varphi)$$



**相量变换的作用：**

> **Phasor transform transfers the sinusoidal function from time domain to phasor domain, which is also called** **frequency domain**





### 频率域下的无源电路元件

**阻抗(impedance)：**$$\hat{Z}$$

**电阻：** $$\hat{V} = R\hat{I} \Rightarrow Z_R = R$$  

**电感：**$$\hat{V} = \frac{1}{jwC} \hat{I} \Rightarrow Z_L = jwL$$

**电容：**$$\hat{V} = jwL\hat{I} \Rightarrow Z_c = \frac{1}{jwC}$$    *Tips：*注意电容和电流的正负关系





### 频率域下的KCL和KVL

**KCL:**$$\sum \hat{I} = 0$$

**KVL:** $$\sum \hat{V} = 0$$

频率域下的电压电流、阻抗串并关系不发生改变













