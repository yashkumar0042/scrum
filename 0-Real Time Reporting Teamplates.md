
---

## **📊 JIRA Dashboard for Scrum Metrics**
### **1️⃣ Sprint Progress Tracking Dashboard**
**Purpose:** Provides a real-time view of sprint progress, including remaining tasks, completed work, and sprint health.

#### **Widgets & Reports:**
- **Sprint Burndown Chart:** Tracks remaining work vs. time.
- **Sprint Velocity Chart:** Displays past sprint performance trends.
- **Issue Statistics:** Categorizes tasks (To Do, In Progress, Done).
- **Sprint Health Status:** Percentage of completed vs. pending tasks.

#### **Example Dashboard Setup in JIRA:**
| **Widget Name**       | **Data Source**          | **Purpose** |
|----------------------|----------------------|------------|
| **Sprint Burndown**  | Sprint Reports       | Tracks remaining story points over sprint duration. |
| **Velocity Chart**   | Completed Sprints    | Helps forecast upcoming sprint capacity. |
| **Issue Statistics** | Active Sprint Board  | Shows tasks breakdown (Bugs, Stories, Tasks). |
| **Cumulative Flow**  | Kanban Reports       | Tracks work-in-progress limits and backlog trends. |

**JIRA Configuration Steps:**
1. Go to **Dashboards** → Click **Create Dashboard**.
2. Add **Sprint Burndown Gadget**.
3. Add **Velocity Chart Gadget**.
4. Add **Issue Statistics Gadget**.
5. Customize for your team’s sprint board.

---

## **📊 Real-Time Reporting Templates**
### **2️⃣ Sprint Burndown Report (Excel/Google Sheets)**
**Purpose:** Tracks how work progresses daily within a sprint.

#### **Template Fields:**
| **Day** | **Planned Story Points** | **Remaining Story Points** | **Completed Story Points** | **Cumulative Flow** |
|--------|-------------------------|-------------------------|-------------------------|-------------------|
| Day 1  | 50                      | 50                      | 0                       | To Do: 10, In Progress: 5, Done: 0 |
| Day 2  | 50                      | 45                      | 5                       | To Do: 8, In Progress: 7, Done: 5 |
| Day 3  | 50                      | 35                      | 15                      | To Do: 5, In Progress: 8, Done: 15 |

📌 **How to Use?**
1. Update the remaining and completed story points daily.
2. Visualize data using a **Line Chart** for Burndown Trends.
3. Use **Conditional Formatting** to highlight delays.

---

### **3️⃣ Velocity Tracking Report**
**Purpose:** Helps forecast sprint capacity based on past performance.

#### **Template Fields:**
| **Sprint Name** | **Story Points Committed** | **Story Points Completed** | **Velocity** |
|---------------|----------------------|----------------------|----------|
| Sprint 1     | 50                   | 45                   | 45       |
| Sprint 2     | 55                   | 50                   | 50       |
| Sprint 3     | 60                   | 52                   | 52       |

📌 **How to Use?**
- Calculate **average velocity** over the last 3-5 sprints.
- Use this for **better sprint planning**.
- Adjust for **scope creep and blockers**.

---

### **4️⃣ Lead Time & Cycle Time Report**
**Purpose:** Measures efficiency in handling tasks from request to completion.

#### **Template Fields:**
| **Task ID** | **Start Date** | **End Date** | **Cycle Time (Days)** | **Lead Time (Days)** |
|----------|------------|------------|-----------------|-----------------|
| TASK-101 | 01 Feb     | 05 Feb     | 4               | 6               |
| TASK-102 | 02 Feb     | 07 Feb     | 5               | 7               |

📌 **How to Use?**
- Identify high lead/cycle times and investigate bottlenecks.
- Reduce handoff delays by improving team collaboration.
