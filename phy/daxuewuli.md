# 第六章

## 6.1 电场强度 

电磁运动是物质的一种基本运动形式。电磁相互作用是自然界已知的四种基本相互作用之一，也是人们认识得较深入的一种相互作用。

### 6.1.1 电荷

#### 6.1.1.1 电荷的量子化

一个电子所带的电荷的绝对值是$e$，任何带点体所带的电荷是电子的$n$倍.

$$
q=\pm{ne} \\
$$

$$
\text{其中} n=1,2,3,\dots 
$$

$$
e=1.602 \times 10^{-18} C
$$


电荷只能取离散的不连续值的性质叫做电荷的量子化。

#### 6.1.1.2 电荷守恒定律

在一个孤立系统中，不管系统中的电荷如何迁移，系统的电荷的代数和保持不变．这一性质称为**电荷守恒定律**。

### 6.1.2 库伦定律

#### 6.1.2.1 库伦定律

1. 条件：
	1. 真空($\varepsilon_0=8.85\times{10^{-12}}C^2N^{-1}m^{-1}=8.85\times{10^{-2}}F\cdot{m^{-1}}$)
	2. 点电荷($ d << r $)


2. 库伦定律
	
	$$
	\vec{F}=\frac{1}{4\pi \varepsilon_0} \frac{q_1q_2}{r^2} \vec{e_r}
	$$
	静止电荷之间的电作用力又称**库仑力**


3. 说明：
	1.  库仑力遵守牛顿第三定律
	2. 牛顿第二定律以及牛顿第二定律所导出的结论，也都能适用于有库仑力作用的情形。


#### 6.1.2.2 电场强度

1. 静电场：
	1. 静电场存在于静止电荷的周围，并分布在一定的空间
	2. 处于静电场中的电荷要受到电场力的作用，并且当电荷在电场中运动时电场力也要对它做功


2. 电场强度
	1. 实验电荷
		1. 点电荷
		2. 电量足够小，对原电场几乎无影响


电场强度：

$$
\vec{E}=\frac{\vec{F}}{q_0}
$$

1. 电场中某点处的**电场强度**等于位于该点处的单位正试验电荷所受的电场力。
2. 单位：$N\cdot{C^{-1}}$
3. 说明：
	1. 电场强度是空间位置的函数
	2. 电场强度的方向与正试验电荷受力方向相同

### 6.1.3 点电荷电场强度

$$\vec{E}=\frac{F}{q_0}=\frac{1}{4\pi \varepsilon_0}\frac{Q}{r^2}\vec{e_r}$$

特点:
1. 方向沿场源与场点连线
2. 非均匀场，具有球对称性


### 6.1.4电场叠加原理

**电场强度叠加原理**：点电荷系所激发的电场中某点处的电场强度等于各个点电荷单独存在时对该点所激起的电场强度的矢量和。

**点电荷系的电场强度**：$\vec{E}=\sum^{n}_{i=1}\vec{E_i}=\frac{1}{4\pi \varepsilon_0}\sum_{i=1}^{n}\frac{Q}{r_i^2}\vec{e_i}$

**电荷连续分布的带点体场强**,元电荷$\text{d}q$
$$
	\vec{E}=\int_{V}\text{d}\vec{E}=\int_V\frac{1}{4\pi\varepsilon_0}\frac{e_r}{r^2}\text{d}q
$$

## 6.2 高斯定理

### 6.2.1 电场线

1. 曲线每一点的切线方向为该点电场方向

2. 电场线特性
	1. 起始于正电荷,终止于负电荷,不形成闭合曲线
	2. 任何两条电场线都不能相交
	
3. 电场线密度和电场强度间的数量关系
	
	$$
	\text{d}N=E\text{d}S
	$$
	
	$$
	\frac{\text{d}N}{\text{d}S}=E
	$$
	
	
	
4. **电场线密度** 通过电场中某点垂直于电场方向的单位面积的电场线数等于该点处电场强度的大小。

### 6.2.2 电场强度通量

1. 符号：$\Phi$
2. 定义：垂直通过电场中某一个面的电场线数
3. 匀强电场
	1. 平面与电场垂直:$\Phi_e=ES$
	2. 平面与电场不垂直 :
		1. 面积矢量：$\vec{S}=S\vec{e_n}$
		2. $\Phi_e=ES\cos{\theta}=\vec{E}\cdot{vec{S}}=\vec{E}\cdot{\vec{e_n}S}$
