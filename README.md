# daikibo-equality-audit
Excel-based classification of gender pay equality across Daikibo’s global factories
# ⚖️ Daikibo Gender Pay Equality Audit

This project investigates gender-based salary disparities across Daikibo’s global factories. Using equality scores provided by the client’s Forensics Tech team, roles were classified into three categories to highlight fairness and discrimination.

## 🧠 Objective
Classify job roles based on their equality score to support HR and leadership in identifying areas of concern.

## 📊 Classification Logic
- **Fair**: ±10
- **Unfair**: >10 or <–10
- **Highly Discriminative**: >20 or <–20

## 🧮 Formula Used
```excel
=IF(ABS([Equality Score])<=10,"Fair",IF(ABS([Equality Score])<=20,"Unfair","Highly Discriminative"))
🔍 Key Findings
Meiyo & Seiko factories showed the highest concentration of highly discriminative roles.

Berlin had the most balanced distribution, with several roles classified as Fair.

C-Level and VP roles in Meiyo scored –25 and –26, indicating severe inequality.

📁 Deliverables
Edited Excel file with Equality Class column

Summary write-up for portfolio use

📈 Future Work
Visualize classification trends using Tableau or Power BI

Recommend HR interventions based on role and location
