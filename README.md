# 🚀 A/B Testing Framework (Frequentist + Bayesian)

 **Production-Grade Experimentation Engine for Product Data Science
End-to-end A/B testing system combining experiment design, statistical inference,
Bayesian modeling, and automated decision logic — deployed via FastAPI.**

--- 
# 📌 Product Context

**Product teams constantly ask:**
- Did this feature improve engagement, conversion, or retention?

**Many experiments fail due to:**
- Underpowered design
- Misinterpreted p-values
- No standardized decision criteria
- Manual spreadsheet analysis
  
**This framework standardizes experimentation into a reproducible decision engine.**

---

# 🎯 What This Project Solves
**This system automates the full experimentation lifecycle:**
## ✅ Pre-Experiment
- Power analysis
- Sample size calculation
- Minimum Detectable Effect (MDE)
- Achieved power validation

## ✅ Post-Experiment
- Frequentist hypothesis testing
- Bayesian inference (PyMC)
- Effect size evaluation
- Risk-adjusted GO / CAUTION / NO-GO decision
---

**🧪 Real Product Use Case: Dark Mode Launch** 
- Primary Metric: Session Duration (continuous)
- Secondary Metric: Conversion Rate (binary)**

**Results:**
- T-test p-value = 0.001
- P(Variant > Control) = 98.5%
- Confidence Score = 87.5%

**Final Decision: GO**

---

# 🧠 Core Capabilities
**🔹 Power Analysis & Experiment Design**
- Detect 5% lift with 80% statistical power
- Cohen’s d / Cohen’s h effect sizes
- Continuous & binary metric support

# 🔹 Frequentist Testing
- Independent Samples T-Test
- Chi-Square Test
- Mann-Whitney U
- Confidence Intervals
- Assumption checks (Shapiro-Wilk, Levene)

# 🔹 Bayesian A/B Testing (PyMC)
- Posterior distributions
- P(Variant > Control)
- Highest Density Interval (HDI)
- Expected loss

---
# 🔹 Decision Engine
- GO       → Confidence ≥ 75%
- CAUTION  → 60–74%
- NO-GO    → < 60%

---

**Decision integrates:**
- Statistical significance
- Practical effect size
- Bayesian probability
- Risk tolerance
  
---
# 🚀 Quick Start
- git clone https://github.com/Denis0242/AB_test_with_stats.git
- cd AB_test_with_stats
- pip install -r requirements.txt
- python test_all.py
- python -m uvicorn app:app --reload

**Access:**

- API → http://localhost:8000
- Swagger Docs → http://localhost:8000/docs
  
 ---
 
# 📡 API Endpoints
| Endpoint                 | Purpose                  |
| ------------------------ | ------------------------ |
| `/api/v1/analyze`        | Full experiment analysis |
| `/api/v1/power-analysis` | Pre-experiment planning  |
| `/api/v1/analyze-csv`    | Upload CSV experiment    |
| `/api/v1/sample-data`    | Generate synthetic data  |


# 📁 Project Structure
```
AB_test_with_stats/
├── power_analysis.py
├── hypothesis_testing.py
├── bayesian_analysis.py
├── analysis_pipeline.py
├── app.py
├── test_all.py
├── requirements.txt
└── README.md
```

# 🧩 Product Data Science Skills Demonstrated
- Experiment design & A/B testing
- Power analysis & MDE planning
- Statistical inference
- Bayesian modeling (PyMC)
- Decision science
- FastAPI deployment
- Reproducible analytics pipelines

# 🔮 Future Improvements
- CUPED variance reduction
- Sequential testing
- Multi-armed bandits
- Uplift modeling

Built for scalable, rigorous experimentation in product organizations.

# Authur

**Denis Agyapong**

**Product Data Scientist/Data Analyst**
