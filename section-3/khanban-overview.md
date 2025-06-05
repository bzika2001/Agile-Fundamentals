![Agile fundementals](../images/Agile-undementals.png "Agile fundementals")
# 🧭 Getting Started with Kanban – A Practical Guide for Delivery Leads

---

## 🔍 What is Kanban?

Kanban is a **visual workflow management method** used to improve flow, limit WIP (Work in Progress), and deliver value continuously.

Originally from manufacturing (Toyota), it's now widely used in software, operations, DevOps, and support teams.

---
## 💡 Four Basic Principles of Kanban

### 1. **Start with what you know**
Kanban doesn’t force big, disruptive changes right away. You begin by **mapping your existing workflow**—how work moves from start to finish. This lowers resistance to change and builds trust.

**💼 As a Delivery Lead**:  
Observe how your team currently works in Azure DevOps. Don’t reinvent the wheel—just start by visualizing existing tasks and processes on a Kanban board. Let the board reflect reality, not some ideal.

---

### 2. **Agree to pursue incremental change**
Kanban thrives on **continuous improvement** (Kaizen). Instead of overhauling everything at once, you **implement small changes** that incrementally improve flow and delivery speed.

**🧩 Example**:  
After visualizing your workflow, you might introduce WIP limits. Later, you could tweak swimlanes or re-define “Done” criteria. Each change builds on the last.

**💼 As a Delivery Lead**:  
Lead retrospectives focused on process tweaks, not big resets. Guide your team to deliver value more often, then build on that progress.

---

### 3. **Respect current process, roles, responsibilities, titles**
Kanban works with the **current organizational structure**—you don’t need to redefine roles or processes from day one. Developers, QAs, PMs—all keep their roles, while the **workflow becomes transparent and easier to improve**.

**💼 As a Delivery Lead**:  
Reassure your team that adopting Kanban doesn’t mean losing autonomy or titles. Your role is to facilitate clarity and remove friction—not to dictate structure.

---

### 4. **Encourage acts of leadership at all levels**
Kanban promotes a culture where **everyone can contribute to improvement**, regardless of seniority. Leadership is not about job titles—it's about **taking initiative and solving problems** collaboratively.

**💼 As a Delivery Lead**:  
Recognize and celebrate when your team members take initiative—whether that’s flagging bottlenecks, proposing changes, or improving a board column. You set the tone by enabling a safe space for experimentation.

## 💡 Core Principles of Kanban

1. **Visualize the Work**
   - Use a Kanban board to show all tasks and their states
   - Columns = workflow stages (To Do, In Progress, Done)
   
2. **Limit Work in Progress (WIP)**
   - Set explicit limits on how many items can be in each column
   - Encourages finishing work before starting new work

3. **Manage Flow**
   - Aim for smooth, consistent movement of tasks through the system
   - Measure flow using **Lead Time** and **Cycle Time**

4. **Make Process Policies Explicit**
   - Clarify entry/exit criteria for each column
   - Helps team align and improve

5. **Implement Feedback Loops**
   - Use daily standups, retrospectives, reviews—tailored to flow instead of timeboxes

6. **Improve Collaboratively, Evolve Experimentally**
   - Use metrics and experiments to drive change
   - Data over opinion

---

## 🧠 Kanban Board: Visual Model

```
┌────────────┬──────────────┬─────────────┬────────────┐
│   To Do    │ In Progress  │   Review    │    Done    │
├────────────┼──────────────┼─────────────┼────────────┤
│ Task A     │ Task B       │ Task C      │ Task D     │
│ Task E     │ Task F       │             │ Task G     │
└────────────┴──────────────┴─────────────┴────────────┘
```

- WIP Limits Example:  
  `In Progress (Max: 3)` → Forces focus and finishes before new starts

---

## 📏 Key Metrics

| Metric | Definition | Coaching Use |
|--------|------------|--------------|
| **Cycle Time** | Time from “Started” to “Done” | Helps measure team efficiency |
| **Lead Time** | Time from “Requested” to “Done” | Tracks end-to-end delivery time |
| **Throughput** | # of items completed per time period | Shows team capacity |
| **Work in Progress (WIP)** | # of items in progress | Identify bottlenecks |

📈 Use a **Cumulative Flow Diagram (CFD)** to spot bottlenecks:
- Flat “Done” line → no throughput
- Widening “In Progress” band → overloaded team

---

## 🛑 Anti-Patterns to Watch For

| Anti-Pattern | Impact |
|--------------|--------|
| No WIP limits | Team starts too much, finishes little |
| Blocking work not flagged | Bottlenecks hide under the radar |
| Long cycle times | Work isn’t flowing; inspect causes |
| "Done" not really Done | Definition of Done unclear or inconsistent |

---

## 🤝 Kanban in Ceremonies

- **Daily Standup**  
  Focus on flow: “What’s blocked?”, “What can we finish today?”

- **Review (Optional)**  
  Highlight completed work and outcomes, not a Sprint goal

- **Retrospective**  
  Use metrics (Lead Time, WIP, Blockers) to drive discussion

- **Planning (Pull-based)**  
  Teams pull new work when capacity allows, rather than on a schedule

---

## 🧑‍🏫 Coaching Advice

### For Devs, QA, Front-End Engineers

- Encourage team to **finish, not start**
- Monitor WIP—respect limits
- Raise blockers early
- Swarm on bottlenecks

### For Stakeholders

- Kanban supports **continuous delivery**
- Less focus on timeboxes, more on **predictability**
- Metrics drive improvement, not just tracking

---

## 🗂️ Example Policies

**Column: "Ready for QA"**  
- Criteria: Code reviewed, feature toggled, merged to test branch  
- WIP Limit: 2

**Column: "In QA"**  
- Criteria: Test case written, environment ready  
- WIP Limit: 3

---

## 📌 Summary

| Topic | Scrum | Kanban |
|-------|-------|--------|
| Timeboxed? | Yes (Sprints) | No (Continuous) |
| Roles? | Scrum Master, PO, Dev Team | Optional |
| Focus | Commitment per Sprint | Continuous Flow |
| Metrics | Velocity, Burndown | Cycle Time, WIP, CFD |
| Planning | Sprint Planning | Pull-based |

---

## 🔄 Kanban Maturity Path

1. Visualize → See bottlenecks
2. Limit WIP → Improve focus
3. Track Flow → Spot delays
4. Use Metrics → Guide decisions
5. Improve Continuously → Real agility
