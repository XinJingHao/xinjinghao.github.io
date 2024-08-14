---
layout:     post

title:      "OkayPlan: A real-time path planning algorithm for dynamic environments"

subtitle:   "考虑障碍物运动学的动态实时路径规划"

author:     "Jinghao"

hidden: false
catalog: true
header-style: text

tags:

    - Paper

---
<div align="center">
<a ><img width="250px" height="auto" src="https://github.com/XinJingHao/Images/raw/main/OkayPlan/navigation.gif"></a>
</div>

### OkayPlan: Obstacle Kinematics Augmented Dynamic real-time path Planning via particle swarm optimization

- **期刊：** Ocean Engineering [Q1, TOP, IF:4.6]

- **作者：** **Xin J**, Kim J, Chu S, et al.

- **时间：** 2024

- **项目链接：** [https://github.com/XinJingHao/OkayPlan][2]

- **研究内容：** 该研究提出了OkayPlan算法，如图1所示。该算法在[SEPSO][1]的基础上，增加了障碍物运动学增强的全局路径规划问题模型（图2）和动态先验初始化机制（图3），使之能够在动态环境中进行实时、安全的全局路径规划。

<div align="center">
<a ><img width="700px" height="auto" src="https://raw.githubusercontent.com/XinJingHao/OkayPlan/main/Overview.png"></a>
<p style="color: gray;">图 1 OkayPlan算法 </p>
</div>

<br>

<div align="center">
<a ><img width="250px" height="auto" src="/img/in-post/OKAOP.png"></a>
<p style="color: gray;">图 2 障碍物运动学增强的全局路径规划问题模型</p>
</div>

<br>

<div align="center">
<a ><img width="700px" height="auto" src="/img/in-post/DPI.png"></a>
<p style="color: gray;">图 3 动态先验初始化机制</p>
</div>

[1]:https://xinjinghao.online/2023/12/22/paper-sepso/
[2]:https://github.com/XinJingHao/OkayPlan
