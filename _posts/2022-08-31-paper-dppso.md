---
layout:     post

title:      "DPPSO: A diversity-based parallel particle swarm optimization algorithm"

subtitle:   "PSO如何分布式运算？"

date:       2022-08-31 12:00:00

author:     "Jinghao"

hidden: false
catalog: true
header-style: text

tags:

    - Paper

---

### A diversity-based parallel particle swarm optimization for nonconvex economic dispatch problem

- **期刊：** Transactions of the Institute of Measurement and Control [Q3, IF:1.7]

- **作者：** **Xin J**, Yu L, Wang J, et al.

- **时间：** 2022


- **研究内容：** 针对粒子群优化算法(PSO)寻优能力差，收敛速度慢的问题，设计出基于多样性的并行粒子群优化算法(DPPSO)。如图1所示，该算法首先将粒子群分组，并赋予每组不同的超参数，从而增加粒子多样性并提升算法寻优能力。其次，DPPSO将各组粒子的计算分散至不同CPU核上并行计算，以提升收敛速度。最后，为各组建立如图2所示的异步信息交互机制，以保证算法的收敛性。


<div align="center">
<a ><img width="400px" height="auto" src="/img/in-post/diversity.png"></a>
<p style="color: gray;">图 1 基于多样性的粒子群优化算法 </p>
</div>

<br>

<div align="center">
<a ><img width="600px" height="auto" src="/img/in-post/AISM.png"></a>
<p style="color: gray;">图 2 异步信息共享机制</p>
</div>
