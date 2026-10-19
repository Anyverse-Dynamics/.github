<p align="left">
  <img src="https://raw.githubusercontent.com/jiejie567/JEPA-Policy/main/docs/images/anyverse-dynamics-logo.png" alt="Anyverse Dynamics · 无界动力" width="320">
</p>

# Anyverse Dynamics · 无界动力

将具身智能转化为可广泛部署、持续进化的基础设施。

[公司网站 / Website](https://www.anyverse.com/)

## 开源研究 / Open Research

### JEPA Policy

**无需扩散采样，同时预测动作与未来隐空间表征。** 视觉编码器与策略从头训练，通过共享 Transformer 学习配对的动作和未来表征。开源内容包括训练、评测及真机部署代码。

Diffusion-free imitation learning with paired action and future representation prediction, trained from scratch.

[Code](https://github.com/jiejie567/JEPA-Policy) · [Paper](https://arxiv.org/abs/2609.09630) · [Project](https://jiejie567.github.io/JEPA-Policy/)

### UpDown-SC

**无需训练的室内激光地点识别。** 通过重力对齐与双包络描述，保留不同高度的场景结构，减少室内天花板对地点区分的干扰。提供 C++ 实现、实验协议与结果。

Training-free indoor LiDAR place recognition with gravity-canonicalized dual-envelope Scan Context.

[Code](https://github.com/jiejie567/updown-sc) · [Project](https://jiejie567.github.io/updown-sc/)

### MonoEgo

**单目第一人称操作数据采集。** 一台头戴 RGB 相机、无源腕部标记和少量工位锚点，用于离线重建米制相机与双腕轨迹。MonoEgo 提供硬件设计、实验结果与演示；MonoTag-SLAM 提供标定、重建与回放代码。

Monocular metric egocentric demonstration capture with passive wrist constellations and sparse workstation anchors.

[Hardware & Results](https://github.com/jiejie567/MonoEgo) · [Processing Code](https://github.com/jiejie567/MonoTag-SLAM) · [Project](https://jiejie567.github.io/MonoEgo/)

---

本页汇总公开项目，代码在各原仓库持续维护。作者、引用方式及许可证请参阅对应项目。

Project authors, citation details, and licenses are provided in the linked repositories.
