# Personal Health Analytics Dashboard (FitnessKPIAnalytics)

**Status: In Progress**

FitnessKPIAnalytics is a personal project created for me and my friends to track our fitness journeys using a real analytics workflow instead of relying on generic fitness apps. I wanted a system that actually helped us understand how our habits affect our progress. By logging daily inputs like calories, protein, workouts, cardio, sleep, and energy, we can measure real consistency, compare results, and improve together. This project makes it easy for multiple people to generate their own logs, analyze progress, and stay accountable as a group.

This project follows a full lifecycle:  
**Daily logs → Python (clean + transform) → SQL (raw + clean) → Power BI dashboards → Machine Learning (later)**

---

## Questions This Project Answers
- How do daily habits influence weekly weight changes?
- How consistent am I with calories, protein, workouts, and recovery?
- Which behaviors have the strongest impact on outcomes?
- How do actual results compare to expected deficit-based projections?
- What patterns appear over multiple weeks or months of data?
- Can we predict future weight trends based on recent behavior? *(planned)*
- Which habits matter the most for progress consistency? *(planned)*

---

## Why I Built This
I built this project because I wanted a simple, reliable way for me and my friends to track our fitness goals without having to guess. Most apps only show surface-level data, and none of them explain why progress is happening or stalling. This system gives us clear KPIs, weekly summaries, and dashboards so we can see patterns, stay consistent, and help each other improve. It’s something we can all use daily, and I plan to keep expanding it as we collect more data.

---

## What This Project Delivers
- Structured Excel file for daily data logging
- Python scripts for data cleaning, validation, and transformation
- SQL raw, cleaned, and modeled tables for analytics
- Weekly KPI summaries focused on progress and consistency
- Power BI dashboards for long-term insight
- A system that multiple people can use for accountability and performance tracking
- **Machine learning predictive analytics planned for future phases**

---

## System Workflow
Daily logs → Python processing  
→ SQL tables (raw + clean + modeled)  
→ Weekly summaries → Power BI dashboards  
→ **ML predictions written back to SQL** *(planned)*

---

## Machine Learning (Phase 2)
Once enough data is collected, machine learning models will be used to generate predictive and behavioral insights:

### Planned Models
- **Weight Trend Forecasting (Regression / TensorFlow):** Predict next week's weight based on recent behavior patterns.
- **Behavior Impact Scoring (Feature Importance):** Identify which inputs (calories, protein, workouts, sleep, energy) influence results the most.
- **Consistency Recommendation Model:** Highlight personalized suggestions to improve outcomes.
- **Cluster Profiles:** Group people with similar behavior patterns or results.

### ML Stack
- **TensorFlow / Keras** — deep learning forecasting model
- **Scikit-Learn** — baseline linear & regression models for comparison
- **SQL** — storage of model outputs + versioning
- **Power BI** — visualize predictions, what-if scenarios, habit impact scoring

Outputs will write back to SQL, so the dashboard displays:
- *Expected next-week weight*
- *Actual vs predicted deltas*
- *Habits with the highest influence on progress*
- *Personalized improvement recommendations*

---

## Power BI Dashboard Plans
- Behavior Overview: calories, protein, workouts, cardio, sleep, energy
- Outcome Trends: weight trend, rolling averages, weekly changes
- Projection vs Reality: expected vs actual weekly change
- Insights: adherence rates, correlations, improvement signals
- **Predictive View (planned):** ML weight forecast, behavior importance ranking

---

## Tech Stack
- Python  
- SQL  
- Power BI  
- Streamlit  
- Excel  
- **TensorFlow / Scikit-Learn (planned)**

---

## Key Metrics
- Weekly average weight  
- Weekly calorie average  
- Protein consistency  
- Workout frequency  
- Cardio load  
- Adherence rates  
- Projected vs actual weekly change  
- Rolling averages  
- **Predicted next-week weight (planned)**  
- **Feature impact ranking (planned)**  

---

## Current Progress
- Idea created and README created

---

## Next Steps
- Daily Excel generator created  
- Python cleaning structure implemented  
- Build SQL raw and cleaned tables  
- Create weekly summary tables  
- Define KPIs for the modeled layer  
- Connect Power BI dashboard  
- Add correlation and behavior analysis  
- **Begin predictive modeling once enough data is collected**  

---

This project will continue evolving as more data is logged and stronger insights become possible. ML will be implemented after enough weekly history is available to generate reliable patterns.