4. 非均匀电场 
	1. $S$为任一曲面
		
		$$
		\text{d}S=\text{d}S\cdot \vec{e_n}
		$$
		
		$$
		\Phi_e=\int_S\text{d}\Phi_e=\int_SE\cos{theta}\text{d}S=\int_S\vec{E}\cdot{text{d}\vec{S}}
		$$
		
		2. $S$ 为闭合曲面
		$$
    \Phi_e=\oint E \cos{\theta} \text{d}S=\oint\vec{E}\cdot\text{d}\vec{S}
    $$
    对于闭合曲面，曲面上某点的法线矢量的方向是垂直指向曲面外侧的。
		
 

### 6.2.3 高斯定理

1. 点电荷位于球面中心

$$
  E=\frac{q}{4\pi \varepsilon_0 R^2}
$$

$$
  \text{d}\Phi_e=\vec{E}\cdot \text{d}S=E\text{d}S
$$

$$
  \Phi_e=\oint\vec{E}\cdot \text{d}\vec{S}=\frac{q}{\varepsilon_0}
$$

  

  1. 若q为正电荷,穿出球面的电场线数为$\frac{q}{\varepsilon_0}$

  2. 若q为正电荷,穿入球面的电场线数为 $\frac{q}{\varepsilon_0}$

  3. 该结论对点电荷不在球心或任意形状的闭合曲面均成立。

4. 点电荷在闭合曲面之外
$$
  \Phi_e=0
$$

5. 点电荷系激发的电场:

$$
  \oint\vec{E}\cdot \text{d}\vec{S}=\frac{q}{\varepsilon_0}\sum^n_{i=1}q^{in}_i
$$

  这就是真空中的高斯定理

6. 在真空静电场中，穿过任一闭合曲面的电场强度通量，等于该曲面所包围的所有电荷的代数和除以$\varepsilon_0$

7. 高斯定理与库仑定律的关系：
  1. 高斯定理比库仑定律更基本，应用范围更广
  2. 库仑定律只适用于静电场，高斯定理不但适用于静电场, 对变化电场也是适用的。

8. 高斯定理的讨论
  1. 高斯面：闭合曲面
  2. 电场强度：所有电荷的总电场强度
  3. 电通量：穿出为正，穿进为负
  4. 仅面内电荷对电通量有贡献
  5. 静电场：有源场

## 6.3 静电厂环路定理 电势

### 6.3.1 静电场力所做的功

1. 在点电荷 q 的电场中
	
	$$
	W=\int{\text{d}W}=\frac{qq_0}{4\pi \varepsilon_0}(\frac{1}{r_A}-\frac{1}{r_B})
	$$
	这说明：做功仅与$q_0$的始末位置有关，而与路径无关.
2. 在任意带电体系的电场中
	$$
	\vec{E}=\vec{E_1}+\vec{E_2}+\dots
	$$
	试验电荷 q0 在静电场中从一点沿任意路径运动到另一点时，静电场力对它所作的功，仅与试验电荷q0  及路径起点和终点的位置有关，而与路径无关。

### 6.3.2 静电场的环路定理

$$
\oint_l{\vec{E}\cdot \text{d}l = 0}
$$
结论：静电场力是保守力，静电场是保守场

### 6.3.3 电势能

电荷$q_0$在静电场中的电势能:$E_{PA}$,$E_{PB}$

$$
W_{AB}=E_{PA}-E{PB}
$$

说明：电势能是一个相对的量;电势能属于电荷-电场系统

### 6.3.4电势

1. 电势：静电场中A点和B点的电势，$V_A=\int{AB}\vec{E} \cdot \text{d}\vec{l} + V_B$
	1. 理论上，若电荷分布在有限空间，常取无穷为零;若电荷分布在无限大空间，常选场中某点电势为零.
	2. 实用上，常选大地的电势或公共接地线的电势为零
	3. $U_{AB}=\int_{AB}\vec{E}\cdot \text{d}\vec{l}$
	4. 电场力的功和电势差的关系:把电荷q从点A点移到点B，静电场力所做的功$W_{AB}=qU_{AB}$
	5. 某点电势值与零电势点的选取有关，但两点间电势差与零电势点的选取无关
