
![Agile fundementals](../images/Agile-undementals.png "Agile fundementals")

# Agile Estimation for SA Payroll Legacy Code: Simplified Guide

## 💡 Introduction: Estimating for High-Risk SA Payroll
---
In **South African payroll legacy systems**, estimation isn't just about time; it's about **managing risk, ensuring compliance (SARS, BCEA, etc.), and protecting data integrity.** It helps us uncover hidden problems and plan for the unexpected in a complex, critical environment.

**Simply Put:** Don't guess. Estimate to find hidden dangers in old payroll code.

## 🤔 Why Estimate in SA Payroll Legacy?
---
We estimate to:

* **✨ Prioritize Smartly:** Balance new features with critical compliance updates or technical debt.
    * *Example:* Fixing a SARS API bug (high risk) might be more urgent than a new bonus feature.
* **📊 Plan Realistically:** Understand how much work the team can truly do, accounting for legacy code challenges.
    * *Example:* Legacy work might mean your team completes fewer "points" per sprint than new development.
* **🤝 Understand Deeply:** Estimation forces team discussions, revealing hidden complexities in old code or SA regulations.
    * *Example:* Discussing a pension change uncovers undocumented COBOL modules and missing tests.
* **🛡️ Spot Risks Early:** High estimates flag potential breaking changes, data errors, or compliance issues.
    * *Example:* A large estimate for an overtime rule change signals complex interactions with old systems and union rules.
* **📈 Learn & Improve:** Reviewing past estimates helps the team get better and avoid future problems, especially with compliance.
    * *Example:* After a SARS penalty, the team learns to add "API monitoring" tasks to every sprint.

## 🛠️ Key Estimation Techniques for SA Payroll Legacy
---
Focus on **relative sizing**, where "effort" includes complexity, risk, and compliance needs.

### 1. 📏 Story Points (using Fibonacci Sequence)
* **What:** Abstract numbers (1, 2, 3, 5, 8, 13, 21...) representing effort. Higher numbers mean more complexity/risk in legacy code.
* **🎲 Planning Poker:** Team members vote silently, then reveal. Differences spark discussion about hidden issues.
    * *How it works:* PO presents "new tax rate update." Team asks SA-specific questions ("Which old module? Any tests?"). Votes (e.g., 3, 5, 13, 21) lead to discussion about old code, no tests, and IRP5 risks. Result: Break down into "Spike: Research tax logic," "Build automated tests," then "Implement update."

### 2. 👕 T-Shirt Sizing (High-Level)
* **What:** Quick sizing (XS, S, M, L, XL, XXL) for very large items like major system overhauls or compliance projects.
* *Example:* "Migrate payroll to cloud (with SARS audit trails)" = **XXL**.

### 3. ➕ Three-Point Estimation (For Risky Tasks)
* **What:** Get three estimates: Optimistic (O), Most Likely (M), Pessimistic (P). Calculate an Expected Estimate (E) = (O + 4M + P) / 6.
* *Example:* For "Update employee bonus calculation":
    * O=6hrs, M=18hrs, P=60hrs (due to hidden bugs, no tests, IRP5 impact).
    * E = 23 hours. This flags a high-risk task.

### The 80/20 Rule for SA Payroll Legacy
---
Focus detailed estimation on the **next few sprints' work**, including critical technical debt and compliance spikes. Don't over-estimate far-off work that will likely change.

## 🚀 How to Help Your Team Adopt Estimation (as Delivery Lead)
---
Be a **coach, protector, and advocate for compliance and deep investigation**.

1.  **🎓 Educate on SA Risks:** Explain *why* legacy estimation is different, focusing on SA compliance and technical debt.
    * *Tip:* Run a "SARS Compliance & Legacy Safari" workshop.
2.  **🗣️ Facilitate Deep Dives:** Encourage thorough discussions. Don't rush. Protect the team from pressure for low estimates.
    * *Tip:* When estimates vary, ask "What specific old code or SA regulation concerns you?"
3.  **🌱 Start Small & Iterate:** Break down big legacy tasks. Prioritize "spikes" (small research tasks) for SA compliance.
    * *Tip:* Start with simple stories. For complex ones, add a "Spike: Research new SARS PAYE tables" story first.
4.  **↔️ Emphasize Relative Sizing:** Use "reference stories" to compare new work to old. Don't let points become hours.
    * *Tip:* Establish that "Upgrading a 10-year-old dependency with SARS implications" is always a 13-point effort.
5.  **💖 Foster Psychological Safety:** Create a blame-free environment. Encourage honesty about unknowns and risks. Celebrate "unsexy" work that improves compliance.
    * *Tip:* If an estimate is off, ask "What did we learn?" not "Why were you wrong?" Praise raising concerns about SA compliance.
---
