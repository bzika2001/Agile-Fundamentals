![Agile fundementals](../images/Agile-undementals.png "Agile fundementals")
# 📊 Burndown and Burn-up Charts in Scrum: A Practical Guide for Delivery Leads

---

## 🔍 Burndown Chart

### ✅ Purpose in Scrum

The **Burndown Chart** tracks how much work remains in a Sprint or project (typically Story Points or hours). It answers:  
> “Are we on track to complete the planned work by the end of the Sprint or Release?”

Common types:
- **Sprint Burndown**
- **Release Burndown**

---

### 📈 How to Interpret It

**Y-axis**: Work remaining (Story Points, Tasks, Hours)  
**X-axis**: Time (e.g., Sprint Days)

#### Example ASCII Visual:
* Actual progress
Chart needed Sprint Burndown (Story Points)



- **Ideal line**: Straight line from total effort to zero
- **Actual line**: Shows real progress

---

### 🚩 Common Anti-Patterns

| Anti-Pattern            | What It Looks Like            | Coaching Advice                                      |
|-------------------------|-------------------------------|------------------------------------------------------|
| 🧊 Flat Line Syndrome   | No work burned down early     | Break stories into smaller slices                    |
| 📈 Burndown Goes Up     | Scope added mid-Sprint        | Coach on stable Sprint planning                      |
| 🧼 End-of-Sprint Cliff  | Work only burned on last day  | Encourage daily updates and transparency             |
| 🦥 Slow Start           | Minimal progress in first days| Discuss blockers and readiness of backlog items      |

---

### 💡 Use in Scrum Ceremonies

- **Daily Standup**  
  Ask: _"Are we burning down as expected? What’s blocking us?"_

- **Sprint Review**  
  Use it to show how work progressed across the Sprint

- **Retrospective**  
  Analyze burndown trends to discuss story sizing, WIP issues, and collaboration

---

## 📊 Burn-up Chart

### ✅ Purpose in Scrum

The **Burn-up Chart** shows how much work has been *completed* vs total scope. It answers:  
> “How much value have we delivered, and are we nearing our goal?”

More transparent than Burndown when scope changes.

---

### 📈 How to Interpret It

**Y-axis**: Story Points completed  
**X-axis**: Time (Sprint days or calendar weeks)

#### Example ASCII Visual:
*Burn-up (Release Scope)




- **Top line**: Total scope
- **Bottom line**: Completed work

---

### 🚩 Common Anti-Patterns

| Anti-Pattern        | What It Shows             | Coaching Focus                                          |
|---------------------|---------------------------|----------------------------------------------------------|
| 🎢 Scope Creep       | Top line keeps rising     | Work with Product Owner to manage change responsibly     |
| 🐌 Flat Completion   | No rise in delivery       | Uncover test/dev blockers, unclear DoD                   |
| 🔁 No Convergence    | Lines far apart for long  | Replan or raise visibility to stakeholders               |

---

### 💡 Use in Scrum Ceremonies

- **Daily Standup**  
  (Less used) If used, track delivery across longer timespans

- **Sprint Review**  
  Great for showing value delivery and release readiness

- **Retrospective**  
  Use to reflect on delivery trends, scope change, and throughput

---

## 🤝 Coaching Advice for Teams

### For Dev, QA, and Front-End Engineers:
- Update progress daily
- Keep tasks granular
- Don’t “burn” work unless it meets the Definition of Done

### For Product Owners & Stakeholders:
- Teach the **difference** between Burndown and Burn-up
- Use **Burn-up** to track delivery vs changing scope
- Use these charts to **guide**, not pressure

---

## 🛠 Sample Templates (Mental Models)

### ✅ Sprint Burndown Table

| Day | Planned Remaining | Actual Remaining |
|-----|-------------------|------------------|
| 1   | 30                | 30               |
| 2   | 27                | 30               |
| 3   | 24                | 28               |
| 4   | 21                | 25               |
| …   | …                 | …                |
| 10  | 0                 | 5                |

---

### ✅ Release Burn-up Table

| Sprint | Total Scope | Completed Work |
|--------|-------------|----------------|
| 1      | 100         | 10             |
| 2      | 105         | 25             |
| 3      | 105         | 45             |
| 4      | 110         | 60             |

---

## 🗣 Communicating to Teams and Stakeholders

- **To Teams**:  
  _“This isn’t about pressure. It’s our feedback loop. Let’s spot issues early and help each other.”_

- **To Stakeholders**:  
  _“Here’s how delivery is trending. If scope increases faster than output, we need to re-align priorities.”_

---




