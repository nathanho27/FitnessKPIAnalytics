# Personal Health Analytics Dashboard (FitnessKPIAnalytics)

**Status: In Progress**

FitnessKPIAnalytics is a personal project created for me and my friends to track our fitness journeys using a real analytics workflow instead of relying on generic fitness apps. I wanted a system that actually helped us understand how our habits affect our progress. By logging daily inputs like calories, protein, workouts, cardio, sleep, and energy, we can measure real consistency, compare results, and improve together. This project makes it easy for multiple people to generate their own logs, analyze their progress, and stay accountable as a group.

This project follows a full data lifecycle:  
**Daily logs → Python (clean + transform) → SQL (raw + clean + modeled) → Power BI dashboards**

---

## Questions This Project Answers
- How do daily habits influence weekly weight changes?
- How consistent am I with calories, protein, workouts, and recovery?
- Which behaviors have the strongest impact on outcomes?
- How do actual results compare to projected, deficit-based expectations?
- What patterns appear over multiple weeks or months of data?

---

## Why I Built This
I built this project because I wanted a simple, reliable way for me and my friends to track our fitness goals without guessing. Most apps only show the surface-level data, and none of them explain why progress is happening or stalling. This system gives us clear KPIs, weekly summaries, and dashboards so we can see patterns, stay consistent, and help each other improve. It’s something we can all actually use daily, and something I plan to keep expanding as we collect more data.

---

## What This Project Delivers
- Structured Excel file for daily data logging
- Python scripts for data cleaning, validation, and transformation
- SQL raw, cleaned, and modeled tables for analytics
- Weekly KPI summaries focused on progress and consistency
- Power BI dashboards for long-term insight
- A system that multiple people can use to track fitness and support each other

---

## Data Inputs
- Weight  
- Calories  
- Protein  
- Workouts  
- Cardio minutes/calories  
- Sleep rating  
- Energy rating  
- Notes  

---

## System Workflow
Daily log → Python processing → SQL tables (raw + clean + modeled)  
→ Weekly summaries → Power BI dashboards

---

## Power BI Dashboard Plans
- Behavior Overview: calories, protein, workouts, cardio, sleep, energy  
- Outcome Trends: weight trend, rolling averages, weekly changes  
- Projection vs Reality: expected vs actual weekly results  
- Insights: adherence rates, correlations, improvement signals  

---

## Tech Stack
- Python  
- SQL  
- Power BI  
- Streamlit  
- Excel  

---

## Key Metrics
- Weekly average weight  
- Weekly calorie average  
- Protein consistency  
- Workout frequency  
- Cardio load  
- Adherence rates  
- Projected vs actual weekly change  
- Rolling weight averages  

---

## Current Progress
- Idea created and readme created

---

## Next Steps
- Daily Excel generator created  
- Python cleaning structure implemented 
- Build SQL raw and cleaned tables  
- Create weekly summary tables  
- Define KPIs for the modeled layer  
- Connect Power BI dashboard  
- Add correlation and behavior analysis  
- Begin predictive modeling once enough data is collected  

---

This project will continue evolving as more data is logged and stronger insights become possible. I will do this after I finish the YelpBI