2. 点电荷电场的电势
$$
V=\int_{P}^{\infty}\vec{E}\cdot \text{d}\vec{l}
$$
$$
V=\frac{q}{4\pi \varepsilon_0}\frac{1}{r}
$$



3.电势的叠加原理

1. 在点电荷系的电场中:
$$
	V_A=\sum_{i=1}^n\frac{1}{4\pi \varepsilon_0} \frac{q_i}{r_i}
$$
2. 电荷连续分布的带电体电场:
	$$
	V=\frac{1}{4\pi \varepsilon_0}\int\frac{\text{d}q}{r}
	$$
	仅当取无穷远作为电势零点才能按照上式计算

### 6.3.5 等势面

等势面：电势相等的点连成的面
	1. 某点的电场强度与通过该点的等势面垂直
	2. 电场中任意两个相邻的等势面之间的电势差都相等

## 6.4 静电场中的导体

### 6.4.1 静电平衡条件
1. 导体内部任何一点处的电场强度为零
2. 导体表面处电场强度的方向，都与导体表面垂直.
3. 推论：导体为等势体
	1. 导体内各点电势相等
	2. 导体表面为等势面
### 6.4.2 静电平衡时导体上电荷的分布

1. 实心导体
	1. 结论：导体内部无净电荷，电荷只分布在导体表面.
2. 空腔导体
	1. 空腔内无电荷时，电荷分布在外表面，内表面无电荷
	2. 空腔内有电荷$+q$时，空腔内表面有感应电荷$-q$，外表面有感应电荷$+q$

### 6.4.3 静电屏蔽
1. 屏蔽外电场：用空腔导体屏蔽外电场
2. 屏蔽内电场：接地空腔导体屏蔽内电场



# 第七章  恒定磁场和电磁感应

人们发现磁现象要比发现电现象早得多，但直到1820年丹麦物理学家奥斯特的实验结果才揭示了电与磁之间的关联。随后，安培、法拉第等物理学家进一步得到了电与磁的联系，最终麦克斯韦建立了电磁场理论。
 本章主要讨论恒定电流激发的磁场的规律和性质。主要内容有：恒定电流密度，电源电动势，磁感强度，电流激发磁场的规律，反映磁场性质的基本原理，电磁感应定律等。

## 7.1 恒定电流 电流密度 电动势

1. 电流
	1. 电流：在电场力的作用下大量电荷作宏观定向运动
		1. 金属导体中——自由电子的定向移动
		2. 电离气体和电解质中——正负离子的移动
		3. 半导体中——电子和空穴的移动
	2. 传导电流：带电粒子（载流子）定向运动形成的电流.
	3. 运流电流：带电物体作机械运动时形成的电流. 
	4. 电流的方向：正电荷定向移动的方向
	5. 电流的表示：通过截面的电荷随时间的变化率
	6. $I = \frac{\text{d}q}{\text{d} t}$
	7. 如果导体中的电流不随时间变化——恒定电流
	8. 单位: 安培  符号：$A$
	9. $1A=1C\cdot s^{-1}$ 进率：10^3
	10. 注意: 电流是标量
2. 电流密度
	1. 电流密度:$\vec{j}$
	2. 方向：该点正电荷运动方向
	3. 大小：等于过该点并与电流方向垂直的单位面积上的电流
		$$
		j=\frac{\Delta{I}}{\Delta{S}\cos{\alpha}}
		$$
		$$
		\Delta{I}=\vec{j}\cdot\Delta{S}
		$$
	4. 通过导体任一有限截面 S 的电流:$I=\int_S\vec{j} \cdot \text{d}\vec{S}$
	5. 漂移速度$v_d$ ：自由电子在电场力的作用下产生的定向运动的平均速度
	6. 在$\Delta{t}$时间内通过$\Delta{S}$的电荷为$\Delta{q}=env_d\Delta{t}\Delta{S}$,即：$j=env_d$
3. 电源的电动势
单靠静电场不能在导体中维持恒定电流；必须有非静电场产生的非静电力，把正点荷不断地从负极板移动到正极板。
	1. 电源
		1. 电源:电源把正电荷从低电势运到高电势，使电流连续
		2. 非静电力: 电源内使正、负电荷分离，并使正电荷聚积
