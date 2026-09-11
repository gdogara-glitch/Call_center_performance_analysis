# 📞 Call Center Performance Analysis

## 📌 Project Overview

This project analyzes **5,000 call center interactions recorded between January and March 2021** to evaluate operational performance, customer experience, and agent effectiveness.

Using **Power BI and Excel**, the analysis focuses on key call-center KPIs including:

- Call volume and trends
- Answered vs. unanswered calls
- Resolution rate
- Average speed of answer
- Customer satisfaction
- Call topics
- Agent performance

The goal is to identify operational gaps and provide **data-driven recommendations** that can improve response efficiency, issue resolution, and customer satisfaction.

---

## 🎯 Business Problem

A call center needs to balance **speed, resolution quality, and customer satisfaction**.

This analysis addresses several key business questions:

1. How many calls are being handled successfully?
2. What percentage of calls remain unanswered?
3. How effectively are customer issues being resolved?
4. Is the average response time meeting the target?
5. Which topics generate the highest call volumes?
6. How consistent is agent performance?
7. Where are the biggest opportunities for operational improvement?

---

## 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Calls** | 5,000 |
| **Answered Calls** | 4,054 (81%) |
| **Unanswered Calls** | 946 (19%) |
| **Resolved Calls** | 3,646 (73%) |
| **Unresolved Calls** | 1,354 (27%) |
| **Customer Satisfaction** | 69% |
| **Average Speed of Answer** | 68 seconds |
| **Response Time Target** | 60 seconds |
| **Total Agents** | 8 |

### 📈 KPI Highlights

- **81% of calls were answered**, leaving 19% unanswered.
- **73% of calls were resolved**, while 27% remained unresolved.
- Customer satisfaction was **69%**, indicating room to improve the overall customer experience.
- Average speed of answer was **68 seconds**, which is **8 seconds above the 60-second target**.

---

## 📊 Dashboard

The Power BI dashboard provides an interactive view of call-center performance across multiple dimensions, allowing users to monitor operational KPIs and identify areas requiring attention.

### Dashboard includes:

- Call volume trends
- Answered and unanswered calls
- Resolution performance
- Customer satisfaction
- Average speed of answer
- Call topics
- Agent-level performance

---

## 🔍 Key Insights

### 1. Response Efficiency

The average speed of answer was **68 seconds**, exceeding the 60-second target by 8 seconds.

This indicates an opportunity to improve call handling efficiency and reduce customer waiting time.

### 2. Unanswered Calls

Out of 5,000 calls, **946 were unanswered**, representing 19% of total call volume.

A consistently high level of unanswered calls may indicate opportunities to optimize staffing and scheduling during periods of high demand.

### 3. Resolution Performance

The call center resolved **3,646 calls (73%)**, while **1,354 calls (27%) remained unresolved**.

Improving first-contact resolution could reduce repeat contacts and improve customer satisfaction.

### 4. Customer Satisfaction

Customer satisfaction was **69%**.

While the majority of customers appear to have had a satisfactory experience, the result suggests that improvements in response time and resolution effectiveness could positively affect customer perception.

### 5. Call Topics

The largest call drivers were:

- **Streaming**
- **Technical Support**
- **Payment Issues**

Each accounted for approximately 20% of call volume, highlighting recurring areas where better self-service resources, troubleshooting guides, or process improvements could reduce call demand.

### 6. Agent Performance

Performance across the eight agents was relatively consistent, with differences that could be explored further through individual productivity, resolution, and satisfaction metrics.

---

## 💡 Recommendations

Based on the analysis, the following actions could improve call-center performance:

### 👥 Optimize Staffing

Review call-volume patterns and schedule additional agents during peak periods to reduce unanswered calls and waiting time.

### ⏱ Reduce Response Time

Investigate the causes of the 68-second average response time and introduce measures to bring performance closer to the 60-second target.

### 🎓 Targeted Agent Training

Use agent-level performance data to identify specific training opportunities, particularly around resolution efficiency and customer handling.

### 🛠 Address Recurring Issues

Develop better self-service resources and troubleshooting processes for high-volume topics such as technical support, streaming, and payment issues.

### 📈 Monitor KPIs Continuously

Use the Power BI dashboard as an ongoing performance-monitoring tool rather than relying only on periodic reporting.

---

## 🛠 Tools & Technologies

- **Microsoft Power BI** — Data modeling, DAX, KPI analysis, and dashboard development
- **Microsoft Excel** — Data preparation and analysis
- **DAX** — KPI and performance calculations
- **Data Visualization** — Interactive charts and performance dashboards

---

## 📁 Repository Structure

```text
Call_center_performance_analysis/
│
├── pbix/
│   └── Call_Center_Dashboard.pbix
│
├── pdf/
│   └── Call_Center_Dashboard.pdf
│
├── screenshots/
│   └── Dashboard screenshots
│
└── README.md
