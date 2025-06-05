![Agile fundementals](../images/Agile-undementals.png "Agile fundementals")
# 📊 Burndown vs Burn-up Charts in Scrum: A Practical Coaching Guide

As a Delivery Lead deepening your Scrum expertise, it's key to not only understand **what** these charts represent, but also **how** to use them to coach, communicate, and guide delivery teams and stakeholders effectively.

---

## 🔥 Burndown Chart

### 🎯 Purpose
Shows **how much work remains** in a Sprint or Release over time. It "burns down" to zero as the team completes work.

Used to:
- Track progress within a Sprint (Sprint Burndown)
- Track progress across Sprints (Release Burndown)
- Identify potential scope creep or delays

---

### 🧠 Mental Model
Imagine a **downward-sloping** line starting at the top left and aiming for the bottom right.

```
Ideal
│
│\
│ \
│  \
│   \            ← Actual
│    \__________
│              |
└───────────────▶
   Day 1      Day 10
```

- The **Y-axis** = Remaining work (story points, hours, tasks)
- The **X-axis** = Time (days in the Sprint)
- The **ideal line** shows expected progress
- The **actual line** shows real progress

---

### 🔍 How to Interpret

- **On track:** Actual line closely follows the ideal
- **Lagging:** Line is flat = no work completed
- **Spikes upward:** New work was added
- **Sharp drops:** Bulk work closed at once (possibly at Sprint end)

---

### ⚠️ Anti-Patterns to Watch For

| Pattern | Coaching Insight |
|--------|------------------|
| Flat Line | Work isn't getting done or updated |
| Last-minute drop | Teams closing work at the end without incremental progress |
| Upward spike | Scope creep—new work added mid-Sprint |
| Steep drops | Work not split well, not delivering iteratively |

---

### 🤝 In Ceremonies

- **Daily Standup:**  
  Highlight what was completed since yesterday. Ask:
  - "Why hasn’t this moved?"
  - "What’s blocking progress?"

- **Sprint Review:**  
  Use it to show the progress toward Sprint/Release goal. Reflect on accuracy.

- **Retrospective:**  
  Discuss gaps in estimation, task breakdown, or team capacity when burndown was off.

---

## 📈 Burn-up Chart

### 🎯 Purpose
Shows how much work is **completed over time**, relative to total scope. Burn-up = progress climbing **up to** a goal.

Used to:
- Show completed work **and** total scope
- Make scope changes visible (ideal for stakeholders)

---

### 🧠 Mental Model

A **rising staircase** or **ascending line chart**. There are two key lines:
1. **Completed Work**
2. **Total Scope**

```
Scope
│           ┌──────────── Total Scope
│         ┌─┘
│       ┌─┘
│     ┌─┘
│  ┌──┘          ← Completed Work
│ ┘
└────────────────────▶
   Time (Days/Sprints)
```

- **Y-axis** = Total work (e.g., story points)
- **X-axis** = Time

---

### 🔍 How to Interpret

- **Gap between lines shrinks** = Progress!
- **Flat top line + rising bottom line** = Scope stable, work progressing
- **Top line moves upward** = Scope creep
- **Flat bottom line** = No work completed

---

### ⚠️ Anti-Patterns to Watch For

| Pattern | Coaching Insight |
|--------|------------------|
| Scope line moves up often | Stakeholders are injecting work mid-Sprint |
| No change in completed line | Team is stuck or underperforming |
| Completed line surges at end | Poor flow; teams may be batching work |

---

### 🤝 In Ceremonies

- **Daily Standup:**
  Less commonly used, but can highlight progress made vs planned.

- **Sprint Review:**
  Use it to communicate **both velocity and scope clarity** to stakeholders.

- **Retrospective:**
  Use it to identify when scope changes happened and whether they were properly managed.

---

## ✅ Coaching Advice for Cross-Functional Teams

### 👥 Developers, QA, Front-End Engineers

- **Ensure transparency**: Encourage daily updates to tasks or tickets so charts reflect reality.
- **Promote small batch delivery**: This makes charts more informative and progress visible.
- **Pair QA & Devs early**: Avoid "test last" where QA work accumulates at the end, flattening burndown.
- **Track Done-Done**: Define “Done” clearly (code, test, merged, deployed to test) to keep the charts honest.

---

## 📄 Templates

### 🧾 Sample Sprint Burndown (Story Points over 10-day Sprint)

| Day | Planned | Actual Remaining |
|-----|---------|------------------|
| 1   | 40      | 40               |
| 2   | 36      | 40               |
| 3   | 32      | 38               |
| 4   | 28      | 35               |
| 5   | 24      | 28               |
| 6   | 20      | 25               |
| 7   | 16      | 18               |
| 8   | 12      | 12               |
| 9   | 8       | 8                |
| 10  | 0       | 0                |

> Flat days early on signal slow start  
> Mid-sprint catch-up shows strong push  
> Ideal for retro discussion

---

### 🧾 Sample Burn-up (Release Level)

| Sprint | Completed Points | Total Scope |
|--------|------------------|-------------|
| 1      | 10               | 50          |
| 2      | 18               | 50          |
| 3      | 27               | 60 🔺       |
| 4      | 38               | 60          |
| 5      | 45               | 65 🔺       |
| 6      | 58               | 65          |

> Scope increases marked with 🔺  
> Useful to explain why velocity didn’t "catch up" linearly

---

## 🗣 Communicating to the Scrum Team

- "These charts aren’t for policing—they’re feedback tools for *us*."
- "If we see a flat burndown, it’s not blame—it’s a flag to inspect the process."
- "This isn’t about ideal lines; it’s about honest, transparent learning."

---

## 🧑‍💼 Communicating to Stakeholders

- "Burn-up charts help show both scope and delivery, so changes in either are visible."
- "These visual tools help us avoid surprises late in the release."
- "If scope changes, we can clearly see its impact on timelines—no hiding, just honest data."

---

## 📌 Summary

| Chart | Focus | Best For | Main Risk |
|-------|-------|----------|-----------|
| Burndown | Work Remaining | Sprint Monitoring | Misleading if not updated |
| Burn-up | Work Completed vs Scope | Release Tracking | Stakeholders misreading flat lines |

Use these tools to lead with clarity, foster accountability, and encourage sustainable delivery.



---




