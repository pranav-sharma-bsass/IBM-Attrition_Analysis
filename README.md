# Why Do Employees Leave? — IBM HR Attrition Analysis

Ever wondered what actually makes people quit their jobs?  
Is it the money? The stress? Or just not feeling valued enough?

This project digs into publicly available IBM's HR dataset of **1,470 employees** to find out — using real statistical tests, not just gut feeling.

---

## What I Found

The company's attrition rate is **16.12%** — higher than the healthy benchmark of ~10%.  
But *who* is leaving, and *why*?

### Money matters — a lot
Employees who left were earning a mean of **₹4,787/month**.  
Those who stayed? **₹6,832/month**.  
That's nearly a ₹2,000 gap — and it's statistically significant (p = 0.000).

### Overworked = out the door
Employees with **bad work-life balance** showed the highest attrition.  
As balance improved from Bad → Good → Better → Best, attrition dropped consistently.  
The data backs what most of us already feel.

### Unhappy at work = looking elsewhere
Employees with **low job satisfaction** left at higher rates.  
Those with very high satisfaction? They stayed.  
Turns out feeling valued at work isn't just nice — it's a retention strategy.

---

## The Bigger Picture

These three factors don't work alone. They chain together:

**Low pay → can't afford to rest → poor work-life balance → low satisfaction → attrition**

Younger employees (15–25) and single employees showed the highest attrition —  
likely because they have less to lose and more to explore.  
Sales Representatives left the most. Research Directors, the least.

---

## How I Analysed This

| What I tested | Method used | Outcome |
|---|---|---|
| Does income differ between leavers and stayers? | Independent samples t-test | Yes — significantly (p = 0.000) |
| Is work-life balance linked to attrition? | Chi-square test | Yes — significantly (p = 0.001) |
| Is job satisfaction linked to attrition? | Chi-square test | Yes — significantly (p = 0.001) |

**Tools:** SPSS · Microsoft Excel  
**Dataset:** IBM HR Analytics (publicly available, 1,470 records)

---

## Report Structure

```
IBM-Attrition-Analysis/
│
├── report/
│   └── IBM Attrition Report.pdf
│
├── visualisations/
│   ├── income_vs_attrition.png
│   ├── worklife_vs_attrition.png
│   └── jobsatisfaction_vs_attrition.png
│
└── README.md
```

---

## What HR Should Do About It

**1. Hire more experienced employees**  
The data shows younger, early-career employees leave the most. Bringing in more experienced hires creates stability — they are less likely to leave on impulse and can mentor younger colleagues, improving overall retention.

**2. Better pay and career growth for younger employees**  
Employees in the lowest income bracket showed attrition rates nearly 30x higher than top earners. Competitive salaries and visible career progression paths act as strong pull factors — giving younger employees a reason to stay rather than explore elsewhere.

**3. Real work-life balance programmes — not just policies on paper**  
Bad work-life balance was the single strongest predictor of attrition in this analysis. Structured workshops, flexible working options, and manager training on workload distribution can meaningfully improve both employee retention and day-to-day productivity.

**4. Make work feel worth staying for**  
Low job satisfaction consistently drove attrition across all groups. Creating a more interactive, growth-oriented work environment — through mentorship, clear feedback, skill-building opportunities, and recognition — directly addresses the dissatisfaction that pushes employees out.

> These recommendations follow directly from the analysis. Each one maps to a statistically significant finding — not assumptions.

---

## Visualisations

![Salary vs Attrition](visualisations/Salary-vs-Attrition)
![Work-Life Balance vs Attrition](visualisations/Work-vs-Attrition)
![Job Satisfaction vs Attrition](visualisations/Satisfaction-vs-Attrition)

---

## Report

[Click here to view the full report](report/IBM-Attrition-Report.pdf)

---


*Made by Pranav Sharma · BS Analytics and Sustainability Studies · TISS Mumbai · Sem II*
