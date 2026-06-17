---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: ea2f37d43cca56d04dfb4cf037af349a_cbbb976e697311f1aa625254006c9bbf
    ReservedCode1: K+sz4ol/7cKPZfaVHmCeqMTGdj1ibiYnr+oVR8LICpUYKxV9HOmKQrv/GajZLLuyyTdJlmtQAFETIXDrxUFbH9yh+dZa0xJNcjLaa0u3aBqn2W1d2unbTSKgBlrCKkqvQlvAPOv/4ZrMzcpuBI8uVuBsjoxtV5BzKI28/VehKgiXOL5jZ3rbybDmRYo=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: ea2f37d43cca56d04dfb4cf037af349a_cbbb976e697311f1aa625254006c9bbf
    ReservedCode2: K+sz4ol/7cKPZfaVHmCeqMTGdj1ibiYnr+oVR8LICpUYKxV9HOmKQrv/GajZLLuyyTdJlmtQAFETIXDrxUFbH9yh+dZa0xJNcjLaa0u3aBqn2W1d2unbTSKgBlrCKkqvQlvAPOv/4ZrMzcpuBI8uVuBsjoxtV5BzKI28/VehKgiXOL5jZ3rbybDmRYo=
---

<p align="center">
  <img src="assets/avatar.png" alt="avatar" width="150">
</p>

<h1 align="center">Hi 👋, 我是陈瑞国</h1>
<h3 align="center">机器人与具身智能工程师 | 多传感器融合 | 全栈原型开发</h3>

<p align="center">
  <a href="README.md">🇬🇧 English</a>
  &nbsp;|&nbsp;
  <a href="mailto:1040889415@qq.com">📧 邮箱</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/wojiaoCRG">🔗 GitHub</a>
</p>

---

## 📋 个人简介

机械工程硕士在读，**3 年以上实操经验**，深耕车臂协同、实时多传感器融合、嵌入式控制与软硬件一体化。能够独立打通从 STM32 感知、ROS/ROS2 数据管道、光学动捕、CAD/PCB/3D 打印原型到 PyTorch/OpenCV 工作流的全链路系统。

- 🎯 **目标岗位：** NVIDIA Full-Stack Solution Engineer – Sensorized Human
- 📍 **所在地：** 中国
- 📅 **可入职时间：** 2026 年 7 月
- 🔬 **研究方向：** DexUMI 风格的人机技能迁移、示教数据集、模仿学习

<p align="center">
  <img src="assets/Overview.png" alt="Overview" width="80%">
</p>

---

## 🛠️ 核心技能

<table>
<tr>
<td width="18%"><b>🔧 语言与基础设施</b></td>
<td>Python, C++, STM32 HAL, CUDA, CMake, Bash/Shell, Git, GitHub Actions (CI/CD), Linux/Ubuntu, Docker, ROS/ROS2, ROS bag, tf2, Protobuf, MQTT, gRPC, YAML/JSON</td>
</tr>
<tr>
<td><b>🤖 机器人与控制</b></td>
<td>车臂协同、运动学/动力学建模、闭环控制、轨迹规划、SLAM、URDF/xacro、RViz、MoveIt、Gazebo、Isaac Sim、ros2_control、多传感器融合（视觉、IMU、里程计、动捕）、遥操作、系统标定</td>
</tr>
<tr>
<td><b>🧠 AI / 机器学习</b></td>
<td>PyTorch, CUDA/TensorRT, OpenCV, 扩散模型, Diffusion Policy, 行为克隆 (BC), ACT, 模仿学习管线, Domain Randomization, Sim2Real 迁移, HuggingFace, ONNX, 模型微调与部署</td>
</tr>
<tr>
<td><b>👤 人体感知与运动</b></td>
<td>光学动捕（12相机亚毫米级）、OpenPose/MediaPipe、SMPL/SMPL-X、运动重定向、RGB-D 相机（RealSense, Azure Kinect）、iPhone LiDAR/Record3D、人机技能迁移、DexUMI 风格数据管线</td>
</tr>
<tr>
<td><b>🔩 硬件与原型开发</b></td>
<td>SolidWorks, Fusion 360, PCB 设计, 3D 打印, I2C/SPI/UART/CAN, PID 控制, FreeRTOS, JTAG/SWD, BMS/电源系统, 电机驱动调参, 力/位移/电流传感, 机械装配, 快速原型</td>
</tr>
</table>

