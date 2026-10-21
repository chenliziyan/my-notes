## Chapter 1 Go Over

两种误差：
- Random 随机误差: 无法避免的
- Systematic 系统误差: 错误的实验方式/实验器具 （未校准： **zero error**）导致


两种衡量：
- Precision 精确度 - *随机误差*影响
- Accuracy 准确度 - *系统误差*影响

减少方式：
1. Random 随机误差
   - 重复取平均
   - 更 precise 的 experiment tools 
2. Systematic 系统误差
   - **Recalibrate**：校准仪器
   - 改良实验方式

---

**三种 Uncertainty Measurements:**
例：$ x = (5.0  \pm 0.2)mm$
- Absolute: $ \Delta x = \pm 0.2 $
- Fractional: $ \frac{\Delta x}{x} = \frac{0.2}{5} = 0.04$
- Percentage: $ \%x = 0.04 \times 100 \% = 4\%$

总结：
absolute为最大减最小的一半
fractional和percentage等价，都为absolute除以average $x$

**加减乘除**
- 加减：absolute 相加
- 乘除：percentage 相加

---

## Chapter 2 Go Over

Kinematics 五公式（背）：
- 缺$ \Delta x$： $ v = u + at $ 
- 缺$ a$： $ \Delta x =  (\frac{u+v}{2}) t $
- 缺 $ t$：  $ v^2 = u^2 + 2a\Delta x$
- 缺 $ v $：  $ ut + \frac{at^2}{2}$
- 缺 $ u $：  $  vt - \frac{at^2}{2}$
---

## Chapter 3 Go Over

**Force**：Rate of change of momentum

牛顿三定律 定义（背）

---
**三种碰撞** 动量都守恒：
- Elastic = Perfectly Elastic 弹性（完全弹性）
  - 动能守恒
  - 相对速度不变：接近速度等于分离速度
- Inelastic 非弹性
  - 动能不守恒
- Perfectly Inelastic 完全非弹性
  - 碰撞后两个 objects 粘在一起（v相同）

---

## Chapter 4 Go Over

Torque = Moment
单位：$ N \cdot m$ （和焦耳相同）

- **Couple** 定义：
  - 两个力
  - act 在同一个面 （coplanar）
  - 大小相等，方向相反
  - 只导致旋转

---
**浮力的推导**
原因：水压差

水压公式：$ p = \rho gh$
所以浮力：$ F = (p_1 - p_2) \times A = \rho g (h_1 - h_2) \times A = \rho g V_排$
（A为面积，因为 $ F = p \cdot A$）

---
**区分正负功**
做功公式：$ W = Fd \cdot cos \theta$ （$\theta$ 为力和displacement两个向量的夹角）
夹角大于90°导致 $cos \theta$ 为负，所以做负功

---

## Chapter 5 Go Over

**Force - Extension图** & **两个 Limits**
![alt text](image.png)
**L**：limit of proportionality 在这之前符合胡克定律
**D**：limit of elasticity 之前为弹性（Elastic Deformation），之后为塑性（Plastic Deformation, 不可恢复原状）
做功：该图线下面积 （积分）
如果过了limit of elasticity，则是loading线到unloading线之间的面积（unloading线可以看作原来的线往右平移，即force为0时extension不为0）

---
**Stress** & **Strain**

应力：$Stress = \frac{F}{A}$
应变：$Strain = \frac{x}{L}$ （$x$为伸长量，$L$为原长度）

**Young Modulus （$E$）**
！！材料的属性
$$ E = \frac{Stress}{Strain} = \frac{FL}{Ax}$$
图和force extension差不多

---
## Chapter 7 Go Over (D)
**定义：** *常用名词*：震荡 **oscillation**
- Progressive Wave：传递能量，不传递物质
- Displacement：distance of a particle away from equilibrium position（垂直）
- Amplitude：A wave's maximum displacement from equilibrium position
- 频率：number of complete oscillations per second
- 周期：time taken for one complete oscillations
- 波长：length of a whole oscillation

---
**波的分类**
1. 机械波（波的传播需要介质），电磁波...
2. 行波（能量传播，波形前进），驻波（能量不传播）
   1. 驻波：两个行波叠加，**Nodes & Antinodes**
3. 横波（oscillate方向垂直与波传播方向），纵波（~ 平行于 ~）
   1. **Crest & Trough**（横），**Compression & Rarefaction**（纵）
   2. 地震s（横），地震p（纵）
   3. 纵波不能polarized，不能真空传播