到电源正极，负电荷聚积到电源负极的非静电性质的作用。
		3. 实际上电源是把其它形式的能量转换为电能的装置
		4. 非静电电场强度: 为单位正电荷所受的非静电力
	2. 电动势
		1. 电动势的定义：单位正电荷绕闭合回路运动一周，非静电力所做的功
		2. $E=\int_内\vec{E_k} \cdot \text{d}\vec{l}$
		3. 电源电动势大小等于将单位正电荷从负极经电源内部移至正极时非静电力所作的功
		4. 电动势越大，表示电源将其它形式能量转换为电能的本领（或能力）越大。电动势的大小与电源内部结构有关

## 7.2 磁感强度  毕奥-萨伐尔定律  磁场的高斯定理

### 7.2.1 磁场强度

1. 磁场
	1. 运动电荷、传导电流、磁铁在周围空间激发磁场，磁场再对其它运动电荷、传导电流、磁铁施加作用力
	2. 恒定电流激发的磁场称为静磁场或恒定磁场
2. 磁感强度
	1. $\vec{B}=\frac{F_\bot}{qv}$
	2. 运动电荷在磁场中受力: $\vec{F}=q\vec{v}\times\vec{B}$，即: $F=qvB\sin{\theta}$
	3. 磁感强度单位:特斯拉($1T=1N\cdot A^{-1} \cdot m^{-1}$)

### 7.2.2毕奥—萨伐尔定律

![image-20200704170338438](/home/yepeng/.config/Typora/typora-user-images/image-20200704170338438.png)

1. 电流元在某点产生的磁场：
   1. 大小：$\text{d}B=\frac{\mu_0}{4 \pi}\frac{I \text{d}l\sin{\theta}}{r^2}$
   2. 方向：$\text{d}l\times\vec{r}$
   3. $\mu_0$：真空刺刀率
   4. 任一载流导线在点P处产生的磁感强度：$\vec{B}=\int\text{d}B$
   5. 毕奥－萨伐尔定律:$\text{d}\vec{B}=\frac{\mu_0}{4 \pi}\frac{I \text{d}\vec{l}}{r^2}$

2. 毕奥—萨伐尔定律应用举例 
   1. 无限长载流长直导线:$B=\frac{\mu_0I}{2\pi r_0}$
   2. 半无限长载流长直导线:$B=\frac{\mu_0I}{4\pi r_0}$
   3. 电流与磁感强度成右螺旋关系

### 7.2.3 磁场的高斯定理

1. 磁感线

   1. 曲线上每一点的切线方向表示该点磁感强度的方向，曲线的疏密程度表示该点的磁感强度的大小，这样的曲线称为磁感线
   2. 磁感线的特征
      1. 磁感线不会相交
      2. 磁感线都是围绕电流的无头无尾的闭合曲线，既没有起点，也没有终点

2. 磁通量

   1. 定义：通过磁场中某一曲面的磁感线数叫做通过该曲面的磁通量

   2. 匀强磁场

      1. 面积矢量：$\vec{S}=S\vec{e}$ 即$\Phi=\vec{B}\cdot{S\vec{e}}$

      2. 单位:$1Wb=1T\times1m^2$

      3. 非匀强磁场:

         1. S 为任一曲面

            1. $\Phi=\int_S\vec{B}\cdot \text{d}\vec{S}$

         2. S 为闭合曲面

            1. $\Phi=\oint_S\vec{B}\cdot \text{d}\vec{S}$

             对于闭合曲面，数学上规定，垂直曲面向外的方向为面法线的正方向

            磁感线从闭合曲面内穿出:$\Phi>0$

            穿过闭合曲面的总磁通量必为零即：
            $$
            \Phi=\oint\vec{B}\cdot \text{d}\vec{S}=0
            $$
            这就是就是磁场的高斯定理

3. 说明：

   1. 自然界没有单一的磁极存在
   2. 闭合曲面上各点的    不一定等于零

## 7.4 安培环路定理

1. 安培环路定理
   $$
   \oint\vec{B}\cdot{d}\vec{l} = \mu_0\sum_{i=1}^nI_i
   $$

2. 真空中磁场的安培环路定理:
   $$
   \oint_l\vec{B}\cdot{d}\vec{l} = \mu_0\sum_{i=1}^nI_i
   $$
    在真空的稳恒磁场中，磁感强度$B$沿任意闭合路径的积分（即 $\vec{B}$的环流的值，等于  $\mu_0$乘以该闭合路径所包围的各电流的代数和

