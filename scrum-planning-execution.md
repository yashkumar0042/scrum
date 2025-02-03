
---

# **Scrum Planning and Execution**

## **1. Sprint Planning**
Sprint Planning is a time-boxed event at the beginning of a sprint where the team defines what work will be completed. The session is collaborative and involves the **Product Owner, Scrum Master, and Development Team**.

### **Key Components of Sprint Planning**
1. **Setting Sprint Goals**
   - A Sprint Goal is a **concise statement** defining what the team aims to achieve during the sprint.
   - It provides **focus** and aligns the team with business priorities.
   - The **Product Owner** collaborates with the team to define the goal based on the **highest priority backlog items**.

   **Example of a Sprint Goal:**  
   _"Improve user onboarding by implementing a guided setup and reducing the sign-up form complexity."_

2. **Capacity Planning**
   - Capacity planning ensures that the team **commits** to a realistic amount of work based on their availability.
   - Factors considered:
     - Number of available team members.
     - Planned leaves, holidays, or meetings.
     - Velocity (average story points completed in past sprints).

   **Formula for Capacity Calculation:**  
   \[
   \text{Capacity} = (\text{Number of Developers} \times \text{Available Hours per Day}) \times \text{Sprint Duration (Days)}
   \]

   Example:  
   - A team of 5 members, working 6 hours/day in a 10-day sprint.  
   - Total capacity = **5 × 6 × 10 = 300 hours**.

3. **Estimation Techniques**
   Estimation helps the team gauge the complexity and effort required for user stories. Common techniques include:

   - **Story Points:**  
     - Measures complexity based on **effort, risk, and uncertainty**.
     - Follows Fibonacci sequence (1, 2, 3, 5, 8, 13…).

   - **Planning Poker:**  
     - A team-based activity where members **individually assign story points** and discuss discrepancies.

   - **T-Shirt Sizing (S, M, L, XL):**  
     - Used for **high-level estimation** when refining large features.

   **Example:**  
   - Login feature: **2 story points (simple)**  
   - Payment integration: **8 story points (complex, external dependency)**

---

## **2. Backlog Refinement**
Backlog Refinement (or Grooming) is a **continuous process** where the team ensures that the product backlog items are **well-defined, prioritized, and ready** for sprint planning.

### **Key Aspects of Backlog Refinement**
1. **Writing Effective User Stories**
   - A good user story follows the **INVEST principle**:
     - **I**ndependent
     - **N**egotiable
     - **V**aluable
     - **E**stimable
     - **S**mall
     - **T**estable

   **User Story Template:**  
   ```
   As a <user role>,
   I want to <do something>,
   So that <I get a benefit>.
   ```
   **Example:**  
   _"As a user, I want to reset my password so that I can regain access to my account."_

2. **Prioritization Techniques**
   - **MoSCoW (Must-have, Should-have, Could-have, Won’t-have)**:
     - Must-have: Critical features.
     - Should-have: Important but not urgent.
     - Could-have: Nice-to-have.
     - Won’t-have: Not planned for now.

   - **WSJF (Weighted Shortest Job First)**
     - Prioritizes work based on the ratio:  
       \[
       \text{WSJF} = \frac{\text{Business Value} + \text{Time Criticality} + \text{Risk Reduction}}{\text{Effort Required}}
       \]
     - Higher WSJF = Higher priority.

---

## **3. Sprint Execution**
Once a sprint begins, the focus shifts to **delivering the committed work** effectively.

### **1. Managing Progress**
To track progress and ensure the sprint stays on course, teams use **Burndown and Burnup Charts**.

- **Burndown Chart:**
  - Tracks remaining work (in story points or hours) **over time**.
  - Ideal for identifying **scope creep or delays**.

  **Example:**  
  - If the sprint starts with 50 story points, the burndown chart should **decline** to 0 by the end.

- **Burnup Chart:**
  - Tracks **work completed** vs. **total work planned**.
  - Helps in **understanding scope changes**.

### **2. Conducting Productive Daily Stand-ups**
A **Daily Stand-up** (Daily Scrum) is a **15-minute time-boxed meeting** for the team to sync up.

**Three Key Questions in Stand-ups:**
1. **What did I complete yesterday?**
2. **What will I work on today?**
3. **Are there any blockers?**

**Best Practices:**
- Keep it **brief and to the point**.
- Focus on **progress and impediments**.
- The **Scrum Master** ensures blockers are addressed.

---

