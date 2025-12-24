---
layout: default
title: 论文与期刊
---

# 论文与期刊

## 概览与个人轨迹
- 我的研究从本科学习的机器人与无线定位切入，逐步延伸至研究生阶段的云端数据分析平台，形成了“数据采集-清洗-分析-可视化”的端到端闭环思路。
- 这一闭环方法后来在自动驾驶与大规模数据基础设施建设中不断被验证和强化：以城市级异构数据平台为原型，将多源数据统一建模、评估并沉淀为可复用的工具链。


## 研究生阶段

### 硕士学位论文 (University of Ottawa, 2016)
**面向云端的数据分析与可视化系统** (Towards a Cloud-based Data Analysis and Visualization System)
- 类型：硕士学位论文（M.A.Sc Thesis）
- 机构：渥太华大学 (University of Ottawa)
- 学校存档链接：[https://ruor.uottawa.ca/handle/10393/35030](https://ruor.uottawa.ca/handle/10393/35030)
- 本地副本：[下载 PDF](./papers/thesis_ma_2016.pdf)

> 关键词：多源数据采集、云端存储与计算、清洗与结构化、标注/分析、可视化与交互式展示；以"项目驱动"方式打通端到端数据闭环。
> 摘要：该论文从工程视角构建了一个云端数据分析与可视化系统，强调多源数据的统一采集、清洗、标注与交互式呈现，为后续在智慧城市与自动驾驶场景的“数据基础设施化”探索奠定了方法论基础。

### 英文期刊论文
**City digital pulse: a cloud based heterogeneous data analysis platform**  
（城市数字脉搯：基于云端的异构数据分析平台）
- 期刊：Multimedia Tools and Applications (Springer)
- Online publication：2016-11-11；Volume 76, pages 10893–10916 (2017)
- DOI：[10.1007/s11042-016-4038-2](https://doi.org/10.1007/s11042-016-4038-2)
- Springer 链接：[查看论文](https://link.springer.com/article/10.1007/s11042-016-4038-2)
- 本地副本：[下载 PDF](./papers/journal_mtap_2017.pdf)

> 关键词：异构城市数据平台、情感/话题等分析、可视化仪表盘；与 thesis 一脉相承，是对外更标准的可引用版本。
> 摘要：文章将论文成果产品化，构建面向城市的异构数据分析平台，支持情感、话题等多维度分析和可视化仪表盘，体现了对真实业务指标的敏感度与落地思路。

## 本科阶段

### 中文期刊
《一种手机平台控制的轮式探测机器人的设计与实现》
- 期刊版：[下载 PDF](./papers/journal_undergraduate.pdf)
- 完整原稿版：[下载 PDF](./papers/journal_undergraduate_full.pdf) （内容更详细）
- 备注：期刊信息（期号/页码/链接）后续补齐

> 摘要：基于手机控制的轮式机器人项目帮助我在硬件驱动、实时控制与通信链路上建立了系统级视角，这种“软硬件协同”经验后来迁移到车端传感器与云端平台的协同设计上。

### 本科毕业论文
**轨迹挖掘在机会网络异常发现中的应用研究（WiFi 指纹室内定位原型系统）**
- 作者：李众力（本科毕业论文）
- 本地副本：[下载 PDF](./papers/thesis_undergraduate_wifi.pdf)
- 概述：在 Android 端实现 WiFi 指纹采集与在线定位原型，客户端采集 RSS 指纹上传到 SAE 云端匹配并返回位置，为后续轨迹异常发现提供数据基础。
- 个人亮点：
  - 端云闭环：双模式客户端（学习采样 / 在线定位）+ SAE 后端存储与指纹匹配。
  - 稳定性提升：多次采样统计量、SSID 过滤与“靠谱度”权重，缓解室内 RSS 波动。
  - 目标导向：聚焦“获得可用轨迹”以支持机会网络中的异常点挖掘。
