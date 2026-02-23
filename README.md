# ETL-Pipeline-Using-AWS
# 📊 CarePlus Insights – Support Tickets & Logs Dashboard

## 📌 Project Overview
CarePlus Insights is a Power BI dashboard project designed to analyze support tickets and system logs data.  
The dashboard provides operational insights into ticket resolution performance, agent activity, CPU usage trends, and response time patterns.

This project demonstrates:
- Data modeling
- Data transformation (Power Query)
- DAX calculations
- KPI design
- Dashboard visualization best practices

---

## 🗂 Dataset Description

The project includes the following datasets:

### 1️⃣ Support Tickets
- ticket_id
- agent
- channel
- status
- issue_category
- priority
- created_at
- resolution_time

### 2️⃣ Support Logs
- timestamp
- cpu
- log_level
- response_time
- user_agent
- component
- event_type

---

## 📊 Dashboard Features

### 🔹 Ticket Insights Page
- Total Tickets KPI
- Resolved Tickets KPI
- Open Tickets KPI
- Escalated Tickets KPI
- Total Agents KPI
- Average Interactions
- Average Resolution Minutes
- 100% Stacked Column Chart (Tickets by Channel & Status)
- Agent Performance Analysis
- Issue Category Resolution Analysis
- Ticket-level detail table

### 🔹 Support Logs Page
- Total Logs KPI
- Logged Tickets KPI
- Avg CPU (%) KPI
- Avg Response Time (ms)
- CPU Trend (Zig-Zag Line Chart by Timestamp)
- Logs by User Agent
- Logs by Log Level (Donut Chart)
- Logs vs Tickets by Response Time Range

---

## 🛠 Tools & Technologies Used

- Power BI Desktop
- Power Query (Data Transformation)
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)
- GitHub (Version Control & Documentation)

---

## 📈 Key Insights

- Identified channel-wise ticket resolution trends.
- Analyzed response time distribution across performance buckets.
- Monitored CPU performance over time using continuous timestamp analysis.
- Evaluated agent workload and resolution efficiency.

---

## 📷 Dashboard Preview

<img width="1329" height="762" alt="image" src="https://github.com/user-attachments/assets/d9aa81ae-6153-481e-842b-e67a255561b3" />
<img width="1326" height="749" alt="image" src="https://github.com/user-attachments/assets/a6144f4b-d2d4-441a-97cb-a6f628591b1f" />

---

## 🎯 What I Learned

- Building clean KPI cards with consistent formatting
- Creating 100% stacked charts for percentage distribution
- Using Continuous Date/Time axis for time-based analysis
- Structuring multi-page Power BI reports professionally
- Applying dashboard layout best practices

---

## 🚀 Future Improvements

- Add drill-through pages
- Implement dynamic time filters
- Optimize model performance
- Add anomaly detection for CPU spikes