3. 说明

   1. $\sum I_i$是指闭合路径所包围的所有电流的代数和
   2.  电流 I 正负的规定 ：I 与 l 成右螺旋时， I 为正；反之为负.
   3.  闭合路径上任一点的磁感强度是由闭合路径内﹑外电流共同激发的，故$\oint_l\vec{B}\cdot{d}\vec{l}=0$
   4. 说明磁场不是保守场，是涡旋场
   5. 长直密绕螺线管内中部的磁场是常见的均匀磁场:$B=\mu_0nI$
      1. n单位长度上的匝数
      2. $n=\frac{N}{L}$

## 7.6 动生电动势和感生电动势

$$
\varepsilon_i=-\frac{\text{d}{\Phi}}{\text{d}t}
$$

感应电动势:

1. 动生电动势——B 不变，导体运动
2. 感生电动势——B 变化，导体不动

### 7.6.1 动生电动势

1. $\varepsilon_i=vBl$

2. 动生电动势的微观解释
   $$
   \vec{F_m}=-e\vec{v}\times\vec{B}
   $$

   $$
   \vec{F}=-e\vec{E}
   $$

   非静电场强:
   $$
   \vec{E_K}=\frac{\vec{F_m}}{-e}=\vec{v}\times\vec{B}
   $$
   在磁场中运动的导线相当于一个电源

   产生动生电动势的非静电力是洛仑兹力.

   动生电动势:
   $$
   \varepsilon_i=\int_O^P\vec{E_K}\cdot\text{d}\vec{l}=\int_l{vB\sin{\theta}\cos{\alpha}\text{d}l}
   $$
   $\vec{v}$与$\vec{B}$成$\theta$角，$\vec{v}\times \vec{B}$与$\text{d}l$成$\alpha$

   <img src="/home/yepeng/.config/Typora/typora-user-images/image-20200704173116374.png" alt="image-20200704173116374" style="zoom:80%;" />



### 7.6.2 感生电动势

1. 把一闭合导体回路放置在变化的磁场中时，穿过闭合回路的Φ发生变化，在回路中激起的感应电动势
2. 麦克斯韦假设
   1. 变化的磁场在其周围空间激发感生电场   ，$\vec{E_K}$为涡旋电场，感生电场施与导体中电荷的力——感生电场力就是构成感生电动势的非静电力
3. 感生电动势:
   1. $\varepsilon_i$=-$\int_S\frac{\text{d}\vec{B}}{\text{d}t}\cdot\text{d}S$
   2. 说明:
      1. 变化的磁场激发感生电场，而感生电场产生感生电动势.
      2. 对于导体存在、回路闭合或不闭合；导体不存在，以及真空都适用.
      3. 反映感生电场是非保守场.
      4. ![image-20200704174321647](/home/yepeng/.config/Typora/typora-user-images/image-20200704174321647.png)



### 7.6.3 涡电流

1. 在大块导体内流动的感应电流——涡电流
2. 由于大块导体的电阻很小，涡电流可以达到很大
   的强度，产生很强的热效应

## 7.8  电磁振荡和电磁波

1865 年麦克斯韦在总结前人工作的基础上，建立了完整的电磁场理论. 他的主要贡献是提出了“有旋电场”和“位移电流” 两个假设，从而预言了电磁波的存在，并计算出电磁波的速度（即光速）
$$
c=\frac{1}{\sqrt{\mu_0\varepsilon_0}}
$$
​         1888 年赫兹的实验证实了他的预言, 麦克斯韦理论奠定了经典动力学的基础，为无线电技术和现代电子通讯技术发展开辟了广阔前景.

### 7.8.1电磁波的产生与传播

1. 变化的电磁场在空间以一定的速度传播就形成电磁波.

$$
T=2\pi\sqrt{LC}
$$

$$
v=\frac{1}{T}
$$

2. 电磁波的特性:
   1. 电磁波是横波 
   2. $\vec{E}$和$\vec{B}$同相位
   3. $\sqrt{\varepsilon_0}E=\sqrt{mu_0}B$
   4. 真空中电磁波的传播速度等于真空中的光速



###  7.8.2 电磁波谱

<img src="/home/yepeng/.config/Typora/typora-user-images/image-20200704174926619.png" alt="image-20200704174926619" style="zoom:150%;" />
