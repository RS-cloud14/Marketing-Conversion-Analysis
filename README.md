# 🧠 Marketing Conversion Analysis (A/B Testing)

## 📋 Project Overview
This project analyzes the impact of a marketing advertisement using **A/B testing** on over **588,000 users**.  
The goal is to evaluate whether exposure to an advertisement increases user conversion rates.

---

## 🎯 Objectives
- Measure the **conversion rate** difference between control and ad-exposed groups.  
- Test the **statistical significance** of the conversion difference using:
  - Chi-Square Test  
  - Simulation (Monte Carlo) Test  
- Provide **data-driven recommendations** for marketing strategy improvement.

---

## 📊 Dataset
- **Total users:** 588,000+  
- **Groups:** Control vs. Ad  
- **Main variable:** Conversion status (1 = converted, 0 = not converted)  
- Additional metadata: user IDs, timestamps, and group assignment.  

*(Dataset not included due to confidentiality.)*

---

## 🧰 Tools & Libraries
- **Python 3.9+**  
- **Libraries:**  
  - `pandas`  
  - `numpy`  
  - `matplotlib` / `seaborn`  
  - `scipy`  
  - `random`  

---

## ⚙️ How to Run
1. Clone this repository or download the `.ipynb` file.  
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Marketing_A_B_Testing.ipynb
   ```
4. Run all cells sequentially to reproduce the analysis and results.

---

## 📈 Key Findings
- The **ad-exposed group** achieved a **42% higher conversion rate** than the control group.  
- **Conversion rates:**  
  - Control group: **1.79%**  
  - Ad group: **2.55%**  
- Statistical validation:  
  - **Chi-Square Test:** p < 0.001  
  - **Simulation Test:** consistent significance confirmed  

---

## 💡 Insights & Recommendations
- Ads had a **statistically significant positive effect** on conversions.  
- Consider scaling ad exposure for similar audience segments.  
- Future improvements:
  - Segment analysis by demographic or engagement level.  
  - Apply Bayesian A/B testing for deeper probabilistic insights.

---

## 🧾 Author
**Tham Ren Sheng**  
Business Analytics Student | Marketing Data Analysis | Python & Statistics  
📧 renshengtham@gmail.com  
💼 [LinkedIn](www.linkedin.com/in/ren-sheng-tham-245649258)
