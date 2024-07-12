---
layout:     post

title:      "Color: Train a Real-world Local Path Planner in One Hour"

subtitle:   "DRL与AGV能碰撞出怎样的火花?"

author:     "Jinghao"

hidden: false

catalog: true

header-img: "img/post-bg/real36.jpg"

tags:

    - Paper

---

### Train a Real-world Local Path Planner in One Hour via Partially Decoupled Reinforcement Learning and ectorized Diversity

- **期刊：** Engineering Applications of Artificial Intelligence [Q1, TOP, IF:7.5, 一修]

- **作者：** **Xin J**, Kim J, Li Z, et al.

- **时间：** 2024

- **项目链接：** [https://github.com/XinJingHao/Color][1]

- **研究内容：** 针对深度强化学习算法训练成本高和泛化性弱的问题，该研究提出了Color算法，如图1所示。具体的，Color由高性能训练框架ASL（图2）和高吞吐量并行仿真平台Sparrow（图3）组成。Color能在普通台式电脑上一小时内训练出具备强泛化能力的局部路径规划器，无需二次调试即可应用于现实世界的局部路径规划任务。


<div align="center">
<a ><img width="600px" height="auto" src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V0/color_img.png"></a>
<p style="color: gray;">图 1  Color: 基于深度强化学习的局部路径规划算法</p>
</div>

<div align="center">
<a ><img width="600px" height="auto" src="https://github.com/XinJingHao/Images/raw/main/asl/ASL.jpg"></a>
<p style="color: gray;">图 2  ASL高性能强化学习训练框架</p>
</div>

<div align="center">
<a ><img width="600px" height="auto" src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V1/render.gif"></a>
<p style="color: gray;">图 3  Sparrow：高吞吐量并行仿真平台</p>
</div>

[1]: https://github.com/XinJingHao/Color