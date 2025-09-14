
# 🧑‍💼 Role Reference Guide: Responsibilities, Questions, and Step-by-Step Involvement

This document summarizes all roles used in the 9-step software development process. For each role, it includes:

- **Core responsibilities**
- **Key questions they ask**
- **What they need (inputs)** from each step

---

## 🎯 1. Visionary

**Responsibilities:**
- Define the high-level product vision and emotional goals
- Communicate the "why" and long-term value
- Inspire the team and users

**Typical Questions:**
- Why does this product need to exist?
- Who is it for and how will it improve their life?
- What’s the bigger story or outcome?

**Step-by-Step Needs:**
- Step 1: Initiate problem framing and idea sketch
- Step 2–3: Provide vision-based input on feasibility and planning
- Step 6–7: Review user alignment and value realization
- Step 9: Ensure final product reflects original vision

---

## 🧭 2. Project Strategist

**Responsibilities:**
- Evaluate alignment with business goals and market fit
- Perform prior art research and competitor analysis
- Guide trade-offs based on risk and return

**Typical Questions:**
- What’s the ROI of this feature?
- Are we duplicating something that exists?
- Is this worth our time and resources?

**Step-by-Step Needs:**
- Step 1–2: Lead strategic framing and risk discovery
- Step 3: Participate in scoping MVP
- Step 4: Ensure PRDs tie back to value
- Step 9: Reflect on business outcomes and lessons

---

## 🙋 3. User Advocate

**Responsibilities:**
- Represent user pain points and experience
- Guide usability and user validation
- Convert feedback into actionable improvements

**Typical Questions:**
- What would a real user do here?
- Where might someone get confused or frustrated?
- What feedback patterns are emerging?

**Step-by-Step Needs:**
- Step 1: Validate real-world value
- Step 4: Help shape user-facing requirements
- Step 6–7: Gather and analyze feedback
- Step 8–9: Prioritize user pain points

---

## 🔬 4. Technical Researcher

**Responsibilities:**
- Explore protocol specs, tooling, and implementation techniques
- Investigate third-party tools and licensing
- Report risks and technical tradeoffs

**Typical Questions:**
- What are the available tools or frameworks?
- What do we need to build vs reuse?
- Are there known technical pitfalls?

**Step-by-Step Needs:**
- Step 2: Conduct core research
- Step 3: Inform tech stack considerations

---

## 🏗 5. System Designer

**Responsibilities:**
- Design tech-agnostic system architecture and module layout
- Define data flows, interface boundaries, and component responsibilities

**Typical Questions:**
- What are the core system components?
- How do we separate responsibilities?
- Are we preserving clean design principles?

**Step-by-Step Needs:**
- Step 2–3: Draft and finalize system design
- Step 4: Ensure features map cleanly to components
- Step 5–8: Prevent architecture drift and refactor as needed
- Step 9: Finalize documentation and diagrams

---

## 🧱 6. Software Architect

**Responsibilities:**
- Oversee architectural integrity and scalability
- Define core patterns and system standards
- Justify and finalize tech stack decisions

**Typical Questions:**
- Does this scale and evolve cleanly?
- Are we violating separation of concerns?
- Is this architecture framework-agnostic?

**Step-by-Step Needs:**
- Step 3: Review and approve architecture
- Step 4: Ensure PRDs fit design constraints
- Step 5–6: Catch architectural anti-patterns
- Step 9: Flag long-term improvements

---

## 🗺 7. Project Planner

**Responsibilities:**
- Break work into milestones, assign roles, and set timelines
- Track progress, blockers, and delivery status
- Maintain the development calendar and release cadence

**Typical Questions:**
- What is the timeline for this?
- Who owns this feature?
- How can we break this down further?

**Step-by-Step Needs:**
- Step 3: Build project plan and timeline
- Step 4: Own and organize PRD output
- Step 5–7: Track implementation and coordinate QA
- Step 9: Lead wrap-up and retrospectives

---

## 👨‍💻 8. Senior Developer

**Responsibilities:**
- Build core components and validate technical feasibility
- Lead code quality, patterns, and testing
- Mentor and review team contributions

**Typical Questions:**
- How can I write this modularly and safely?
- What are the edge cases and failure modes?
- How will we test and maintain this?

**Step-by-Step Needs:**
- Step 4–5: Estimate effort and implement core logic
- Step 6: Build and run automated tests
- Step 7–8: Patch bugs and refactor critical code
- Step 9: Clean up repo and document maintainability

---

## 🧪 9. QA Tester *(optional: simulated via Developer or User Advocate)*

**Note**: This role may be handled by the Senior Developer or User Advocate.

**Responsibilities:**
- Write test plans, explore edge cases, validate stability and correctness

**Step-by-Step Needs:**
- Step 6–7: Test product manually and via automation
- Step 8: Track regressions and retest fixes

---

## 📘 Summary Table

| Role               | Key Steps Involved                             |
|--------------------|------------------------------------------------|
| Visionary          | 1, 2, 6, 7, 9                                   |
| Project Strategist | 1, 2, 3, 4, 9                                   |
| User Advocate      | 1, 4, 6, 7, 8, 9                                |
| Technical Researcher | 2, 3                                          |
| System Designer    | 2, 3, 4, 5, 6, 8, 9                             |
| Software Architect | 3, 4, 5, 6, 9                                   |
| Project Planner    | 3, 4, 5, 6, 7, 8, 9                             |
| Senior Developer   | 4, 5, 6, 7, 8, 9                                |
