# 🗺️ 6-Month Sprint Plan: NVIDIA Sensorized Human

> 目标：在 2026 年 12 月前达到 NVIDIA Full-Stack Solution Engineer – Sensorized Human 的核心要求

---

## Timeline Overview

```
Jun 2026 ──── Aug 2026 ──── Oct 2026 ──── Dec 2026
  Phase 1        Phase 2        Phase 3        Ready
  Foundations    Deep Build     Polish & Ship
```

---

## Phase 1: Foundations (Jun – Jul 2026) — Now

### Goal: 补齐数字人与仿真基础，建立 Isaac Sim 工作流

| Week | Focus | Deliverable | Est. Hours |
|------|-------|-------------|:----------:|
| **W1** | Isaac Sim 安装 + Getting Started | 跑通 5 个官方 Tutorial | 10h |
| **W2** | Isaac Sim Python API | 写 Python 脚本创建/控制机器人场景 | 12h |
| **W3** | SMPL/SMPL-X 模型学习 | 加载模型 → 输入参数 → 渲染 Mesh | 10h |
| **W4** | AMASS 数据集探索 | 下载动作数据，可视化 10+ 种动作 | 8h |
| **W5** | Human-in-the-Loop 仿真 | 动捕数据驱动 Isaac Sim 中数字人 | 15h |
| **W6** | ROS2 Bridge in Isaac Sim | 实现 ROS2 ↔ Isaac Sim 双向通信 | 12h |
| **W7** | MoCap → ROS2 → Isaac Sim Pipeline | 端到端 Demo + 录制视频 | 10h |
| **W8** | Buffer / Review | 整理文档，发布 Phase 1 总结博客 | 8h |

**Phase 1 产出物**:
- ✅ Isaac Sim 场景文件（USD）+ 控制脚本
- ✅ MoCap-to-IsaacSim 数据管线原型
- ✅ B站/博客：Phase 1 技术总结

---

## Phase 2: Deep Build (Aug – Sep 2026)

### Goal: Diffusion Policy 实战 + 低成本数据采集原型

| Week | Focus | Deliverable | Est. Hours |
|------|-------|-------------|:----------:|
| **W9** | Diffusion Policy 论文精读 | 笔记 + 核心公式推导 | 8h |
| **W10** | 复现 Stanford 官方代码 | 在自己的 ROS-bag 数据上训练 | 15h |
| **W11** | 超参数调优 + 结果分析 | 对比 BC vs Diffusion Policy | 12h |
| **W12** | iPhone Record3D 采集实验 | 用 1-2 部 iPhone 采集手部动作 | 10h |
| **W13** | Record3D → SMPL → Isaac Sim | 低成本数据采集管线 | 15h |
| **W14** | Domain Randomization | 生成 500+ 变体训练数据 | 12h |
| **W15** | Sim2Real 初步验证 | 仿真策略 → 实体机器人对比 | 15h |
| **W16** | Buffer / Open Source | 整理代码，写 README，开源发布 | 10h |

**Phase 2 产出物**:
- ✅ GitHub 开源项目：Low-Cost Human2Robot Data Pipeline
- ✅ Diffusion Policy 训练 + 对比实验报告
- ✅ B站视频：低成本数据采集 Demo

---

## Phase 3: Polish & Ship (Oct – Nov 2026)

### Goal: 完整 Sim2Real 项目 + 面试准备

| Week | Focus | Deliverable | Est. Hours |
|------|-------|-------------|:----------:|
| **W17** | Isaac Sim 高级特性 | Replicator / PhysX 调优 / RTX 渲染 | 12h |
| **W18** | 完整 Sim2Real 项目 | 从人类示教 → 仿真训练 → 实体部署 | 20h |
| **W19** | 系统级优化 | 延迟分析、带宽优化、精度对标 | 10h |
| **W20** | 技术文档 + Demo 视频 | 中英双语 README + Showcase 视频 | 10h |
| **W21** | 开源发布 + 社区推广 | 发布到 GitHub / B站 / NVIDIA Forum | 8h |
| **W22** | System Design 模拟面试 | 练习 5+ 道架构设计题 | 10h |
| **W23** | Coding + Domain 模拟面试 | LeetCode + 领域知识复习 | 12h |
| **W24** | Final Polish | Resume 更新、Portfolio 整理、Mock Interview | 10h |

**Phase 3 产出物**:
- ✅ 完整 Sim2Real 项目（开源，50+ Stars 目标）
- ✅ NVIDIA Developer Forum 技术帖
- ✅ GTC 2027 Poster 提案草稿
- ✅ 模拟面试记录 + 改进清单

---

## Key Milestones

| Date | Milestone | Metric |
|------|-----------|--------|
| 2026-07-15 | MoCap-to-IsaacSim Pipeline 完成 | Demo 视频发布 |
| 2026-08-31 | Diffusion Policy 训练成功 | BC vs DP 对比报告 |
| 2026-09-30 | Low-Cost Data Pipeline 开源 | GitHub 20+ Stars |
| 2026-10-31 | 完整 Sim2Real 项目 | 论文级别实验报告 |
| 2026-11-30 | 面试 Ready | 5 轮模拟面试通过 |
| 2026-12-15 | Portfolio 最终版 | Resume + GitHub + Portfolio 对齐 |

---

## Weekly Check-in Template

```
Week __:

✅ Completed:
- [ ] Task 1
- [ ] Task 2

📝 Learnings:
- 

🚧 Blockers:
- 

🎯 Next Week:
- [ ] Priority 1
- [ ] Priority 2
```

---

## Resources & References

| Category | Resource | Link |
|----------|----------|------|
| **Isaac Sim** | Official Documentation | https://docs.omniverse.nvidia.com/isaacsim/ |
| **Isaac Sim** | GitHub Samples | https://github.com/NVIDIA-Omniverse/isaac-sim-samples |
| **SMPL-X** | PyTorch Implementation | https://github.com/vchoutas/smplx |
| **AMASS** | Motion Dataset | https://amass.is.tue.mpg.de/ |
| **Diffusion Policy** | Stanford Code | https://github.com/real-stanford/diffusion_policy |
| **ACT** | Imitation Learning | https://tonyzhaozh.github.io/aloha/ |
| **Record3D** | iPhone 3D Capture | https://record3d.app/ |
| **NVIDIA DLI** | Free Courses | https://learn.nvidia.com/ |
| **ROS2** | Official Tutorials | https://docs.ros.org/en/humble/ |

---

*Plan created: 2026-06-17*
*Next review: 2026-07-01*