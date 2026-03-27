<div style="text-align: center;">
  <h1 style="color:#1f883d; font-weight:900; font-size:2.5em; text-shadow: 0 0 8px rgba(211, 231, 211, 0.5);">MicroWind | AI 编程核心知识库</h1>
  <p style="color:#FF6600; font-size:2em; font-weight:500;">
      <a href="https://github.com/microwind/algorithms" style="color:#FF6600; text-decoration:none;">算法思想</a> ·
      <a href="https://github.com/microwind/design-patterns" style="color:#FF6600; text-decoration:none;">设计模式</a> ·
      <a href="https://github.com/microwind/ai-prompt" style="color:#FF6600; text-decoration:none;">Prompts</a> ·
      <a href="https://github.com/microwind/ai-skills" style="color:#FF6600; text-decoration:none;">Skills</a>
  </p>
</div>

---

## AI 编程时代发展历程

> AI能替代编码，无法替代思考；提升思想与认知，是驾驭 AI 的核心竞争力。 

```mermaid
%%{init: {'flowchart': {'nodeSpacing': 30, 'rankSpacing': 30, 'padding': 10}}}%%
graph LR
%% ===== 时间线主线 =====
P(["2023以前<br/>传统模式"]) --> Q(["2023-2024<br/>Copilot模式"]) --> R(["2025+<br/>Agent模式"]) --> S(["2026+<br/>Agentic模式"])

%% ===== 核心能力纵向显示 =====
P1("手写代码<br/>实现功能<br/>角色：执行者")
Q1("L1 AI Copilot<br/>辅助编码<br/>角色：增强执行")
R1("L2 AI Agent<br/>指导AI<br/>角色：指挥者")
S1("L3 Agentic AI<br/>驱动AI<br/>角色：决策者")

P --> P1
Q --> Q1
R --> R1
S --> S1

%% ===== 主节点样式 =====
style P fill:#666666,stroke:#282A2D,color:#ffffff,stroke-width:2px,rx:12,ry:12
style Q fill:#FF6600,stroke:#c94c4c,color:#ffffff,stroke-width:2px,rx:12,ry:12
style R fill:#6a5acd,stroke:#1D4ED8,color:#ffffff,stroke-width:2px,rx:12,ry:12
style S fill:#11908A,stroke:#15803D,color:#ffffff,stroke-width:2px,rx:12,ry:12

%% ===== 子节点样式 =====
style P1 fill:#E6E8EB,stroke:#90959D,color:#15181E,rx:10,ry:10
style Q1 fill:#FDE2DF,stroke:#F59E0B,color:#78350F,rx:10,ry:10
style R1 fill:#F2E7FA,stroke:#7C04AB,color:#1E3A8A,rx:10,ry:10
style S1 fill:#C2F8F1,stroke:#23B659,color:#14532D,rx:10,ry:10
```

## AI 编程核心能力矩阵

> 表层的 API、开发框架日新月异，而算法思想、设计模式、底层逻辑历久弥新。

```mermaid
%%{init: {'flowchart': {'nodeSpacing': 40, 'rankSpacing': 40, 'padding': 15}}}%%
graph TD
    A(AI时代程序员核心能力) --> B[算法思想与数据结构]
    A --> C[设计模式与架构思想]
    A --> D[AI提示词工程]
    A --> E[AI编程Skills库]
    
    B --> F[驾驭AI的底层根基]
    C --> F[驱动AI的架构思维]
    D --> F[高效协作AI的工具]
    E --> F[AI全面技能体系]
    
    F --> G[从执行者 -> 指挥者 -> 决策者]

    %% 主节点
    style A fill:#615C5C,stroke:#ccc,color:#fff,stroke-width:2px,rx:12,ry:12
    %% 核心能力节点
    style B fill:#E75E19,stroke:#ccc,color:#fff,rx:10,ry:10
    style C fill:#1656BC,stroke:#ccc,color:#fff,rx:10,ry:10
    style D fill:#C66D01,stroke:#ccc,color:#fff,rx:10,ry:10
    style E fill:#048D54,stroke:#ccc,color:#fff,rx:10,ry:10
    %% 汇总能力节点
    style F fill:#0550C2,stroke:#ccc,color:#fff,rx:12,ry:12
    %% 最终能力发展节点
    style G fill:#722C9D,stroke:#ccc,color:#fff,stroke-width:1px,rx:12,ry:12
```
---

