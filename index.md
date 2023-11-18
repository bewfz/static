# 「沾水之后的两片玻璃为何很难分开？」

## 现象描述

流行科普上讲，由于玻璃之间充满了水，它们之间没有空气，因而靠大气压就可以把它们紧密地挤压在一起。如下图所示：

![现象图](https://pica.zhimg.com/80/v2-fb4c43622f55a7721f3d88624688cc22_1440w.webp?source=1def8aca)

## 原理分析

**但是这个答案其实并不正确，或者说并不准确。**

因为我们知道，水也是满足帕斯卡原理的。大气压并不仅仅是作用在玻璃表面的，玻璃中间的水也与大气有接触，因而大气压也会作用在缝隙中的水上的。由帕斯卡原理，外界的大气压力是可以经由水传递到玻璃间隙之中的。所以仅仅是有水的填充，玻璃不会「被大气压挤压在一起」。我们可以用下面的局部放大图来说明这种情况：

![原理1](https://pic1.zhimg.com/80/v2-55bc7d0e362bb768a7b1f38060dffc10_1440w.webp?source=1def8aca)

**缝隙中的水也会将大气压传递到两片玻璃的缝隙内部。大气压的作用效果并非是「向内」挤压两片玻璃，因为在缝隙内部同样存在着压力。**

这里的真实原因，**其实是表面张力与大气压的共同作用。**

![原理2](https://pic1.zhimg.com/80/v2-2e1b6f23bae8dd69e595e18fe9bd871e_1440w.webp?source=1def8aca)

***

谬误勘正：**水和大气的界面不是平的，而应该是一个凹液面。**

这就引出了上文的结论：**表面张力与大气压的共同作用**

表面张力，我们简单形象地理解，**可以认为流体的两相（如气液）界面就像是一张紧绷的皮膜，这张膜在外力的约束下，总是希望尽可能地收缩。**沿着它的表面就有一种张力，就是表面张力。

![原理3](https://picx.zhimg.com/80/v2-6992d95e31926b56958acc1bcb9a1279_1440w.webp?source=1def8aca)

**由于表面张力的存在，弯曲的表面就会在两侧形成压力差。**

### 压力差的变化

决定因素就是张力的大小：“绷”的越紧，所能产生的压力差就越大。但是还有另一个很重要的因素，就是表面弯曲的程度，也就是它的曲率。

![原理4](https://picx.zhimg.com/80/v2-0c1e1d85cfc13398cc35416ab419523f_1440w.webp?source=1def8aca)

明显地，气球内部的气压应该处处相等，那为什么有些地方感觉“崩”的更紧呢？

皮膜的曲率是不相等的：**曲率越大，同样的张力所能产生的压力差就更大；曲率越小，同样的张力产生的压力差就越小。**

我们有一个公式可以表示这个关系，叫做杨-拉普拉斯方程（Young-Laplace equation）：

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mi mathvariant="normal">Δ</mi><mi>p</mi><mo>=</mo><mi>γ</mi><mrow data-mjx-texclass="INNER"><mo data-mjx-texclass="OPEN">(</mo><mfrac><mn>1</mn><msub><mi>R</mi><mn>1</mn></msub></mfrac><mo>+</mo><mfrac><mn>1</mn><msub><mi>R</mi><mn>2</mn></msub></mfrac><mo data-mjx-texclass="CLOSE">)</mo></mrow></math>

![原理5](https://pic1.zhimg.com/80/v2-d0f6ed6a3a7d9b7b2ce63f3d5f8ed984_1440w.webp?source=1def8aca)

这个凹液面沿着我们切面的视角上的曲率半径是（假设玻璃的间隙为 d）（初中数学）：

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mi>R</mi><mo>=</mo><mfrac><mi>d</mi><mrow><mn>2</mn><mi>c</mi><mi>o</mi><mi>s</mi><mi>θ</mi></mrow></mfrac></math>

**证明一下**
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

我们假设液膜面积尺度远大于间隙尺度，这个凹液面所产生的液体内部与大气之间的压力差为：

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mi mathvariant="normal">Δ</mi><mi>p</mi><mo>=</mo><mfrac><mi>γ</mi><mi>R</mi></mfrac><mo>=</mo><mi>γ</mi><mfrac><mrow><mn>2</mn><mi>c</mi><mi>o</mi><mi>s</mi><mi>θ</mi></mrow><mi>d</mi></mfrac></math>

两片（面积不大的）玻璃的缝隙数量级在 5 微米左右。（来源于网络）

常温下水的表面张力大约为 0.073N/m。水在普通玻璃上的接触角大约为 30°左右。

**计算一下**
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

因此，对于贴合较好的两片玻璃片，很容易计算出这个液膜内部的压力与大气压的压力差为 25Kpa – 大约为大气压的 1/4 左右。

也就是说，液膜内部压力比大气压小 25Kpa。对于这样 <math xmlns="http://www.w3.org/1998/Math/MathML"><mn>10</mn><mi>c</mi><msup><mi>m</mi><mrow><mn>2</mn></mrow></msup></math> 的两片玻璃，如果我们用一点水把它「沾」在一起，我们需要大约 250N 的力才能掰开。但是如果是按照流行科普的说法（液膜排出空气导致玻璃间隙压力为零），我们所需要 1000N 的力才能掰开，这个就不太可能了。

# The End