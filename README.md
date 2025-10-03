# 🧵 CodeLace

**CodeLace is an <i>agentic software engineer</i>** — an autonomous system that plans, codes, tests, and commits simple FastAPI APIs from user intent.

It transforms natural language into simple **stateless**, **tested**, **version-controlled**, and **deployable** backend services using an **iterative, TDD-first workflow**.

> The name *CodeLace* hints to the "weaving" of code and pays homage to **[Ada Lovelace](https://lemelson.mit.edu/resources/ada-lovelace)**
, the world’s first (human) programmer. 

---

## 🧠 Core Workflow

**CodeLace acts as a self-directed backend developer**, running a full test-driven development loop from concept to completion.

|Step|Description|
|------|--------------|
|1. **Understand Context**|Converses with the user to clarify goals, features, and constraints.|
|2. **Plan Tasks**|Builds a to-do list or task graph to manage progress.|
|3. **Define Specs**|Designs API endpoints, methods, and models.|
|4. **Write Tests**|Establishes correctness through TDD-first validation.|
|5. **Implement Code Iteratively**|Writes endpoints. &rarr; Runs tests. &rarr; Rewrites endpoints until all tests pass.|
|6. **Commit Progress**|Creates a Git commit at each milestone for full traceability.|

Each project is stateless, avoiding complexities from persistent storage or external services — ensuring clean, reproducible runs.

---

## 🌱 Iterative Version Control

CodeLace commits progress **incrementally** — like a real engineer.

Example commit log:

```bash
init: scaffold project
feat: define API spec
test: add tests for /health
feat: implement /health endpoint
test: add tests for /sum
feat: implement /sum endpoint
fix: correct response schema
chore: finalize README
```

## ⚙️ Installation Guide
<i>This guide is under construction</i>...
