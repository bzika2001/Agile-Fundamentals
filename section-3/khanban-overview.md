![Agile fundementals](../images/Agile-undementals.png "Agile fundementals")
# 🧭 Getting Started with Kanban – A Practical Guide for Delivery Leads

---

## 🔍 What is Kanban?

Kanban is a **visual workflow management method** used to improve flow, limit WIP (Work in Progress), and deliver value continuously.

Originally from manufacturing (Toyota), it's now widely used in software, operations, DevOps, and support teams.

---

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
