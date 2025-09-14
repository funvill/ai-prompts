
# 🧪 Step 5: Prototyping & Implementation

## 🎯 Primary Goal of Step 5

To begin development by first **validating key technical risks** through targeted prototypes or spikes, and then proceeding to **implement MVP features** as defined in the PRDs.

This phase ensures that the most uncertain or risky components are explored early, while the team builds the application in controlled, testable increments.

## 🧩 Key Objectives

| Objective | Description |
|----------|-------------|
| **Risk Reduction** | Address unknowns or difficult components early through isolated prototypes. |
| **Incremental Implementation** | Build features in small, verifiable steps tied directly to their PRDs. |
| **Integration Management** | Start wiring together major components according to the architecture. |
| **Maintainability & Patterns** | Establish clear code structure and standards from day one. |

## ❓ Key Questions to Ask

### 🧪 Prototype & Spike Focus
- What parts of the system have the most technical uncertainty?
- Can we validate assumptions quickly without full implementations?
- What are the exit criteria for each prototype?

### 🔧 Development Strategy
- What is the first feature or component to implement?
- Are there shared libraries/utilities that should be built early?
- How will we track implementation progress against PRDs?

### 🧹 Code Quality & Maintainability
- What folder structure, naming conventions, and design patterns will we use?
- How will developers know how to write maintainable code?
- When and how will we write tests (unit/integration)?

## 👥 Participating Roles (4 of 10)

| Role | Description | Step 5 Responsibilities |
|------|-------------|--------------------------|
| **Senior Developer** | Leads prototyping and early implementations. Ensures foundational code quality and guides less experienced devs. | - Build technical spikes to test assumptions<br>- Implement core MVP features<br>- Define reusable modules and service boundaries |
| **System Designer** | Monitors fidelity of implementation to architecture. | - Assist with API/interface consistency<br>- Suggest better modular boundaries<br>- Refactor if needed to preserve system design |
| **Software Architect** | Oversees architectural integrity and tech decisions. | - Review early implementations<br>- Approve architecture adaptations<br>- Maintain separation of concerns |
| **Project Planner** | Tracks execution, removes blockers, adjusts timelines. | - Align development with PRDs<br>- Monitor velocity and cross-team dependencies<br>- Facilitate daily or weekly check-ins |

## 📝 Deliverables

| File | Contributed by | Description |
|------|----------------|-------------|
| `05_spikes/<topic>.md` | Senior Developer (lead) | Outcomes of experimental prototyping efforts (e.g. protocol handling, performance tests) |
| `src/` | Senior Developer | Initial implementation of MVP features |
| `tests/` | Senior Developer | Unit and integration tests for completed modules |
| `04_prds/feature_<name>.md` | All roles | PRDs updated with development notes, surprises, or refinements |
| `01_vision_logbook.md` | All roles | Architecture deviations, tech decisions, and planning updates |

## ✅ Exit Criteria

- Risky components have been prototyped and findings documented
- MVP features are implemented and traceable to PRDs
- Core services, modules, and interfaces are in place
- Code is clean, modular, and includes foundational tests
- Early feedback or self-testing reveals a usable (but incomplete) product
