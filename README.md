# Customer-Satisfaction-Support-Performance-Analysis
End-to-end customer support analytics project analyzing satisfaction drivers, resolution time impact, and channel performance using Python and Tableau.


## 📌 Project Overview
This project analyzes customer support ticket data to identify key factors influencing customer satisfaction. 
The focus is on resolution time, ticket channel, ticket type, and operational efficiency.

## 🎯 Business Objectives
- Understand drivers of customer satisfaction (ratings 1–5)
- Analyze the impact of resolution time on satisfaction
- Compare satisfaction across support channels
- Identify high-volume and high-risk ticket types
- Deliver insights for improving customer support operations

## 🧰 Tools & Technologies
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Tableau
- Excel

## 📊 Dataset Summary
- **Records:** 8,469 customer support tickets  
- **Features:** 18  
- **Target Variable:** Customer Satisfaction Rating (1–5)  
- ~67% ratings missing (feedback collected post resolution)

## 🔧 Data Preprocessing
- Converted date & time columns to proper datetime formats  
- Created `Resolution_Hours` feature  
- Handled missing satisfaction ratings logically  
- Filtered resolved tickets for satisfaction analysis  

## 📈 Key Analysis & Insights
- Customer satisfaction decreases as resolution time increases  
- Chat channel shows slightly higher average satisfaction  
- High-priority and technical issues receive lower ratings  
- Email and phone channels dominate ticket volume  
- Resolution speed is the strongest driver of satisfaction  

## 📊 Tableau Dashboard
Interactive dashboard includes:
- Satisfaction rating distribution  
- Satisfaction by ticket channel  
- Resolution time vs satisfaction  
- Ticket volume by type  

![Dashboard](images/customer_satisfaction_dashboard.png)

## 👩‍💻 Role
**Data Analyst Intern**  
Performed EDA, feature engineering, visualization, and business insight generation.

## 🚀 Future Enhancements
- Machine learning model to predict customer satisfaction  
- SLA-based performance monitoring  
- Real-time dashboard integration
