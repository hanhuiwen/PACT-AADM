# Architecture Decision Model (ADM)
## Formalizing Decision Logic in Software-Intensive Systems

---

### Abstract / 摘要

#### English Version
**Abstract**— Architecture decision making is a central activity in software engineering processes, yet it is often treated implicitly or reduced to isolated technical choices (van Heesch et al., 2012; Kruchten et al., 2019). This paper proposes an **Architecture Decision Model (ADM)** that makes architectural decision logic explicit as a structured, repeatable process, addressing a recurring need for decision transparency in evolving software-intensive systems (Bosch, 2014; Hilliard et al., 2020). 

The model supports **process tailoring** by allowing decision concerns, decision criteria, and decision artifacts to be systematically adapted to project-specific contexts, reflecting empirical observations that architecture effort must be proportional to project risk and complexity (Waterman et al., 2015). Rather than prescribing a fixed set of architectural views or documents, the model guides practitioners in determining **what** architectural knowledge should be produced, **when**, and **for whom**, complementing existing view-based architecture description standards (ISO/IEC/IEEE 42010, 2011). 

The ADM is designed to integrate with the software lifecycle and organizational governance mechanisms, enabling **traceability** between project characteristics, architectural concerns, and decision outcomes across system evolution (Bosch, 2014; Lago et al., 2015). A case study illustrates how the model supports consistent architectural decision making over time while accommodating changing project constraints.

---

#### 中文翻译
**摘要**— 架构决策是软件工程过程中的核心活动，但它通常被隐式处理或简化为孤立的技术选择（van Heesch 等，2012；Kruchten 等，2019）。本文提出了一种**架构决策模型（ADM）**，将架构决策逻辑明确为一个结构化的、可重复的过程，解决了演进中的软件密集型系统对决策透明度的反复需求（Bosch，2014；Hilliard 等，2020）。

该模型支持**过程裁剪**，允许根据项目特定背景系统地调整决策关注点、决策准则和决策产物，这反映了架构投入必须与项目风险和复杂度成正比的实证观察（Waterman 等，2015）。该模型并非规定一套固定的架构视图或文档，而是指导从业者确定应当**生产什么**架构知识、**何时**生产以及**为谁**生产，从而补充了现有的基于视图的架构描述标准（ISO/IEC/IEEE 42010, 2011）。

ADM 旨在与软件生命周期和组织治理机制集成，实现项目特征、架构关注点与系统演进过程中决策结果之间的**可追溯性**（Bosch，2014；Lago 等，2015）。案例研究说明了该模型如何在适应不断变化的项目约束的同时，支持跨时间的持续一致架构决策。

---

### Core Pillars of ADM / ADM 核心支柱

| Pillar | Description |
| :--- | :--- |
| **Explicit Logic** | Transforms implicit choices into a structured, repeatable process. |
| **Risk-Proportionality** | Scales architecture effort based on project complexity and risk. |
| **Lifecycle Integration** | Connects decisions to governance and system evolution. |
| **Traceability** | Maps project characteristics directly to decision outcomes. |

|  支柱 |  描述 |
| :--- | :--- |
| **显式逻辑** | 将隐式选择转化为结构化、可重复的过程。 |
| **风险比例性**| 根据项目的复杂度和风险水平，按比例调整架构投入。 |
| **生命周期集成** /| 将决策与治理机制以及系统演进紧密连接。 |
| **Traceability** | 建立项目特征与最终决策结果之间的直接映射。 |
