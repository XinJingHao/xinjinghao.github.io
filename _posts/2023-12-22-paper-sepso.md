---
layout:     post

title:      "SEPSO: Self-Evolving Particle Swarm Optimization for Real-time Path Planning"

subtitle:   "基于PSO的实时路径规划"

author:     "Jinghao"

hidden: false
catalog: true
header-style: text

tags:

    - Paper

---

<div align="center">
<a ><img width="250px" height="auto" src="https://github.com/XinJingHao/Real-time-Path-planning-with-SEPSO/blob/main/Code_for_Path_Plannning/Dynamic%20Path%20Planning%20with%20SEPSO(Application%20Phrase)/dynamic.gif?raw=true"></a>
</div>

### Efficient Real-Time Path Planning with Self-Evolving Particle Swarm Optimization in Dynamic Scenarios

- **期刊：** Unmanned Systems [Q2, IF:3.0]

- **作者：** **Xin J**, Li Z, Zhang Y, et al.

- **时间：** 2023

- **项目链接：** [https://github.com/XinJingHao/Real-time-Path-planning-with-SEPSO][2]

- **研究内容：** (1)在[DPPSO论文][1]的基础上，为DPPSO算法推导了张量运算形式，使之可以部署到GPU上加速运算，进一步提升算法实时性；(2)提出分层自进化架构（图1），使得算法可以自动整定其多样化超参数；(3)结合(1)和(2)，提出SEPSO算法；(4)提出基于线段表征的全局路径规划问题模型（图2），实现基于SEPSO的实时全局路径规划算法。

<div align="center">
<a ><img width="300px" height="auto" src="/img/in-post/HSEF.png"></a>
<p style="color: gray;">图 1 分层自进化架构</p>
</div>

<br>

<div align="center">
<a ><img width="300px" height="auto" src="/img/in-post/segments_problem.png"></a>
<p style="color: gray;">图 2 基于线段表征的全局路径规划问题模型</p>
</div>



[1]:https://xinjinghao.github.io/2022/08/31/paper-dppso/
[2]:https://github.com/XinJingHao/Real-time-Path-planning-with-SEPSO