# 🚀 A/B Testing Experimentation Framework 

### Product Analytics | Experimentation | Decision Science 

🌐 **Live App:** https://ab-test-with-stats.onrender.com 

🐙 **GitHub:**[AB-Testing-Experimentation-Framework](https://github.com/Denis0242/AB_test_with_stats)

---

## 📌 Executive Summary
End-to-end experimentation framework enabling product teams to analyze A/B tests, compute statistical significance, and make data-driven decisions.

---

## 🎯 Business Problem
Product teams need reliable experimentation systems to:
- Validate features
- Reduce risk
- Make data-driven decisions

---

## 📈 Key Metrics
- Conversion rate
- p-value
- Confidence interval
- Statistical significance

---

## 🔍 Analysis
- Hypothesis testing
- Power analysis
- Experiment simulation

---

## 💡 Insights
- Statistical significance determines feature success
- Sample size impacts decision reliability

---

## ✅ Recommendations
- Use proper sample size before launching experiments

---

## 🎯 Decision
- Ship / No Ship based on statistical significance

---

## 💰 Business Impact
- Reduces failed feature launches
- Improves product decision accuracy

---

## 🔌 API Preview

### Endpoint
POST /api/v1/analyze
{
  "users": 1000,
  "conversion_rate": 0.12
}
{
  "decision": "Ship",
  "p_value": 0.03
}

---

# ⚙️ Tools & Tech Stack
Python, FastAPI, Statsmodels

# ▶️ How to Run
uvicorn main:app --reload

---

# 📁 Project Structure
AB_test_with_stats/
│── main.py
│── api/
│── README.md


# Author

**Denis Agyapong**
