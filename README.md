# AI Chatbot Performance Analysis

A Tableau dashboard analyzing customer interactions with an AI chatbot to evaluate operational performance, customer experience, and drivers of sentiment.

This project explores how chatbot metrics such as **resolution rate, escalation rate, satisfaction, and response time** influence customer experience outcomes.

---

## Dashboard Preview

![AI Chatbot Dashboard](Executive_Summary.png)

Interactive dashboard available on Tableau Public:  
https://public.tableau.com/views/AIChatbotInteractionSummary_17710544931370/ExecutiveSummary
## Business Problem

Many companies deploy AI chatbots to reduce customer support costs and handle high volumes of customer queries. However, operational efficiency does not always translate into positive customer experience.

The objective of this project was to evaluate chatbot performance across three dimensions:

- **Customer Experience** (satisfaction and sentiment)
- **Operational Effectiveness** (resolution and escalation rates)
- **Operational Efficiency** (response time)

Understanding the relationship between these metrics helps organizations identify where chatbot improvements should be prioritized.

---

## Key Metrics

| Metric | Value | Interpretation |
|------|------|------|
| Resolution Rate | 84.9% | Most queries are resolved without human intervention |
| Escalation Rate | 10.1% | A smaller percentage of conversations require human agents |
| Avg Satisfaction | 3.1 / 5 | Moderate customer satisfaction |
| Avg Sentiment Score | 0.4% | Neutral customer sentiment overall |
| Avg Response Time | 5 seconds | Fast response performance |

While most queries seemed to be resolved by the AI Chatbot, the customer satisfaction and sentiment scores are low.

---

## Key Insights

### 1. High Resolution Rate Does Not Guarantee Customer Satisfaction

The chatbot successfully resolves nearly **85% of queries**, yet the average satisfaction rating remains only **3.1 out of 5**.

This suggests that while issues are technically resolved, the **quality of the interaction may not fully meet customer expectations**.

---

### 2. Escalated Conversations Show the Strongest Negative Sentiment

Escalated conversations consistently show lower sentiment compared to conversations resolved by the chatbot.

This indicates that customers requiring escalation may already be experiencing friction or frustration during the interaction.

---

### 3. Response Time Has Minimal Impact on Customer Sentiment

Analysis of sentiment versus response time shows **little correlation between response speed and sentiment outcomes**.

This suggests that **accuracy and resolution quality are more important drivers of customer satisfaction than speed alone**.

---

### 4. High-Volume Query Types Offer the Greatest Opportunity for Improvement

Customer satisfaction ratings are relatively similar across query types (between **3.1 and 3.2**).

However, query types with **higher conversation volumes** represent the largest opportunity for improving overall customer experience.

Improving performance in these categories would impact the greatest number of customers.

---

## Dashboard Components

The dashboard includes several visual components designed to highlight different aspects of chatbot performance:

| Section | Visualization Type | Purpose |
|------|------|------|
| KPI Overview | KPI Cards | Provide quick summary of chatbot performance |
| Escalation Trends | Line Chart | Show escalation rate changes over time |
| Resolution Trends | Line Chart | Track resolution rate stability |
| Satisfaction by Query Type | Horizontal Bar Chart | Compare satisfaction and conversation volume |
| Sentiment Drivers | Scatter Plot & Diverging Bars | Identify factors influencing sentiment |

---

## Tools Used

- **Tableau** – dashboard development and visualization
- **Data Visualization Principles**
- **Customer Experience Analytics**
- **Sentiment Analysis**
- **Customer Support Operations Metrics**

---

## Repository Contents

| File | Description |
|------|------|
| `README.md` | Project overview and insights |
| `Executive_Summary.png` | Screenshot of the Tableau dashboard |
| `ai_chatbot_interaction_dataset.xlsx` | Chatbot Interaction Dataset |

---

## Analytical Report

A full analytical report describing the dashboard design and insights is available here:

[View Report](report.pdf)

---

## Author

**Pratiti Soumya**  

Portfolio: https://datascienceportfol.io/prati  
Tableau Public: https://public.tableau.com/app/profile/pratiti.soumya/vizzes