## 🚀 重点项目

### 1. 车臂协同移动操作与遥操作数据管线
*项目负责人 · 2023 年 9 月 – 2026 年*

<p align="center">
  <img src="assets/Vehicle-Arm.png" alt="车臂协同系统" width="75%">
</p>

<p align="center">
  <a href="https://www.bilibili.com/video/BV1LBjV6kEPN/">📹 B站观看：移动机器人3D打印演示</a>
</p>

- 对**全向移动底盘 + 多自由度机械臂**进行耦合运动学建模，解决 SLAM 漂移、运动不同步及实时偏差补偿问题。
- 融合**视觉、IMU、里程计、语音和动捕信号**构建统一感知-控制管线，记录关节角、末端位姿及偏差指标，支持回放分析。
- 搭建**ROS-bag 数据记录与回放工作流**，可扩展为人类示教数据集，用于遥操作、模仿学习及扩散策略训练。
- 🎯 **成果：** 末端/路径精度提升 22%–55%；成功制造 **1.2m × 1.2m** 大幅面薄壁件。
- 📄 **产出：** 1 个开源项目 · 1 篇第一作者 EI 论文 · 1 项授权实用新型专利。

---

### 2. 高精度动捕用于机器人轨迹标定 / High-Precision Motion Capture for Robot Trajectory Calibration
*独立研究 · 2025 年 7 月 – 10 月*

<p align="center">
  <img src="assets/Motion%20Capture.png" alt="光学动捕系统 / Motion Capture System" width="75%">
</p>

<p align="center">
  <a href="https://www.bilibili.com/video/BV1RBjV6rEYy/">📹 B站观看：动捕标定演示</a>
</p>

- 操作 **12 相机光学动捕系统**（亚毫米精度），记录打印任务中底盘与机械臂的动态轨迹。
- 将**动捕真值与机载里程计及 IMU** 进行时间同步，实现逐层误差分析与补偿。
- 🔄 **可迁移至人体追踪：** 空间标定、帧对齐、低延迟流传输、操作者运动到机器人末端的运动学映射。

---

### 3. 基于 STM32 的力感知直线执行器测试台
*本科毕业论文 · 2023 年 2 月 – 5 月*

<p align="center">
  <img src="assets/motor%20test.png" alt="测试台" width="75%">
</p>

<p align="center">
  <a href="https://www.bilibili.com/video/BV1HL41167A9/">📹 B站观看：电机测试台演示</a>
</p>

- 设计并搭建测试平台，测量**直线电机位移、电压、输出力及电流**。
- 编写 **STM32 HAL 固件**实现实时数据采集、闭环控制、传感器标定及实验验证。
- 🔧 建立了力测量、信号调理与确定性嵌入式控制的实践基础 —— 与**触觉传感及力反馈集成**直接相关。

---

### 4. 扩散 Transformer 微调用于语音转换
*独立研究 · 2025 年 4 月 – 7 月*

<p align="center">
  <img src="assets/huggingface.png" alt="HuggingFace" width="32%">
  <img src="assets/model%20training.png" alt="模型训练" width="64%">
</p>

- 在 PyTorch 中微调 **1.96 亿参数扩散 Transformer + Length Regulator**，完成 13 epoch / 500 优化步，损失降低约 50%。
- 🧠 强化了扩散模型调试、序列生成、训练循环设计及**可复现的 Linux/Docker 部署**能力 —— 可直接迁移至扩散策略管线。

---

### 5. 快速机电原型：电动滑板 & 升降椅
*独立 / 团队负责人 · 2021 年 6 月 – 2024 年 10 月*

