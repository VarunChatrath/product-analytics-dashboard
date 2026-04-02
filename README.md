# 📊 Product Analytics Dashboard

This project focuses on analyzing user engagement and platform adoption for an analytics platform using Power BI. The objective is to understand how users interact with different features, identify behavioral patterns, and detect key drop-off points in the user journey.

---

## 🔍 Project Overview

The dashboard provides a comprehensive view of:

- User activity and engagement trends
- Feature usage across different stages
- Funnel progression from Login to Export
- Differences between Free and Pro users
- Identification of highly engaged (power) users

The dataset used in this project was manually generated to simulate realistic user behavior, ensuring meaningful insights rather than random patterns.

---

## 📊 Dashboard Structure

### 🟦 1. Executive Overview
- Key KPIs: Total Users, DAU, Sessions, Avg Session Duration, Engagement %
- Feature usage distribution
- User growth trends over time
- Country-wise user distribution
- Free vs Pro user segmentation
- Interactive slicers for dynamic filtering

---

### 🟦 2. User Journey & Behavior Analysis
- Funnel analysis (Login → Data Upload → Cleaning → EDA → ML → Export)
- Drop-off identification across stages
- Feature usage comparison by plan type
- Session trends and activity patterns
- Session duration distribution
- Power user identification

---

## 📈 Key Insights

- Total users: **467**, with ~**325 DAU (~70% engagement rate)**
- Over **3000+ sessions** with consistent activity levels
- Strong initial engagement at Login and Data Upload (~325 events each)
- Significant drop-off of ~**47%** from Data Cleaning (214 users) to EDA (113 users)
- Only ~**4% users (14 users)** complete the full funnel till Export
- Majority users (~**71%**) are on Free plan
- Around **31 users (~6–7%)** contribute significantly as power users
- Daily sessions fluctuate between **20–45 sessions**, indicating varying engagement

---

## 🧠 Data Model

The data model consists of the following tables:

- **Users** → User information (country, plan type, signup date)
- **Events** → User actions across platform features
- **Sessions** → Session-level activity (login time, duration)
- **Features** → Platform feature mapping
- **Date** → Time-based analysis support

Relationships are designed to ensure clean filtering and avoid ambiguity.

---

## 🛠 Tools & Technologies

- Power BI (Data Modeling, DAX, Visualization)
- Microsoft Excel (Data generation)
- DAX (Measures and calculations)

---

## 📁 Files Included

- `Product_Analytics_Dashboard (.pbix)`
- `Dataset (Excel)`
- `Theme 1 – Documentation (PDF)`
- `Theme 2 Secure Document Access in Power BI – Design Proposal (PDF)`
- `ER Diagram (PNG)`
- `Executive Overview (PNG)`
- `User Journey & Behaviour Analysis (PNG)`

---

## 🎯 Key Highlights

- Designed a realistic synthetic dataset with funnel logic and behavioral patterns
- Built an end-to-end analytics dashboard with business-focused insights
- Identified critical drop-off points in user journey
- Demonstrated strong understanding of data modeling and user behavior analysis

---

## 📌 Note

Due to limitations in the free Power BI service, a demo video has been provided to showcase the dashboard functionality and interactions.

---

## 🙋‍♂️ Author

**Varun Chatrath**
