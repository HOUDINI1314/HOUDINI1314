<div align="center">

# 胡洋

**西南交通大学 · 交通运输硕士（2027 届）**

数学与应用数学学士 · 深度学习 / 优化理论 / 大模型

正在寻找 **AI 算法 · 大模型应用 · Agent 开发** 岗位

</div>

---

数学训练打下建模和优化的底子，硕士阶段把深度学习和大模型用在轨迹预测、网络优化和 Agent 工具上。实习期间在上市公司做过硬件设计场景的知识库与绘图 Agent。希望下一份工作是把模型接进真实业务流程，而不是停在演示。

导师：孙湛博（交通运输学院副院长） · 学业奖学金 × 2 · CET-6

## 技术关注

| 方向 | 具体内容 |
| --- | --- |
| 大模型与 Agent | Transformer；SFT、LoRA、QLoRA；Embedding 与 Function Calling；ReAct、Memory、MCP / Skills；Prompt 与 HITL |
| 检索 | RAG 全链路优化；RAGAS 评估；ChromaDB、Milvus |
| 框架 | PyTorch、LlamaFactory、LangGraph、LangChain、AutoGen、vLLM、Pandas、NumPy |
| 工程 | Python、FastAPI、Docker、Git、Linux / PowerShell；Cursor、Claude Code |

## 实习

### AI 算法工程师 · 北京经纬恒润科技股份有限公司

2026.07 — 2026.09 · 上市公司 · 硬件设计自动化

围绕企业私有硬件知识库和设计数据，用 Agent 减少工程师的重复操作。

- 处理 PDF 跨页表格、Excel 合并单元格、PNG 等异构文档：格式路由加语义分块，用 RAGAS 做评估，并用 FastAPI 封装 MCP / Skills / CLI。知识库综合召回率从 82% 提到 93%。
- 用 LangGraph 优化 EDIF 驱动的电源树和功能模块框图，处理芯片关系追踪和模块重叠，并加入人工校验闭环。上线后任务完成度 95%。
- 针对 ICD 引脚命名不规范、多义命名和拓扑矛盾，做引脚推断 Agent，调用正则、datasheet、EDIF 拓扑和历史 ICD 消歧。工程师校验回流到共享记忆，规则覆盖率随使用增长。上线任务完成度 92%。

## 项目

### [智能旅游咨询与行程规划 Agent](https://github.com/HOUDINI1314/smart-travel-agent)

2026.03 — 2026.06 · Python · LangGraph · 开源

开放域咨询走 ReAct，行程规划走固定主链路：分类、意图、补槽、天气、POI、路线、行程、校验、导出。行程规划完成率 92%。

云端用通义千问做复杂规划；本地用 LlamaFactory 对 Qwen2.5-1.5B-Instruct 做 QLoRA 微调，再用 vLLM 部署，专门做意图识别和槽位抽取。意图链路 P95 降到 180ms，入口 Token 成本下降 42%。工具侧接了高德、联网检索和本地 RAG，并做了多层 Memory。工具调用成功率 87%，RAG 召回率 95%、准确率 82%。

### [DietCoach](https://github.com/HOUDINI1314/DietCoach)

Kotlin · Jetpack Compose · Qwen · 开源

面向 OriginOS 的饮食与训练记录。本地统计三大营养素、有氧和力量消耗、热量缺口；用通义千问做一句话记餐、拍照识餐和针对个人数据的助手。这个是我的减肥助手的演示视频，感兴趣的面试官也可以看看：https://www.bilibili.com/video/BV1oAuS6dE4R/?spm_id_from=333.1387.homepage.video_card.click&vd_source=a27efab372adbf20f4426f4f0769617d

### 多车轨迹预测对抗攻击检测

2025.09 — 至今 · 研究

打通 NGSIM / Apolloscape 上「数据处理 — 神经网络训练 — 对抗攻击复现 — 检测修复」流程。复现基于 GAT / FQA / GRIP 的物理约束攻击，并做双模型一致性检测。强约束场景 F1 0.95，隐匿攻击 ROC-AUC 0.84，攻击源定位成功率 87%，修复后 RMSE@3s 为 0.21m。

### 共享电动汽车多模式充电网络优化

2024.09 — 2026.03 · 发明专利 202511736948.8

从 GPS 轨迹里提取行程和补能事件，识别需求的时空分布；用层次聚类和 DBSCAN 生成固定站、移动站候选网络；以建设成本和平均延误为双目标，用 NSGA-II 求帕累托解并和基准方案比较。

## 教育

| 时间 | 学校 | 专业 | 学位 |
| --- | --- | --- | --- |
| 2024.09 — 2027.06 | 西南交通大学（211 / 双一流） | 交通运输（A+，学科评估全国第一） | 硕士 |
| 2020.09 — 2024.06 | 西南交通大学（211 / 双一流） | 数学与应用数学 | 学士 |

## 联系

代码与演示见 [smart-travel-agent](https://github.com/HOUDINI1314/smart-travel-agent) 和 [DietCoach](https://github.com/HOUDINI1314/DietCoach)。
