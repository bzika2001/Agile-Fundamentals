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

## 📋 Kanban Board

A **Kanban Board** is a visual tool used to manage and track work as it moves through a process. It helps teams see what needs to be done, what's in progress, and what’s completed—bringing transparency and accountability to the workflow.

---

### 🧱 Basic Structure of a Kanban Board

Most Kanban boards have at least **three columns**:

- **To Do** – Work that’s been requested or planned but not started yet.
- **In Progress** – Tasks currently being worked on.
- **Done** – Completed work items.

Boards can be expanded with more detailed stages such as:

- Backlog
- Ready for Development
- In Review / QA
- Blocked
- Released

---

### 🎴 Kanban Cards

Each task or work item is represented by a **Kanban Card**. These cards typically include:

- Title or brief description
- Assignee
- Due date
- Priority or class of service
- Tags or labels
- Links to specs, code, or documents

Cards move **left to right** across the board as work progresses.

---

### 🔄 Real-Time Visibility

Kanban boards update in real time and provide a **clear snapshot** of:

- Who is working on what
- Where bottlenecks exist
- What tasks are getting stuck

This visibility helps Delivery Leads and team members **spot delays early and act quickly**.

---

### 🛠 Kanban in Azure DevOps

Azure DevOps allows you to:

- Create **custom Kanban boards** per team or project
- Use **columns and swimlanes** to reflect your workflow stages
- Attach WIP limits and policies to control flow
- Filter by tags, users, and areas for better tracking

---

### 💼 As a Delivery Lead:

- Use the board daily during stand-ups to **drive team discussions**.
- Monitor the flow to ensure work is moving smoothly.
- Use it to identify **bottlenecks**, blockers, or resource issues.
- Guide the team in keeping the board up to date and accurate.

---

## 💡 6 General Practices of Kanban
The **Six General Practices** of Kanban provide the operational foundation to apply and evolve the methodology effectively within a team.

1. **Visualize the Work**
 Make work visible. This is usually done by creating a **Kanban board** with cards and columns that represent workflow stages.
   - Use a Kanban board to show all tasks and their states
   - Columns = workflow stages (To Do, In Progress, Done)
     
 **💼 As a Delivery Lead:**  
Encourage transparency. Ensure everyone—from developers to QA—can clearly see the status of every task. Use board columns to match your team’s real process.

---
  
2. **Limit Work in Progress (WIP)**
Set explicit WIP limits to reduce multitasking, avoid bottlenecks, and encourage the team to finish tasks before starting new ones.
   - Set explicit limits on how many items can be in each column
   - Encourages finishing work before starting new work
     
**💼 As a Delivery Lead:**  
Introduce WIP gradually. Explain that it’s about improving **flow**, not restricting productivity. Help your team balance load and focus.

---

3. **Manage Flow**
 Focus on how work items flow through the system. The goal is to make the process smooth and predictable by identifying delays and constraints.
   - Aim for smooth, consistent movement of tasks through the system
   - Measure flow using **Lead Time** and **Cycle Time**
     
**💼 As a Delivery Lead:**  
Monitor **cycle time**, **lead time**, and blockers. Use Azure DevOps analytics or dashboards to identify where work tends to slow down.

---

4. **Make Process Policies Explicit**
Define clear, agreed-upon rules and criteria for how work items progress from one stage to another.

   - Clarify entry/exit criteria for each column
   - Helps team align and improve
     
**💼 As a Delivery Lead:**  
Work with your team to agree on definitions of “Ready,” “In Progress,” and “Done.” Make acceptance criteria and QA requirements visible on cards.

---
5. **Implement Feedback Loops**
 Introduce regular cadences for review and improvement, such as daily stand-ups, flow reviews, and retrospectives.

   - Use daily standups, retrospectives, reviews—tailored to flow instead of timeboxes
     
**💼 As a Delivery Lead:**  
Facilitate feedback loops with purpose. Use team check-ins to review WIP limits, adjust priorities, and gather ideas for improvement.

---
6. **Improve Collaboratively, Evolve Experimentally**
   Use a scientific, data-informed approach to evolve practices. Involve the whole team in identifying and testing small improvements.
   - Use metrics and experiments to drive change
   - Data over opinion

**💼 As a Delivery Lead:**  
Promote a safe space for experimentation. Celebrate incremental wins and show how each change contributes to better delivery.

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

## 📊 Key Kanban Metrics

Kanban relies heavily on **data-driven improvement**. These core metrics help measure the effectiveness of your delivery process and identify opportunities to optimize flow.

---

### 1. **Cycle Time**
The time it takes for a task to move from **"In Progress" to "Done"**.

- Measures efficiency.
- Lower cycle time = faster delivery.

**💼 As a Delivery Lead:**  
Use Cycle Time to assess how quickly your team can deliver once work starts. Track outliers to uncover bottlenecks or blockers.

---

### 2. **Lead Time**
The total time from when a task is **requested (To Do)** to when it’s **completed (Done)**.

- Includes waiting and idle time.
- Good for understanding the customer’s wait time.

**💼 As a Delivery Lead:**  
This is a key metric for forecasting and setting realistic stakeholder expectations. Shorter lead times = happier customers.

---

### 3. **Work In Progress (WIP)**
The number of tasks currently **in progress** (not started or finished).

- Directly impacts flow.
- Too much WIP = bottlenecks and multitasking chaos.

**💼 As a Delivery Lead:**  
Use WIP to encourage focus. Set reasonable WIP limits per column or per person using Azure DevOps rules.

---

### 4. **Throughput**
The number of tasks **completed in a given time period** (e.g., per week).

- Measures team productivity.
- Useful for forecasting future delivery rates.

**💼 As a Delivery Lead:**  
Use throughput trends to assess capacity and team output. Compare with cycle time to spot delivery slowdowns.

---

### 5. **Cumulative Flow Diagram (CFD)**
A visual chart showing the **number of items in each workflow state over time**.

- Highlights bottlenecks.
- Reveals trends in progress and delivery.

**💼 As a Delivery Lead:**  
Review your Azure DevOps CFD to understand whether work is piling up in certain stages or flowing smoothly.

---

### 6. **Blocked Time / Wait Time**
How long tasks are blocked or idle in any stage of the process.

- Uncovers invisible delays.
- Helps address root causes.

**💼 As a Delivery Lead:**  
Encourage your team to flag blocked tasks immediately. Analyze patterns—do certain issues or people cause frequent delays?

---

### 🧠 Pro Tip:
Combine metrics (e.g., Cycle Time + WIP + Throughput) to create **data-backed strategies** for improving flow.



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
## 🛑 Step to Get Started
 - Step 1:Visualize your work
 - Step 2:Visualize your work
 - Step 3:Adapt, monitor, and improve

   
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
