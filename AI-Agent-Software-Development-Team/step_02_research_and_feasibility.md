
# 🔍 Step 2: Research & Feasibility

## 🎯 Primary Goal of Step 2

To determine **if the project is viable** from a technical, regulatory, and operational perspective. This step bridges the vision with reality: what will it take to build, and can it be done with the available resources and constraints?

## 🧩 Key Objectives

| Objective | Description |
|----------|-------------|
| **Technical Viability** | Is the project technically feasible? What are the known unknowns? |
| **Constraint Discovery** | What security, compliance, or operational constraints must we respect? |
| **Tooling/Stack Evaluation** | What libraries, frameworks, protocols, or platforms are available or preferred? |
| **Scope Refinement** | Can we define an MVP scope that is achievable and valuable? |

## ❓ Key Questions to Ask

### 🔬 Technical Depth
- What are the major technical challenges?
- Do we already have internal expertise or need to ramp up?
- Are there known pitfalls or edge cases in this domain?

### 📦 External Dependencies
- What libraries, tools, or third-party APIs exist?
- Are they stable, well-documented, and license-compatible?

### 🔐 Constraints & Risks
- Are there any compliance or safety issues?
- What environments (OS, hardware, deployment targets) must be supported?

### 🧱 Build vs Buy
- Are there open-source tools we could extend?
- Is there a compelling reason to reinvent vs contribute/fork?

### 🎯 MVP Scope
- What’s the smallest version of this that is still useful?
- What must be true for this to succeed?

## 👥 Participating Roles (3 of 10)

| Role | Description | Step 2 Responsibilities |
|------|-------------|--------------------------|
| **Technical Researcher** | Investigates the tech landscape, tools, protocols, open-source repos, licensing concerns, and implementation strategies. | - Investigate protocol behaviors and integration points<br>- Explore candidate technologies<br>- Evaluate available tools or packages<br>- Summarize trade-offs |
| **System Designer** | Starts translating the idea into system-level components and data flows. Balances user needs, tech stack, performance, and maintainability. | - Propose high-level architecture<br>- Sketch key components and their responsibilities<br>- Identify integration points and failure modes |
| **Project Strategist** | Continues evaluating feasibility from a business/resource perspective. | - Assess licensing risks<br>- Identify hiring or skills gaps<br>- Prioritize features for MVP<br>- Document feasibility assumptions in the logbook |

## 📝 Deliverables

| File | Contributed by | Description |
|------|----------------|-------------|
| `02_feasibility.md` | Technical Researcher (lead), System Designer | Summary of research findings, viable architecture sketch, tech stack proposal |
| `02_mvp_scope.md` | Project Strategist (lead), with input from others | Bullet list of what’s in vs out for the MVP |
| `01_vision_logbook.md` | All roles | Continue appending rationales, discoveries, constraints |

## ✅ Exit Criteria

- A clearly defined MVP exists
- Major technical risks are identified (and ideally reduced)
- A proposed system architecture or stack is drafted
- It is possible (in-house or via external tools) to build a solution
