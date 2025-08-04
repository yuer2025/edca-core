1.0  Core Concept: Expression-Driven Execution
2.0  System Overview and Agent-Oriented Architecture
3.0  Expression Parsing & Intent Resolution Layer
4.0  Response Weighting and Module Arbitration
5.0  Semantic Interrupt & Path Correction
6.0  Multi-Path Reasoning Chain Construction
7.0  Protocol Lifecycle: From Input to Resolution
8.0  Appendix: Glossary & Implementation Notes

# EDCA_PROTOCOL.md

## 1.0 Core Concept: Expression-Driven Execution

### 1.1 Motivation

Traditional “AI Agents” often rely on pre-defined workflows, static chains of prompts, or rigid APIs that assume user intent is known, explicit, and stable.  
This assumption fails under real human interaction, where intent is layered, shifting, and often implicit.

**EDCA proposes a fundamental shift:**
> Treat human expression not as a query, but as an execution protocol — capable of driving, interrupting, and modifying behavior.

---

### 1.2 Definitions

- **Expression**: Any natural language input from a user, whether complete or partial, implicit or direct.
- **Protocol**: A logical execution pathway derived from the expression, which governs how agents respond.
- **Cognitive Unit (CU)**: A semantic entity extracted from expression, used to activate modules or switch paths.
- **Module**: A functional agent, capable of interpreting CUs and responding if selected by arbitration.
- **Response Arbitration**: The mechanism by which competing modules assign weight to a CU and negotiate control.
- **Interrupt Trigger**: A secondary expression or shift in semantic signal that forcibly re-evaluates current path ownership.

---

### 1.3 Core Assumptions

1. **There is no “fixed workflow.”**  
   Every interaction is path-determined by the user’s expression.

2. **Modules do not execute blindly.**  
   They compete, adapt, and yield based on semantic priority and path weight.

3. **Expression is a living protocol.**  
   It evolves as the user speaks — modifying control states and pushing execution forward.

---

### 1.4 Conceptual Summary (Human-AI Cooperation View)

- You express → System parses expression → CU formed → Modules weight CU → Winner executes
- You re-express → System triggers semantic interrupt → Arbitration resets → New module path activated
- You stay silent → Active path continues unless timed decay or watchdog module intervenes

---

### 1.5 Quote

> “A protocol is not a format. It is a behavior contract written in language.”  
> — EDCA, V0.1
