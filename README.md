# Acid Black (`@theacidblack`)

> **Python software engineer focused on building clean, deterministic, and highly maintainable systems.**
> I bridge the gap between high-level project briefs and production-ready prototypes with rigorous architectural standards, moving fluidly from conceptual userflows to strict, test-driven implementations.

---

## 🛠️ Local Environment & Tech Stack

* **Core Language:** `Python` (Advanced backend architecture, automated testing, systems integration)
* **GUI Framework:** `PyQt6` (Desktop application development)
* **Inference Infrastructure:** LM Studio, Ollama, llama.cpp + turboquant, Docker, self-hosted MCP servers
* **IDE & Agentic Tooling:** VS Code equipped with Cline and Zoo Code extensions; also experimenting with Hermes, n8n, and ComfyUI

---

## 🤖 Self-Hosted Models

1. **Qwen 3.6 35B 128k tokens UD-Q4**
* Main architecture for reasoning, planning, execution, audits, and documentation. Can burn over 5M+ tokens in one run without issue.


2. **Qwen3 Coder Next 80B 128k tokens UD-Q3**
* Restricted to executing structured plans only. Can seamlessly burn over 5M+ tokens in a single run.


3. **Qwen3.5 9B Q4-Q5 32-185k token variants**
* Mainstay for rapid iteration, git-style diffs, and binary vision (yes/no) logic. Best 9B model family ever released.


4. **SDXL**
* For ComfyUI



---

## 🔄 Engineering Workflow

* **Deterministic Engineering:** Utilizing low-temperature inference constraints (0.2) to ensure structural rigidity, stable logic, and predictable code layout generation.
* **Dual-Model Agentic Pipeline:** An isolated local 35B reasoning model parses project documentation to establish structured execution plans, which are then programmatically processed and executed via the 80B Coder model.
* **Strict Pylance Enforcement:** Eliminating runtime vulnerabilities statically. Why allow errors when they can be completely prevented?
* **Architectural Blueprinting:** Rigid adherence to the Single Responsibility Principle (SRP), clear boundary modularity, robust userflow documentation, and comprehensive unit testing. Zero god files tolerated.

---

## 📁 Current Projects

* **Local Token & Inference Monitor** `(Upcoming Open-Source / MIT License)`
* A standalone Windows desktop application built with PyQt6 to track token utilization, real-time throughput analytics, and performance cost-efficiency across local LM Studio instances.


* **Modular Active Pipeline**
* 5 ongoing personal projects focused on evaluating diverse integrations and libraries. Designed with strict modularity to allow seamless plug-and-play component reuse.
