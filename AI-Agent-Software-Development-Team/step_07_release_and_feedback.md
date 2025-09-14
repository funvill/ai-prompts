
# 🚀 Step 7: Release & Feedback Gathering

## 🎯 Primary Goal of Step 7

To release the MVP to real users in a controlled or public environment, monitor its use, and systematically collect feedback. This feedback loop validates the product’s assumptions and informs future iterations or expansion.

This step emphasizes **measuring outcomes**, not just shipping code.

## 🧩 Key Objectives

| Objective | Description |
|----------|-------------|
| **Deployment** | Prepare and deploy the product to a real environment (internal, beta, or public). |
| **Communication** | Inform internal teams or early users about the release. |
| **Feedback Collection** | Gather structured and unstructured feedback on performance, usability, and value. |
| **Metrics Tracking** | Monitor product behavior, errors, and usage patterns. |

## ❓ Key Questions to Ask

### 📦 Deployment Readiness
- Have all blockers and critical bugs been resolved?
- Has the release been tested in an environment that mirrors production?
- Are rollback and hotfix strategies defined?

### 📢 Communication Strategy
- Who needs to know about the release (internal/external)?
- Are release notes or user instructions available?
- Are testers or champions available to advocate or guide usage?

### 📊 Feedback & Metrics
- Are logging, telemetry, and crash/error tracking in place?
- What are users telling us directly or indirectly?
- What features are being used the most (or least)?

## 👥 Participating Roles (4 of 10)

| Role | Description | Step 7 Responsibilities |
|------|-------------|--------------------------|
| **Project Planner** | Coordinates the release process and post-launch feedback loop. | - Set release date, publish announcement<br>- Collect team-wide and user feedback<br>- Triage post-release issues |
| **Senior Developer** | Prepares and executes the deployment. | - Package and ship the release<br>- Ensure error reporting and monitoring are in place<br>- Fix critical post-release bugs |
| **User Advocate** | Captures and summarizes feedback from real users. | - Interview or survey users<br>- Identify themes in feedback<br>- Suggest refinements or improvements |
| **System Designer** | Monitors system behavior and performance in real use. | - Validate system stability<br>- Spot unanticipated issues or edge cases<br>- Adjust diagrams if behavior diverges |

## 📝 Deliverables

| File | Contributed by | Description |
|------|----------------|-------------|
| `07_release_notes.md` | Project Planner | Summary of what was released, when, and how |
| `07_feedback_summary.md` | User Advocate (lead) | Themes, pain points, suggestions from users |
| `bugs/` | Senior Developer | List of new issues found after release |
| `01_vision_logbook.md` | All roles | Release decision log, risk reviews, post-release summaries |

## ✅ Exit Criteria

- Product has been released to a meaningful audience
- Feedback from users is collected and documented
- Release logs and deployment steps are reproducible
- Metrics and post-release issues are being tracked
- Stakeholders can evaluate success and decide on next steps