---

**波的强度**
*Power per unit area*:
$$ I = \frac{P}{A}$$

行波-两个比例关系：
1. 正比于**振幅**平方：$I \propto A^2$
2. 正比于频率平方：$I \propto f^2$

球面波-平方反比定律 Inverse Square Law
1. 截面积 = 球体表面积 = $4 \pi r^2$
2. 所以和 $r $ 方成反比：$I \propto \frac{1}{r^2}$
*$r$ 即距离点波源的距离*

---
**多普勒效应**
*频率近高远低（移动）*
$$ f_o = \frac{f_sv}{ v \pm v_r}$$
$v$ 为波速，$v_r$ 为波源和观测者的相对速度
  - Towards减，Away加
---
**极化**
transverse wave polarized = ***vibrations restricted to one plane of ocsillation***
- 例：电磁波，磁场在一个plane上震荡，电场在一个plane上震荡
- Vertically/Horizontally polarized: 只在vertical/horizontal平面上震荡
- polarising filter - many parallel tiny slits：只允许与slit平行方向的波通过

**极化影响波的强度**
- 经过一个Polariser，I变为1/2：$I = \frac{I_0}{2}$
- 经过Analyser（第二个Polariser）： $ I = I_0cos^2 (\theta)$ 
  - 这里的$\theta$为analyser和polariser方向的夹角
  - 所以如果analyser和polariser方向一致，$cos \theta$等于1，则强度不变，如下图
   ![alt text](image-1.png)
  
---

## Chapter 8 Go Over (DD)

**定义：**
- **Superposition**: 2 or more waves of **same type** cross each other
- **Principle of Superposition**: when 2 or more waves overlap at a point, the displacement of resultant wave equals to the sum of displacement of individual waves.
- **Coherence**: waves having same frequency and constant phase difference.
- **Interference**: addition of displacements of individual waves when they overlap
  - Constructive: in phase, resultant wave's amplitude doubles
  - Destructive: anti-phase, results no amplitude/cancellation.

---
驻波
*formed when **2 progressive waves of same type** with **same Frequency, Wavelength and Amplitude** travelling in **opposite direction** overlap on each others.*
- Node: point where stationary wave has zero amplitude (in phase meet)
- Antinode: point where stationary wave has maximum amplitude (anti-phase meet)
  
---
**驻波 - 震荡模式**
*First, Second, Third Harmonic*
判断第几谐波：第n谐波指该条件下n个第一谐波相连
1. 两端封闭（两端都是node）
   1. First Harmonic：$\lambda_1 = 2L$
   2. Second Harmonic：$\lambda_2 = L$
   3. Nth Harmonic: $\lambda_n = \frac{2L}{n}$
2. 一端封闭一端开口（封闭端node，开口端 antinode）
   1. 只有 **odd** harmonic
   2. First Harmonic：$L = \frac{\lambda_1}{4}$
   3. Third Harmonic：$\lambda_3 = \frac{3\lambda_3}{4}$
3. 两端开口（两端都是 antinode）
   1. First Harmonic: $L = \frac{\lambda_1}{2}$
   2. Second Harmonic：$L = \lambda_2$

越高谐波，频率越高

---
**衍射**
*The spreading out of wave when it encounters aperture or abstacle*
- 改变振幅（丢失能量）
- slit width和波长长度差不多时衍射最明显

---
**干涉**
- Constructive: 
  - path difference $ = n\lambda$
- Destructive:
  - path difference $= (n+\frac{1}{2})\lambda$

双源：
maximum displacement lines的找法：
![alt text](<屏幕截图 2025-12-11 061310.png>)
确定一点是constructive干涉还是destructive干涉：
![alt text](<屏幕截图 2025-12-11 061421.png>)
比如该点是整数倍 path difference，所以是constructive。

---
**双缝干涉 （D）**
条件：恒定相位差（coherent），相同波长（monochromatic
  所以常用laser，白光并不是monochromatic
会产生 bright fringes 和 dark fringes
maxima: 正中间的 bright fringe: $n=0$，往两边分别$n=1,2,3...$

path difference示意图：
![alt text](<屏幕截图 2025-12-11 062041.png>)

**Young's double slit experiment:**
$$ \lambda = \frac{ax}{D}$$
$\lambda$：波源的波长
$a$：两个slits的距离
$x$：fringe width（相邻亮条纹/暗条纹之间距离）
$D$：slit到屏幕的平行距离
*主要是改变 $\lambda,a,D$ 影响 $x$*

