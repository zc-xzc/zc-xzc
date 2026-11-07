# Zicheng Xu · 许子成

**Mechanism · Algorithm · Intelligence**

📧 xzc18155121449@163.com

---

| [**embodied-ai-learning-handbook**](https://github.com/zc-xzc/embodied-ai-learning-handbook) ★71 | [**robot_platform**](https://github.com/zc-xzc/robot_platform) ★7 | [**postharvest-agent-framework**](https://github.com/zc-xzc/postharvest-agent-framework) | [**uav-leaflet-dispenser**](https://github.com/zc-xzc/uav-leaflet-dispenser) |
|---|---|---|---|
| 1800+ paper embodied AI guide | Head-tracking active vision platform | Closed-loop postharvest fruit handling | UAV single-sheet dispenser + patent |

| [**SO-ARM100**](https://github.com/zc-xzc/SO-ARM100) | [**embodied-intelligence**](https://github.com/zc-xzc/embodied-intelligence) | [**ai-biopharma-notes**](https://github.com/zc-xzc/ai-biopharma-notes) | [**academic-tools**](https://github.com/zc-xzc/academic-tools) |
|---|---|---|---|
| Open-source 3D-printable robot arm | Embodied AI project portal & index | AI × drug discovery study notes | Policy-text library & statistical analysis |

---

## 📚 embodied-ai-learning-handbook ★71

**具身智能学习手册 — 1800+ 论文系统性知识指南**

覆盖 VLA 模型、遥操作、Sim2Real、强化学习等完整知识体系。17 个目录、69 篇 Markdown 文档，从理论到前沿到实战，整合顶会论文（CVPR/AAAI/ICLR/NeurIPS）、仿真环境（MuJoCo/Isaac Lab）、数据飞轮与遥操作（ALOHA/UMI）等全栈资源。

```
学习路径 → 基础理论 → 经典算法 → 前沿技术 → 仿真环境 → 数据飞轮 → 项目实战 → 行业求职
```

`VLA` `Imitation Learning` `Sim2Real` `Teleoperation` `Reinforcement Learning` `MuJoCo` `Isaac Lab`

---

## 🤖 robot_platform ★7

*PICO 4 → dual-axis gimbal → RealSense D415 — full-stack active vision for humanoid robots*

<table>
<tr>
<td width="33%" align="center"><img src="./assets/exploded_overview.jpg" width="100%" /><br/><sub>Exploded view</sub></td>
<td width="33%" align="center"><img src="./assets/final_perspective.jpg" width="100%" /><br/><sub>Assembled gimbal</sub></td>
<td width="34%" align="center"><img src="./assets/left_side_view.jpg" width="100%" /><br/><sub>On robot platform</sub></td>
</tr>
</table>

3D-printable mounts · URDF/SDF models · PD controller · Win/Linux · Unitree G1

---

## 🍎 postharvest-agent-framework

**采后水果处理闭环智能系统 — 概念研究框架**

五段式前向管线配两条反馈回路：物理输入与感知 → 多模态品质推断（逐对象状态 `q = (g, d, m, u)`，即等级 / 缺陷 / 质量 / 不确定度）→ 监督智能体任务规划（仅检索·推理·提议，**不直接驱动电机**）→ 安全门控下的柔顺操作（力 / 速度 / 工作空间限幅）→ 可追溯审计输出（对象 ID、传感证据、动作日志，PASS / RECHECK / REJECT）。

验证设计明确可证伪：独立批次 + 人工核验标注 + 跨批次与光照迁移，B0 规则固定抓取 / B1 视觉分拣 / B2 加约束规划 / B3 加智能体与闭环审计四组消融。当前为概念设计阶段，收录框架图与设计说明，暂不含数据集与实验结果。

`Multimodal Perception` `Constraint-aware Planning` `Robotic Manipulation` `Traceable Audit`

---

## 🧬 ai-biopharma-notes

**AI × 药物发现学习笔记 — 行业图谱 · 方法论 · 公开工具**

五章公开资料整理：行业周期与格局、从表型到靶点的反向找靶（target fishing）、数据质量与多组学整合、可解释性与因果链、公开数据库与工具地图；附 ChEMBL 活性检索与 RDKit 结构归一化示例脚本。纯公开来源、论断附出处，CC BY 4.0。

`AI for Drug Discovery` `Target Identification` `Multi-omics` `RDKit`

---

## 🦾 SO-ARM100

**Standard Open Arm 100 — 开源低成本机械臂平台（SO-100 / SO-101）**

*(fork of [TheRobotStudio/SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100))*

SO-100/SO-101 3D 打印机械臂：引导臂 / 跟随臂遥操作方案，适配 Hugging Face LeRobot 生态，用于机器人遥操作与数据采集研究。含 3D 打印件、装配指南及可选硬件（相机支架、增高底座、柔性夹爪等）。

`3D Printing` `Robotic Arm` `Teleoperation` `LeRobot`

---

## 🧭 embodied-intelligence

**具身智能 Embodied Intelligence — 研究方向日志与项目索引**

纯研究方向日志：记录具身智能 / 人形机器人方向的研究路线，同时作为具身智能项目系列的 Portal & Index，从学习手册到机器人平台，集中索引全部相关仓库与文档。

`Embodied Intelligence` `Research Directions` `Portal` `Index`

---

## 🛸 uav-leaflet-dispenser

**无人机挂载式单张纸页分离投放装置**

UAV-mounted single-sheet paper dispensing device — 面向中型多旋翼无人机，打印机式搓纸分纸实现单张分离，配主动出纸快门遮蔽巡航，导纸通道使纸张切入旋翼下洗流减小落点漂移，微控制器实现单张 / 连续 / 飞控联动多模式投放。

📄 含 **专利交底书源稿** 及完整技术文档（需求规格 / 总体方案 / 查新报告 / 测试验收）

`Mechanical Design` `Embedded Control` `Patent`

---

## 🔧 Other Projects

| Project | Description | Stack |
|---|---|---|
| [Water_robot](https://github.com/zc-xzc/Water_robot) | Underwater stereo perception + FSI modeling (bionic fins) | C, YOLO |
| [fsi-coatings](https://github.com/zc-xzc/fsi-coatings) | 流固耦合数值模拟 × 钢结构涂层多场耦合老化 | Python |
| [MathViz](https://github.com/zc-xzc/MathViz) | Interactive 3D/2D math visualization — 把抽象概念变成可观察的空间结构 | HTML |
| [HandEye-Tsai](https://github.com/zc-xzc/HandEye-Tsai) | Fork — Tsai hand-eye calibration + VICON | MATLAB |
| [Dual-eye 3D Recon](https://github.com/zc-xzc/Dual-eye-three-dimensional-reconstruction-system) | Binocular stereo + YOLOv12 | Python, OpenCV |
| [AI-Vision](https://github.com/zc-xzc/AI-Vision) | Object detection & face recognition (TFLite) | Python, TensorFlow Lite |
| [yolov5-master](https://github.com/zc-xzc/yolov5-master) | YOLOv5 env: Py3.9 + PyTorch 2.0.1 + CUDA 11.8 | Python, YOLO |
| [ros](https://github.com/zc-xzc/ros) | ROS Docker env: URDF / Gazebo / MoveIt | ROS, Docker |
| [Docker-Localization](https://github.com/zc-xzc/Docker-Localization) ★1 | Fork — cross-registry Docker mirror → Alibaba Cloud ACR | GitHub Actions |
| [midea-local](https://github.com/zc-xzc/midea-local) | Fork — local LAN control for Midea M-Smart appliances | Lua |

---

## 🛠️ Skills

Python · PyTorch · MATLAB · C/C++ · ROS · OpenCV · RealSense · STM32 · Jetson · Docker · Git · Linux · SolidWorks · Fusion 360

---

📧 xzc18155121449@163.com · 🐙 [github.com/zc-xzc](https://github.com/zc-xzc) · 🎬 [space.bilibili.com/1664940404](https://space.bilibili.com/1664940404)

---

<sub>Mechanism · Algorithm · Intelligence</sub>
