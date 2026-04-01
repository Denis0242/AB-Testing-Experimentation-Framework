# 🚀 A/B Testing & Experimentation Framework 

### Product Analytics | Experimentation | Decision Science 

🌐 **Live App:** https://ab-test-with-stats.onrender.com 

🐙 **GitHub:**[AB-Testing-Experimentation-Framework](https://github.com/Denis0242/AB_test_with_stats) 

---

## 🎯 Product Decision Focus
**Should we launch this feature?** 
This project simulates how product teams evaluate whether a new feature improves key metrics such as engagement, conversion, or retention using A/B testing. It also evaluate feature launches using frequentist and Bayesian A/B testing, power analysis, and KPI comparison. It goes beyond statistical analysis to provide **data-driven product decisions** (go / caution / no-go).

--- 
## 📌 Business Problem
Product teams frequently launch features without rigorous experimentation, leading to: 
- Misleading results due to poor test design
- Underpowered experiments
- Incorrect interpretation of metrics
- Increased risk of negative product impact This project solves this by creating a **standardized experimentation framework** that supports reliable decision-making.
       
  ---

  ## 🧠 Approach
  ### 🔹 Pre-Experiment Design
-  Power analysis & sample size estimation
-  Minimum Detectable Effect (MDE) calculation
-  Experiment setup for continuous & binary metrics 

### 🔹 Post-Experiment Evaluation
- Control vs Treatment comparison
- Hypothesis testing (Frequentist)
- Bayesian probability of improvement
- Effect size & confidence interval analysis
        
### 🔹 Decision Layer (KEY DIFFERENTIATOR)
- Automated recommendation:
- ✅ Go (positive impact)
- ⚠️ Caution (inconclusive)
- ❌ No-Go (no improvement or negative impact)
   
--- 

## 📊 Example Product Use Case 
A product team tests whether a new feature improves user engagement. 
- **Primary Metric:** Session Duration
- **Secondary Metric:** Conversion Rate 👉 Instead of just reporting results, this framework answers: **“Should we launch this feature?”**
--- 

## 📈 Product Metrics
- Conversion Rate
- Engagement (Session Duration)
- Retention Signals
- KPI performance comparison (Control vs Treatment)
  
--- 
## 📌 Business Impact
- Enables **data-driven feature launch decisions**
- Reduces risk of deploying low-impact or harmful features
- Improves experimentation rigor and consistency
- Bridges the gap between **statistics and product decisions**
- Simulates real-world workflows used by product analytics teams
----  

## 🛠️ Tools & Technologies 
- Python - FastAPI
- NumPy, SciPy, Statsmodels
- PyMC (Bayesian Analysis)
- Uvicorn 

--- 
## 🚀 How to Run Locally 
- git clone https://github.com/Denis0242/AB_test_with_stats.git
- cd AB_test_with_stats - pip install -r requirements.txt
- python -m uvicorn app:app --reload
- API: http://localhost:8000
- Docs: http://localhost:8000/docs 

 -----
 
## 📁 Project Structure
AB_test_with_stats/
├── app.py
├── analysis_pipeline.py
├── power_analysis.py
├── hypothesis_testing.py
├── bayesian_analysis.py
├── data_loader.py
├── test_all.py
├── requirements.txt
└── README.md

-----



## ✅ Skills Demonstrated
- A/B Testing & Experimentation
- Hypothesis Testing (Frequentist & Bayesian)
- Power Analysis & MDE Planning
- KPI Design & Evaluation
- Product Analytics
- Decision Science
- API-based Analytics Deployment
---

# 🔮 Future Improvements
- CUPED variance reduction
- Sequential testing
- Multi-armed bandits
- Uplift modeling
---

# 💡 Why This Project Matters
This project reflects how Product Data Analysts work in real environments:
- Not just analyzing data
- But driving product decisions using experimentation
- Many teams run experiments but stop at p-values. This framework goes further by connecting statistical outputs to real product decisions, helping teams decide whether a feature should launch, be iterated on, or be rolled back.
---

# 👤 Author

**Denis Agyapong**
**Product Data Analyst | 2+ yrs Product Analytics | 4+ yrs Healthcare Analytics**
