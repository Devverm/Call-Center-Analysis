# 📞 Call Center Analytics Dashboard | Power BI

## 🚀 Boost agent performance and improve customer satisfaction with interactive dashboards.

![Call Center Trends Dashboard](Call_center_trends_manager.png)

---

## 📌 Overview

An interactive **Call Center Analytics Dashboard** built with Power BI Desktop and Excel, designed to help call centre managers make data-driven decisions. The dashboard provides a comprehensive view of agent performance, call volume trends, customer satisfaction, and operational efficiency — all in one place.

The dataset covers **5,000 calls** handled by 8 agents (Becky, Dan, Diane, Greg, Jim, Joe, Martha, Stewart) across multiple topics including Technical Support, Payment Related, Contract Related, Admin Support, and Streaming.

---

## 📊 Dashboard Features

### 🔢 KPI Cards
| Metric | Value |
|---|---|
| Total Calls | 5,000 |
| Calls Answered | 4,054 |
| Calls Unanswered | 946 |
| Avg Customer Rating | 3.40 / 6.81 |
| Avg Speed of Answer | 67.52 seconds |

### 📈 Visuals Included
- **Count of Answered Calls** — Pie chart showing answered (81.08%) vs unanswered (18.92%) calls
- **Count of Calls By Time** — Area chart tracking call volume throughout the day (09:00–18:00)
- **Average Customer Rating Gauge** — Needle gauge showing satisfaction score out of max rating
- **Average Speed of Answer Gauge** — Response time performance indicator
- **Average Calls Answered Gauge** — Team throughput at a glance
- **Agent Performance Table** — Breakdown per agent: unanswered calls, calls answered, avg speed of answer, avg talk duration
- **Agent Filter Buttons** — Interactive filter to drill into individual agent performance

---

## 🗂️ Dataset Details

**File:** `01_Call-Center-Dataset.xlsx`

| Column | Description |
|---|---|
| `Call Id` | Unique identifier for each call |
| `Agent` | Name of the agent who handled the call |
| `Date` | Date the call was received |
| `Time` | Time the call was received |
| `Topic` | Call category (Technical Support, Payment Related, Contract Related, Admin Support, Streaming) |
| `Answered (Y/N)` | Whether the call was answered |
| `Resolved` | Whether the issue was resolved |
| `Speed of answer in seconds` | Time taken to answer the call |
| `AvgTalkDuration` | Duration of the call |
| `Satisfaction rating` | Customer satisfaction score (1–5) |

---

## 💡 Key Insights

- **81.08%** of all calls were successfully answered, leaving **946 calls unanswered** — a key area for improvement
- The **average customer satisfaction rating is 3.40**, indicating room to improve customer experience
- **Average speed of answer is 67.52 seconds** — tracking this per agent helps identify bottlenecks
- Call volume peaks can be identified from the **time-based chart**, enabling better shift planning
- The **agent filter** allows managers to isolate individual performance and conduct targeted coaching

---

## 🛠️ Technology Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development, DAX measures, interactive visuals |
| **Microsoft Excel** | Raw data source and preprocessing |

---

## 🎯 Target Audience

- 📋 Call centre managers and supervisors
- 📊 Business analysts and data analysts
- 🎓 Students learning Power BI with real-world datasets
- 💡 Anyone interested in operational analytics and data-driven decision-making

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)
- Microsoft Excel (to view/edit the dataset)

### Steps

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/Call-Center-Analytics-PowerBI.git
   ```

2. **Open the dashboard**
   - Launch Power BI Desktop
   - Open `Call_Center_Analysis.pbix`

3. **Connect the data source**
   - If prompted, relink to `01_Call-Center-Dataset.xlsx`
   - Go to **Home → Transform Data → Data Source Settings** and update the file path

4. **Explore the dashboard**
   - Use the **agent filter buttons** at the top to drill into individual agents
   - Hover over charts for tooltips with detailed metrics
   - Click on any visual to cross-filter the rest of the report

---

## 📁 Project Structure

```
📦 Call-Center-Analytics-PowerBI
 ┣ 📊 Call_Center_Analysis.pbix          # Power BI dashboard file
 ┣ 📄 01_Call-Center-Dataset.xlsx        # Raw call centre dataset (5,000 records)
 ┣ 🖼️ Call_center_trends_manager.png     # Dashboard preview image
 ┗ 📝 README.md                          # Project documentation
```

---

## 🔮 Future Enhancements

- Add a **monthly trend page** to track performance over time
- Include a **resolution rate** breakdown by topic and agent
- Build a **predictive model** for call volume forecasting
- Add **customer sentiment analysis** using NLP on call notes