## AI 编程四大核心仓库

### 1.  [algorithms](https://github.com/microwind/algorithms)| 算法思想与数据结构

> 理解算法与数据结构，指导AI做出合理决策。

- 覆盖数值计算、字符查找、树遍历、排序、动态规划等
- C/Java/Python/JS/Go/TypeScript/Rust 多种语言实现
- 注释详尽、例子递进，兼顾算法原理与编程语言特性

👉 [github.com/microwind/algorithms](https://github.com/microwind/algorithms)

### 2.   [design-patterns](https://github.com/microwind/design-patterns) | 设计模式与架构思想

> 理解设计模式与架构思想，让AI写出有灵魂的代码

- 经典设计模式 + 编程范式详解 ，结合实际场景
- 支持 C/Java/JS/Python/Go 多语言实现  
- 持续完善，打造 AI 时代架构思维库

👉 [github.com/microwind/design-patterns](https://github.com/microwind/design-patterns)

### 3.  [ai-prompt](https://github.com/microwind/ai-prompt) | 程序员 Prompt Engineering 知识库

> 14 大场景提示词，让AI成为你的得意助手

- 覆盖软件开发全流程的 AI 协作指南  
- 适配 Claude Code、Codex、OpenClaw
- 提示词实践，提高工作效率

👉  [github.com/microwind/ai-prompt](https://github.com/microwind/ai-prompt)

### 4.  [ai-skills](https://github.com/microwind/ai-skills) | AI 编程 Skills 知识库大全

> 100 + 结构化技能库，用AI学习编程技术

- 为程序员量身打造的 AI Skills 体系  
- 涵盖流行框架、工具、实战技巧  
- AI 精准匹配技能需求，高效辅助开发

👉 [github.com/microwind/ai-skills](https://github.com/microwind/ai-skills)

---

## 核心愿景

> **AI时代，做AI驱动者，不做代码搬运工**

**本仓库旨在帮助大学生和程序员朋友：**

1. 掌握核心思想，筑牢底层认知，驾驭 AI 而非被 AI 替代
2. 掌握高效协作 AI 的方法，让 AI 成为核心生产力
3. 从 **代码执行者** 到 **AI指挥者** 再到 **AI决策者**


---

## 相关链接

- [AI编程时代，为什么35岁以上程序员会更吃香？](https://github.com/microwind/algorithms/blob/main/start-here/Why-Programmers-35-Plus-Are-Thriving-in-AI-Era.md)
- [AI时代，人人都是AI Agent工程师](https://github.com/microwind/algorithms/blob/main/start-here/AI-Era-Programmers-as-Agent-Engineers.md)
- [AI时代，人人都是需求描述工程师](https://github.com/microwind/algorithms/blob/main/start-here/AI-Era-Programmers-as-Requirements-Engineers.md)
- [AI时代，人人都是系统设计工程师](https://github.com/microwind/algorithms/blob/main/start-here/AI-Era-Programmers-as-System-Design-Engineers.md)
- [AI时代，人人都是算法思想工程师](https://github.com/microwind/algorithms/blob/main/start-here/AI-Era-Programmers-as-Algorithmic-Thinkers.md)

---

## 🌟 欢迎共建

`仓库：` https://github.com/microwind

如果您对本项目感兴趣请加我，欢迎一起共建！

 If you are interested in this project, please add me. I welcome you to build it together!

我是Jarry 李春平, 一个20年互联网工程师

- 📧 mail: `jarryli@gmail.com` or `lichunping@buaa.edu.cn`
- 💬 wechat: `springbuild`
- 🌟 如果这个项目对你有帮助，请给个 Star 支持一下！