<p align="center">
  <a href="https://www.bilibili.com/video/BV1y51uYWEHZ/">📹 B站观看：筋斗云电动滑板演示</a>
</p>
<p align="center">
  <a href="https://www.bilibili.com/video/BV18L4y1h7vY/">📹 B站观看：攀高椅演示</a>
</p>

- **电动滑板：** 完整硬件集成 —— 需求分析与器件选型 → PCB 制作 → **10S2P 电池组装配** → 电机控制器调参 → 结构制作。稳定运行 2 年以上。
- **智能全向升降椅：** 带领团队完成剪叉升降机构 + 手控界面的原型开发，强化了人本设计和全栈机电装配能力。

---

## 📚 论文与专利

| 类型 | 标题 | 发表/编号 | 年份 |
|------|------|-----------|------|
| 📄 **EI 期刊（第一作者）** | 移动机器人 3D 打印层间偏差优化双跟踪策略研究 | 《中国机械工程》 | 2025（已录用） |
| 🔧 **授权实用新型专利** | 一种基于视觉传感的双跟踪连续移动 3D 打印装置 | ZL 2025 2 0638034.7 | 2026 |

---

## 🏭 行业实习

| 公司 | 岗位 | 时间 |
|------|------|------|
| 宁波荣鸿汽车部件有限公司 | 激光切割操作员 | 2021 年 1 月 – 2 月 |
| 玉环通发塑料机械有限公司 | 机械制图与装配支持 | 2021 年 7 月 – 9 月 |
| 松正智能有限公司 | 产教融合项目负责人 | 2022 年 2 月 – 4 月 |

- **荣鸿：** 将产品图纸转化为钣金激光切割 CAD 排版，完成下料、尺寸检验及基础激光头维护。
- **通发：** 为吹塑设备钣金外壳进行三维建模，参与产线机械装配及电气接线。
- **松正：** 带领学生团队对热水器内胆产线进行三维建模，研究成型、冲压、卷边、焊接全流程。

---

## 🎓 教育背景

| 学校 | 学位 | 时间 |
|------|------|------|
| **新疆大学**（211 / 双一流） | 机械工程硕士 —— 车臂协同方向 | 2023 年 9 月 – 2026 年 6 月 |
| 台州学院 | 机械电子工程学士 —— 机器视觉方向 | 2019 年 9 月 – 2023 年 6 月 |

---

## 🏆 荣誉奖项

| 奖项 | 级别 |
|------|------|
| 浙江省政府奖学金 | 2020–2021, 2021–2022 |
| 新疆大学学业奖学金 | 2024, 2025 |
| 🥉 全国三维数字化创新设计大赛 三等奖 | 国家级 |
| 🥇 全国三维数字化创新设计大赛 特等奖 | 省级 |
| 🥈 全国三维数字化创新设计大赛 二等奖（×2） | 省级 |
| 🥈 工程训练大赛 & 机械设计大赛 二等奖 | 省级 |
| 🎖️ 浙江省优秀毕业生 | 2023 |

---

## 🔭 当前技术探索

- **Isaac Sim / Omniverse:** 基于 Python API 与 ROS2 Bridge 搭建 Human-in-the-Loop 仿真，用动捕数据驱动数字人。
- **SMPL/SMPL-X:** 加载参数化人体模型，从 AMASS 数据集驱动关节，在 Isaac Sim 中可视化。
- **Diffusion Policy:** 在车臂协同数据上复现 Stanford Diffusion Policy —— 从 ROS-bag 到动作生成。
- **低成本数据管线:** iPhone Record3D → SMPL 拟合 → Isaac Sim 重定向 → ROS2 流式传输原型。
- **Sim2Real 迁移:** 设计域随机化训练环境，对标真实机器人策略迁移效果。

📊 **技能差距分析:** [SKILL_GAP_ANALYSIS.md](SKILL_GAP_ANALYSIS.md)
🗺️ **6个月冲刺计划:** [ROADMAP_6MONTH.md](ROADMAP_6MONTH.md)---
