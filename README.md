![Project Cover](https://github.com/sidolawi85-lab/telco-BI-to-AI-churn-engine/blob/main/assets/thumbnails/Digital%20transformation%20in%20telco%20analytics.png)

# Revenue-Stabilization-System: Protecting Ksh 456K MRR via BI + AI Automation
### Turning churn insights into autonomous AI actions that protect recurring revenue

---

## 🚀 Project Overview

This project demonstrates the **transition from traditional Business Intelligence (BI) dashboards to production-ready AI automation** for a telecommunications provider.  

Instead of stopping at insights, this system **acts on churn risks automatically**, stabilizing Monthly Recurring Revenue (MRR) and improving customer retention while reducing manual effort.

---

## 📊 Dashboard Highlights

### Churn Overview
![Churn Overview](https://github.com/sidolawi85-lab/telco-BI-to-AI-churn-engine/blob/main/dashboard/dashboard_images/Telco%20project%20executive%20summary.png)
*Shows overall churn trends and the “6-Month Churn Cliff” where early cancellations spike.*

### Contract Churn
![Contract Churn](https://github.com/sidolawi85-lab/telco-BI-to-AI-churn-engine/blob/main/dashboard/dashboard_images/dashboard-growth.png)
*Highlights Month-to-Month subscribers as the highest churn risk segment.*

### Fiber Churn
![Fiber Churn](https://github.com/sidolawi85-lab/telco-BI-to-AI-churn-engine/blob/main/dashboard/dashboard_images/dashboard-retention.png)
*Reveals high-ARPU Fiber Optic customers at risk despite premium plans.*

> **Key Insight:** Early churn, unstable contracts, and high-value fiber users are the three biggest threats to recurring revenue.

---

## 🔍 Business Problems & AI Solutions

### 1️⃣ Early-Stage “Churn Cliff”

**Problem:**  
Sharp spike in cancellations within the first six months of customer tenure.

**AI Solution — Customer Lifecycle Retention System**  
- Classifies customers into *Onboarding* (0–90 days) and *Value Discovery* (91–180 days) phases  
- Sends automated, AI-generated emails and notifications to educate and activate users

![Customer Lifecycle Automation](https://github.com/sidolawi85-lab/telco-BI-to-AI-churn-engine/blob/main/automations/Customer%20Lifecycle%20Retention%20System.png)
*Automation monitors new joiners and triggers retention actions automatically.*

**Impact:** Reduces early churn while scaling customer success operations.

---

### 2️⃣ Month-to-Month Contract Vulnerability

**Problem:**  
Month-to-Month contracts are high-risk, creating unstable MRR.

**AI Solution — Contract Stability Engine**  
- Segments users into **Gold / Silver / Bronze** tiers based on spend and loyalty  
- Uses AI to generate personalized upgrade offers with price locks or long-term benefits

![BI to AI Flow](https://github.com/sidolawi85-lab/telco-BI-to-AI-churn-engine/blob/main/automations/Contract%20Stability%20Engine.png)
*Workflow showing how BI insights are transformed into AI-driven contract interventions.*

**Impact:** Protects 15–20% of MRR and replaces thousands of manual outreach tasks.

---

### 3️⃣ High-Value Fiber Optic Churn

**Problem:**  
Fiber users generate the highest revenue but show a **66% churn risk**, indicating service quality gaps.

**AI Solution — Fiber Experience Sentinel**  
- Detects “silent churners” before complaints arise  
- Tenured users receive automated diagnostics  
- New users get escalated to white-glove manual intervention

![Fiber Experience Sentinel](https://github.com/sidolawi85-lab/telco-BI-to-AI-churn-engine/blob/main/automations/Fiber%20Experience%20Sentinel.png)
*AI triggers proactive support actions to prevent high-value customer churn.*

**Impact:** Reduces manual workload by 80% and prevents revenue loss.

---

## 🧠 System Architecture

1. **BI Layer:** SQL-based churn analysis and segmentation  
2. **Decision Logic Layer:** Customer tiering and eligibility rules (JS logic)  
3. **AI Layer:** Gemini AI generates personalized communications  
4. **Automation Layer:** Orchestrated workflows trigger emails, diagnostics, and escalations

 ### 🛡️ Operational Guardrails (The Bouncer Logic)
Unlike standard bots, this system is 'Safe-to-Scale.' It uses 5 critical data gates 
before triggering an intervention:
- **CSAT Filter:** Only engages users with scores < 7.
- **Open Ticket Check:** Blocks automation if a technical issue is currently active (AZ Column).
- **Control Group:** Reserves 10% of users to measure true ROI/Lift.

---

## 🛠️ Tech Stack

- SQL & BI dashboards  
- JavaScript (Automation logic)  
- Gemini AI (Generative Decision Support)  
- n8n-style workflow orchestration  
- Markdown documentation for reproducibility  

---

## 🎯 Why This Project Matters

Most BI projects stop at insights. This project **acts on insights autonomously**, bridging the gap between **reporting → execution**. It’s a portfolio-ready example of:

- Analytics → automated action  
- Revenue protection through AI  
- Scalable customer retention strategies  

---

## 📌 Author

**Sydney Lawi**  
AI Automation • Business Intelligence • Marketing Intelligence


