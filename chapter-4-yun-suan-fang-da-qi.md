---
description: by mjuicem
---

# 🥰 Chapter 4 运算放大器

## 理想运算放大器 ideal op amp

#### 一般原理

理想的运放电路分析有两大重要原则贯穿始终，即“虚短”与“虚断”。“虚短”的意思是正端和负端接近短路，即V+=V-,看起来像“短路”;“虚断”的意思是流入正端及负端的电流接近于零，即I+=I-=0,看起来像断路（因为输入阻抗无穷大）

#### 端电压和端电流

* 所有电压相对于公共节点为电压升
* 所有电流参考方向都是进入运放的端子
* $$v_p=v_n$$
* $$i_p=i_n=0$$

<div>

<figure><img src=".gitbook/assets/截屏2023-04-23 15.20.35.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/截屏2023-04-23 15.20.50.png" alt=""><figcaption></figcaption></figure>

</div>

#### 反向放大器

**比例器**

![image](https://user-images.githubusercontent.com/114148730/233790332-9954cfa1-9b22-45fc-a159-ab297463fe0d.png)

$$v_p=v_n=0$$

$$i_p=i_n=0$$



**求和放大器**

![image](https://user-images.githubusercontent.com/114148730/233790351-68ac9255-ada2-4eab-b349-5254daaf5597.png)

#### 同向放大器

![image](https://user-images.githubusercontent.com/114148730/233790359-9bd7b73f-0b6e-41d1-9b59-f607dea195c4.png)

$$v_1=v_2=v_S$$

$$i_p=i_n=0$$

#### 差分放大器(难点)

![image](https://user-images.githubusercontent.com/114148730/233790374-ccfdfd15-3e9a-4bb6-8770-acb81832dc8f.png)

差分放大器的题型非常多，所以没有现成的公式可以记，所以应该对每道题按&#x20;

1.虚短虚断($$i_p=i_n=0$$, $$v_p=v_s$$)

&#x20;2.KCL列方程

这两个步骤

**差分放大器中的叠加方法**

![image](https://user-images.githubusercontent.com/114148730/233790384-02982321-b093-4c50-ae6f-b2ba9dada13c.png)

#### summary

![image](https://user-images.githubusercontent.com/114148730/233790394-ecb2bb79-081a-4a87-807d-719d2f7a5044.png)
