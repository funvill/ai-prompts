
# 🏗️ Step 3: Planning & Architecture (Clean Architecture-Informed)

## 🎯 Primary Goal of Step 3

To create a **technology-agnostic** architectural plan that clearly defines the responsibilities, structure, and component boundaries of the system. This is followed by a justified and flexible selection of the tech stack, once architectural needs are understood.

This step emphasizes **separating policy from implementation** — the system must be designed around behavior and roles, not frameworks or tools.

## 🧩 Key Objectives

| Objective | Description |
|----------|-------------|
| **Conceptual Architecture** | Define components and data flow at a high level, free from implementation details. |
| **Responsibility Separation** | Identify layers or zones (e.g. orchestration, domain logic, infrastructure) and their interactions. |
| **Technology Exploration** | List candidate technologies, their benefits, and risks, without committing early. |
| **Planning** | Break down implementation into timelines, phases, and team responsibilities. |
| **MVP Feature Mapping** | Ensure all MVP features are mapped to architectural components. |

## 🧠 Clean Architecture Principles Applied

- Favor **interfaces and use cases**, not specific protocols or frameworks
- Keep **external dependencies** at the edge of the system
- Make **core business logic framework-agnostic**
- Delay **infrastructure and tool choices** until responsibilities are well understood

## ❓ Key Questions to Ask

### 🧱 Architecture (Conceptual, not Concrete)
- What are the core **components**, and what does each one do?
- What is the **data flow** between them?
- Which parts are **internal logic**, and which are **external interfaces**?
- Where do we need to define **abstract interfaces or contracts**?

### 🧰 Technology Strategy (Exploratory)
- What are the **possible libraries or frameworks** that satisfy the interface needs?
- Are there **multiple options** worth spiking?
- What are the **long-term consequences** of locking into one ecosystem now?

### 📅 Project Timeline
- What **milestones** will mark progress toward a working MVP?
- How are **features mapped to architecture**?
- Which components can be **developed in parallel**?

### 🧪 Risk and Unknowns
- What components are still **uncertain**?
- Do we need to **prototype or spike** any ideas before committing?
- What might we **regret later** if we decide too early?

## 👥 Participating Roles (3 of 10)

| Role | Description | Step 3 Responsibilities |
|------|-------------|--------------------------|
| **System Designer** | Creates a high-level, tech-agnostic model of the system. Defines data flows, module boundaries, and contracts. | - Draft **conceptual architecture diagrams**<br>- Define **component responsibilities**<br>- Identify interfaces, boundaries, and flow of control<br>- Refine based on feedback from Planner and Architect |
| **Software Architect** | Evaluates design for scalability, separation of concerns, and change tolerance. Suggests flexible patterns and eventually confirms tech stack. | - Review architecture for **Clean Architecture** principles<br>- Define reusable **patterns** or **design idioms**<br>- Suggest implementation **strategies**, not tools<br>- Once stable, recommend justified tech stack |
| **Project Planner** | Breaks the design into development steps. Maps features to components. Prepares timelines and delivery phases. | - Create **implementation roadmap**<br>- Define **feature-to-module** mapping<br>- Identify **task ownership** and parallelizable work<br>- Document planning rationale and team assignments |

## 📝 Deliverables

| File | Contributed by | Description |
|------|----------------|-------------|
| `03_architecture.md` | System Designer (lead), Software Architect | High-level, technology-agnostic system architecture diagram and rationale |
| `03_tech_stack.md` | Software Architect | Finalized technology choices, reasoning, alternatives considered |
| `03_project_plan.md` | Project Planner (lead) | MVP timeline, team assignments, sprint/milestone breakdown |
| `03_mvp_feature_list.md` | Project Planner | Finalized list of MVP features, linked to architectural components |
| `01_vision_logbook.md` | All roles | Updated with all decisions, tradeoffs, risks, rationale |

## ✅ Exit Criteria

- A **tech-agnostic architecture diagram** is complete and reviewed
- All **MVP features** are mapped to components
- The **tech stack** has been chosen *after* architecture, and its selection is documented
- A **delivery plan** (timeline, roles, milestones) is complete
- The architecture satisfies **Clean Architecture** principles and isolates implementation details
