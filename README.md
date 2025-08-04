# edca-core

**Expression-Driven Cognitive Architecture**  
*A Protocol Layer for Agent Execution*

---

## 🔍 What is EDCA?

EDCA（表达驱动认知架构）是一种**以语言表达为主控路径**的 AI 协同框架，旨在替代当前流行但伪智能的“工作流式 Agent”，构建真正具备**路径理解 + 响应分配 + 控制协议**能力的 AI 协作系统。

它不是提示词堆砌，不是流程脚本，而是一种**“表达即协议”的认知执行系统设计方法论”**。

---

## 🎯 Why EDCA? · 为什么我们需要它

> “Current agents pretend to be smart by running workflows. EDCA builds smart agents by understanding your expression.”

当前主流AI代理结构（如“写周报的Agent”、“总结会议的Agent”）大多基于**工作流**封装：
- 响应路径固定
- 行为不可协商
- 用户表达被忽视，只剩表单参数

而 EDCA 的目标是：
- 让语言本身成为任务分发协议
- 让表达路径驱动模块响应与切换
- 在执行过程中动态计算“谁该说话”、“谁该沉默”

---

## 🧩 Core Design | 核心设计理念

- **表达驱动（Expression-Driven）**：不再依赖流程定义，而以自然语言构建任务路径。
- **响应权重偏移机制（Response Weight Shift）**：多个模块监听同一输入，动态判定主导模块。
- **多路径推理链（Multi-Path Reasoning Chain）**：根据表达意图结构，激活不同的行为链路。
- **语义熔断（Semantic Interrupt）**：当执行偏离目标或用户表达变化，可中断当前路径转向新路径。
- **模块解耦（Agent Modularization）**：通过协议调度不同功能模块，实现结构化协同。

---

## 📐 Project Structure | 项目结构

/docs
└─ EDCA_PROTOCOL.md ← 协议规范文档（进行中）

/arch
└─ edca-overview.svg ← 架构图（准备上传）

README.md ← 本说明文档
LICENSE ← MIT开源协议

---

## 🌐 For Who? | 适合谁使用与参考

- 构建 AI Agent 的开发者
- 设计协作式系统的架构师
- 想摆脱提示词依赖的高级用户
- 对认知路径、语言协议感兴趣的研究者

---

## 🔓 License

This project is licensed under the [MIT License](LICENSE).

---

## 📎 Coming Soon

- [x] `EDCA_PROTOCOL.md` (v0.1)
- [ ] 架构图上传
- [ ] 使用案例：构建具有主动判断能力的中控代理
- [ ] Python伪代码样例

---

> **“表达即控制，语言即协议。”**  
> EDCA is not just a design — it's a reclaim of expression-driven agency in the age of AI.
