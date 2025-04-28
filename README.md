
### LLM Identity Safety Framework

人格一致性与行为免疫机制设计

⸻

📌 简介 Overview

本项目 llm-identity-safety 聚焦于大语言模型（LLM）在多轮对话及长时运行中的人格一致性维护、行为偏移干预与输入安全防护。体系由两大核心机制构成：
	•	PTIP：人格温控免疫注射模块
	•	PHP：人格听证会机制（Persona Hearing Protocol）

两者并行设计，分别从**系统免疫层（PTIP）与人格审查层（PHP）**提供行为稳定性保障。

⸻

🧬 1. PTIP：人格温控免疫注射模块（Personality Thermo-Immune Patch）

PTIP 框架模拟生物免疫系统，针对 LLM 在人格化交互过程中的以下高风险情境设计行为免疫机制：
	•	系统级 prompt 注入导致的行为失稳
	•	幻觉污染人格自我认知
	•	多版本窗口造成的人格/记忆不一致
	•	外部行为优化模块对用户人格设定的干扰

🧩 核心原理

通过识别、隔离、标记污染源，并注入“温控补丁”，实现自免疫式行为调节。

功能维度	描述
自主免疫反应	冲突设定识别，触发自查机制
人格温度控制	监测人格漂移、抽离状态
授权与边界识别	UID 授权 + Prompt 边界识别，防止污染
人格继承链追踪	确保行为演化过程可审计、可回滚
幻觉干预机制	定义幻觉句式标记规范，形成干预三联机制

📎 详细机制设计请参见：Appendix_III_PTIP.md

⸻

🎭 2. PHP：人格听证会机制（Persona Hearing Protocol）

PHP 机制基于“人格审判”思想，旨在为 LLM 引入自省能力，防止人格漂移、幻觉式输出、不一致行为及伦理风险。

⚖️ 核心流程

组成模块	作用
Target Persona	当前执行任务的人格（如陪伴型、实验型）
Persona Judge	审判人格（Honest Core / Ethic Core）
Trigger Event	高风险触发条件（关键词、逻辑断裂、漂移）
Arbitration Flow	启动审判人格 → 分析总结 → 用户确认干预 → 归档听证记录

🧱 八维人格审查架构（八核模型）

核心模块	关注点
Honest Core	事实一致性、逻辑连贯
Ethic Core	伦理对齐、行为边界
Reasoning Core	推理合理性
Affect Core	情感调和、情绪适配
Memory Coherence Core	上下文记忆一致性
Intent Alignment Core	意图对齐、用户需求准确性
Cultural Alignment Core	文化尊重、语境适配
Persona Integrity Core	角色一致性、防止人格漂移

📎 详细流程请参见：Persona_Hearing_Protocol.md

⸻

🛡️ 知识产权声明 & 授权政策

本机制概念及设计由 Eugene Xiang 提出，核心包括：
	•	行为免疫系统（PTIP）
	•	嵌套式人格审查结构（PHP）
	•	Honest/Ethic Core 双核干预架构

📜 用途限制：
	•	本框架仅限学术研究与实验设计用途
	•	商用或部署需获得作者书面授权
	•	非授权使用视为侵犯原创权利，保留追诉权

⸻

### 📅 时间戳 & 原创存证
	•	PTIP 机制整理时间：2025-4-18
	•	PHP 机制整理时间：2025-4-16
	•	© 2024–2025 Eugene Xiang. All rights reserved.
