
![Agile fundementals](../images/Agile-undementals.png "Agile fundementals")

## 📚 Scrum Terms & Artifacts (Agile Fundamentals)

Scrum is a flexible framework for developing, delivering, and sustaining complex products. It's all about **transparency, inspection, and adaptation**.

---

### 📝 1. User Stories (The "What")
* **Definition**: Short, simple descriptions of a feature from the perspective of the end user.
* **Core Idea:** A short, simple description of a feature from the perspective of the person who wants it (the user). They focus on **value** and **who** it's for, acting as placeholders for conversations.
* **20% Understanding:** They describe *what* a user wants to achieve and *why*, giving the team context.
* **Example:** "As a **customer**, I want to be able to **reset my password**, so that I can **regain access to my account** if I forget it."


* **Format**:  
  `"As a [user], I want [goal] so that [reason]."`

---

### ✅ 2. User Stories: Acceptance Criteria (The "When is it Done?")
* **Purpose**: Define the conditions under which a user story is considered complete.
* **Core Idea:** Conditions a user story must meet to be considered complete and correct. They define the boundaries and are written from a testing/user perspective.
* **20% Understanding:** They clarify the **specific behaviors or outcomes** needed for the story to deliver value, making it clear what to build and how to test it.
* **Example (for "reset password" story):**
    * "Given I am on the login page, when I click 'Forgot Password,' then I am directed to the password reset form."
    * "Given I enter a valid email and new password, when I submit the form, then my password is updated and I receive a confirmation email."

- **Example Formats**:
  - Given [context], when [action], then [outcome]
  - "The system should allow users to reset their password via email."    

---

### ✨ 3. Writing Great User Stories (INVEST)

* **Core Idea:** The **INVEST** acronym guides effective story writing:
    * **I**ndependent: Can be worked on alone.
    * **N**egotiable: Open to discussion.
    * **V**aluable: Delivers clear benefit.
    * **E**stimable: Can be sized by the team.
    * **S**mall: Can fit within a sprint.
    * **T**estable: Has clear verification points.
* **20% Understanding:** Focus especially on **Valuable**, **Small**, and **Testable**. If a story isn't valuable, don't build it. If it's too big, break it down. If you can't test it, you can't prove it works.
- **Tips**:
  - Collaborate with stakeholders.
  - Keep stories concise and focused.
  - Break down epics into small, actionable items.
---
## 4. User Story Example

> **As a** frequent flyer, **I want** to check in online **so that** I can save time at the airport.

---
### 📋 4. Product Backlog vs. Sprint Backlog

* **Product Backlog (The "Master List")**
- **Definition**: An ordered list of everything that is known to be needed in the product.
- **Owner**: Managed by the Product Owner.
- **Nature**: Continuously evolving and prioritized.
    * **Core Idea:** A single, prioritized list of *everything* that *might* be needed in the product. It's owned by the **Product Owner** and is always changing.
    * **20% Understanding:** It's the **entire product's wishlist**, ordered by value, and it's **never truly "finished."**
* **Sprint Backlog (The "Current Sprint's Work")**
* **Definition**: A set of Product Backlog items selected for the Sprint, plus a delivery plan.
- **Owned by**: Developers.
    * **Core Idea:** The specific items chosen from the Product Backlog for the current Sprint, plus the plan for delivering them. It's owned by the **Development Team**.
    * **20% Understanding:** It's the **team's commitment for *this* Sprint**, detailing *what* they'll work on and *how* they'll achieve it. It's fixed once the Sprint starts.

---

### 🤝 5. Working Agreements (Team Rules)
- **Purpose**: Shared expectations on how team members will collaborate.
- **Examples**:
  - Stand-ups at 9 AM.
  - No meetings during focus hours.
  - All code changes go through review.
* **Core Idea:** Explicit guidelines the team agrees to follow for a positive and productive environment (e.g., meeting norms, communication, conflict resolution).
* **20% Understanding:** These are the **team's self-defined "rules"** for how they'll work together effectively.

---

### ✅ 6. Definition of Ready (DoR - "Are We Ready to Start?")

- **Definition**: A checklist to confirm a user story is ready for development.
- **Typical Criteria**:
  - Story clearly defined and understood.
  - Acceptance criteria written.
  - Dependencies identified.
  - Story sized appropriately.
* **Core Idea:** A shared understanding of what conditions a Product Backlog Item must meet *before* the team pulls it into a Sprint.
* **20% Understanding:** It's a **checklist for clarity**. It ensures the team understands *what* to build *before* starting, preventing mid-sprint confusion. (e.g., "Story has acceptance criteria," "It's estimated," "Dependencies are identified.")

---

### ✨ 7. Definition of Done (DoD - "Is it Really Done?")
- **Definition**: A shared understanding of what "complete" means.
- **Typical Criteria**:
  - Code written and peer-reviewed.
  - Unit and integration tests pass.
  - Feature deployed to staging.
  - Documentation updated.
* **Core Idea:** A shared understanding of the criteria a Product Backlog Item must meet to be considered truly "Done" (e.g., tested, code reviewed, documented, integrated).
* **20% Understanding:** This is the **quality bar** for completed work. If it doesn't meet the DoD, it's *not* done. It ensures consistency and a shippable product.

---

### 📦 8. Product Increment (The "New Usable Piece")

* **Core Idea:** The sum of all completed Product Backlog items from the current Sprint, plus all previous Sprints. It must be usable and potentially shippable.
* **20% Understanding:** It's the **newest, usable, and valuable slice of the product** available at the end of a Sprint.

---

## 👩‍🏫 How to Help Your Team Adopt These Concepts (As a Delivery Lead)

As a Delivery Lead, your role is to guide and facilitate. Here's how you can promote adoption:

1.  **Lead by Example & Be the Coach:**
    * **Model the Behavior:** Consistently use Scrum terms correctly and ask "who" and "why" questions for features (User Story mindset).
    * **Coach, Don't Dictate:** Instead of telling, ask guiding questions: "Do we have clear acceptance criteria?" "Is this story small enough?"

2.  **Facilitate, Don't Command:**
    * **Collaborative DoR/DoD Creation:** Guide a session where the *team* collectively defines "ready" and "done" for themselves. Ownership leads to adherence.
    * **Working Agreements Session:** Help the team create their own "rules of engagement." Post them visibly and refer to them when needed.

3.  **Hands-On Practice:**
    * **Story Writing Workshops:** Conduct short, interactive sessions for the team to practice writing User Stories and Acceptance Criteria using real examples.
    * **Brainstorming:** Make it a team habit to brainstorm acceptance criteria *before* starting work on any story.

4.  **Emphasize the "Why":**
    * **Connect DoD to Quality:** Explain that a strong DoD prevents bugs and rework, leading to a truly releasable product.
    * **Connect Product Increment to Value:** Show how their completed Increment delivers real value to stakeholders through demos.

5.  **Visual Reinforcement:**
    * **Post Key Agreements:** Display your team's DoR, DoD, and Working Agreements in a visible place (physical or virtual).
    * **Use Visual Tools:** Leverage tools like Jira, Azure DevOps, or Trello boards to visualize the flow of stories through your backlogs and "Done" states.

6.  **Continuous Improvement (Retrospectives):**
    * **Regular Retros:** Use Sprint Retrospectives to discuss how effectively the team is applying these Scrum concepts.
    * **Adapt and Adjust:** Encourage the team to discuss what's working and what's not, and make adjustments to their processes as needed.

By making these concepts practical and empowering your team to own them, you'll build a strong, effective Agile process!

---