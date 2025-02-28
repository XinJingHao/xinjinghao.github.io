---
layout:     post

title:      "ColorDynamic: Generalizable, Scalable, Real-time, End-to-end Local Planner for Unstructured & Dynamic Environments"

subtitle:   "ColorDynamic: 面向动态、非机构化环境的基于DRL的端到端局部规划算法"

author:     "Jinghao"

hidden: false
catalog: true
header-style: text

tags:

    - Paper

---


分享一下我的近期工作**ColorDynamic**，它由我之前的工作[Color](https://link.zhihu.com/?target=https%3A//www.sciencedirect.com/science/article/abs/pii/S0952197624018840)拓展而来，最核心的贡献是给模型赋予了时序感知能力，使得模型能够在非结构化的动态场景中实现局部规划。同时，该算法还可以无缝迁移到多机器人任务中。
- **项目链接：** https://github.com/XinJingHao/ColorDynamic
- **作者：** **Jinghao Xin**, Zhichao Liang, Zihuan Zhang, Peng Wang, and Ning Li
- **时间：** 2025


<p align="center">
  <img src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V2/case2.gif" width="500" />
  <img src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V2/case_cd.gif" width="500" />
  <img src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V3/N10.gif" width="500" />
</p>

<p align="center">
  <img src="https://github.com/XinJingHao/Images/raw/main/ColorDynamic/warehouse1.gif" width="500" />
  <img src="https://github.com/XinJingHao/Images/raw/main/ColorDynamic/warehouse2.gif" width="500" />
  <img src="https://github.com/XinJingHao/Images/raw/main/ColorDynamic/warehouse3.gif" width="500" />
</p>

<p align="center">
  <img src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V2/real1.gif" width="500" />
  <img src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V2/real2.gif" width="500" />
  <img src="https://github.com/XinJingHao/Images/raw/main/Sparrow_V2/real3.gif" width="500" />
</p>

