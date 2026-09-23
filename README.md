<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Hey%2C%20I'm%20Prince%20%F0%9F%91%8B&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Data%20Analyst%20%7C%20Ex-Pharma%20Key%20Account%20Manager%20%7C%20Turning%20Business%20Problems%20Into%20SQL%20Queries&descAlignY=58&descSize=16" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=Python+%C2%B7+SQL+%C2%B7+Power+BI;3+Years+Pharma+Commercial+Experience;From+Territory+P%26L+to+Dashboards" alt="Typing SVG" />

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=prince2310-97&label=Profile%20Views&color=6C63FF&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/prince2310-97?label=Followers&style=for-the-badge&color=6C63FF" />

</div>

<br/>

## 🙋 About Me

```python
class PrinceKumar:
    def __init__(self):
        self.role        = "Data Analyst"
        self.background  = "3 Years @ Wockhardt Pharmaceuticals — Key Account Management"
        self.now_doing   = "Applying commercial/B2B instinct to data-driven analysis"
        self.stack       = ["Python", "SQL", "Power BI", "DAX", "Excel"]
        self.focus_areas = ["Territory & Sales Effectiveness", "Account Profitability",
                             "Healthcare Operations Analytics"]

    def superpower(self):
        return "Turning messy business data into decisions that hold up under scrutiny 💡"
```

> 🏆 3 years of B2B / Key Account Management experience in pharmaceutical commercial operations — managing distributor relationships and healthcare accounts.
> Now channeling that same commercial instinct — territory economics, account profitability, rep performance — into data analysis with Python, SQL, and Power BI.

<br/>

## 🚀 Featured Projects

<table>
<tr>
<td width="33%" valign="top">

### 💊 Pharma Sales Effectiveness

**Territory & rep-level commercial diagnostic**

`Python` `SQL` `Power BI`

<img src="https://img.shields.io/badge/Revenue-₹84.12M-6C63FF?style=flat-square" /><br/>
<img src="https://img.shields.io/badge/Marketing_ROI-5.11-6C63FF?style=flat-square" /><br/>
<img src="https://img.shields.io/badge/Reps-20-6C63FF?style=flat-square" />

**Top finding:** East territory conversion at 0.87 vs. 0.95 avg — dipped below the 0.80 risk threshold in Q1

[**→ View Repo**](https://github.com/prince2310-97/pharma_sales_effectiveness_analysis)

</td>
<td width="33%" valign="top">

### 🛒 Retail Profitability Diagnostic

**Cost-to-serve & KAM tier classification**

`Python` `SQL` `Power BI`

<img src="https://img.shields.io/badge/Sales-$1.92M-F2994A?style=flat-square" /><br/>
<img src="https://img.shields.io/badge/Loss_Found-$291.45K-F2994A?style=flat-square" /><br/>
<img src="https://img.shields.io/badge/Loss_Txns-48.98%25-F2994A?style=flat-square" />

**Top finding:** Only 2 of 1,952 transactions carry >10% discount — small-order cost-to-serve, not discounting, drives the losses

[**→ View Repo**](https://github.com/prince2310-97/retail-key-account-profitability-analysis)

</td>
<td width="33%" valign="top">

### 🏥 Medical No-Show Analysis

**Statistical EDA on 110K+ appointments**

`Python` `SciPy`

<img src="https://img.shields.io/badge/Appointments-110%2C519-27AE60?style=flat-square" /><br/>
<img src="https://img.shields.io/badge/No--Show_Rate-20.19%25-27AE60?style=flat-square" /><br/>
<img src="https://img.shields.io/badge/SMS_Effect-up_to_--7.2pp-27AE60?style=flat-square" />

**Top finding:** SMS reminders associated with lower no-shows — effect strengthens as wait time grows

[**→ View Repo**](https://github.com/prince2310-97/Medical_appointment_No_Show_Analysis)

</td>
</tr>
</table>

<details>
<summary><b>💊 Pharma Sales Effectiveness & Territory Optimization — full breakdown</b></summary>
<br/>

**Dataset:** 720 records (12 months × 20 reps × 3 products), FY 2024–25 (Apr 2024–Mar 2025), synthetic
**Tools:** Python (Pandas, Matplotlib, Seaborn) · SQL · Power BI (DAX)

| Highlight | Finding |
|-----------|---------|
| 📍 North Territory | ₹24.5M revenue — strongest primary + secondary balance |
| ⚠️ East Territory | Conversion ratio 0.87 vs. 0.95 portfolio avg; dipped below 0.80 threshold in Q1 — channel inventory pressure indicator (directional, not conclusive) |
| 🌟 Star Performer | Ravi Menon (South) — 124% target achievement, highest of all 20 reps |
| 🔴 PIP Candidate | Manoj Roy (East) — 69% target achievement, lowest of all 20 reps |
| 📦 Wokderm Plus | Q4 primary push without proportionate secondary offtake — localized inventory risk, not confirmed stuffing |
| 📈 Marketing ROI | **5.11** overall (Revenue ÷ Marketing Spend) · North 5.95 (best) · East 3.97 (worst) |

**Business impact:** Flagged East territory for an ABM review and inventory audit, identified a structured PIP candidate, and recommended reallocating marketing spend from East toward North/South based on ROI.

</details>

<details>
<summary><b>🛒 Retail Key Account Profitability Diagnostic — full breakdown</b></summary>
<br/>

**Dataset:** SuperStore US (public), H1 2015 (Jan–Jun 2015) — 1,952 transactions, 1,130 customers
**Tools:** Python (Pandas, Matplotlib, Seaborn) · SQL · Power BI (DAX) · Excel (source data)

| Highlight | Finding |
|-----------|---------|
| 💸 Loss Transactions | **48.98%** of 1,952 transactions are loss-making — $291.45K lost within $1.92M sales |
| 📦 Not a discounting problem | Only 2 of 1,952 transactions carry >10% discount (r ≈ -0.06 to profit). Loss transactions average $590 vs. $1,366 for profitable ones — small-order **cost-to-serve** is the real driver |
| 📍 South Region | Net loss at -4.04% margin, highest loss-transaction rate (52.71%) |
| 🏆 Central Region | Best performer at 17.26% margin |
| 🪑 Furniture | Structurally lowest-margin category (~9%) — a base pricing/cost issue, not discounting |
| 📉 Office Machines | Most loss-making sub-category (-$67,907); single biggest loss-making product is the Polycom ViewStation ISDN Videoconferencing Unit (-$27,621) |
| 🎯 KAM Tiers (1,130 customers) | 141 Strategic Core · 53 Margin Risk · 539 Loss-Making (47.7%) · 397 Standard |
| 📈 Profit Concentration | 156 of 591 profitable customers (26.4%) generate 80% of total profit |
| 🔎 Flagged Accounts | 370 high-discount/low-margin accounts identified; Technology shows the deepest loss within this group (-49.38% margin) |
| 👤 Segment Mix | Corporate drives the largest revenue share (34.18%) |

**Business impact:** Recommended a minimum order value threshold to address small-order cost-to-serve, a South region profitability review, base pricing review for Furniture, and dedicated KAM coverage for the 141 Strategic Core accounts.

</details>

<details>
<summary><b>🏥 Medical Appointment No-Show Analysis — full breakdown</b></summary>
<br/>

**Dataset:** Kaggle Medical Appointment No-Show (Brazil, 2016) — 110,527 raw appointments, 110,519 after cleaning; Apr–Jun 2016
**Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy) · Jupyter Notebook

| Highlight | Finding |
|-----------|---------|
| 📋 Overall No-Show Rate | ~20.19% across 110,519 cleaned appointments |
| 📱 SMS Reminders | Associated with lower no-show rates across wait-time groups once stratified (the unconditional comparison is confounded by same-day appointments, which never receive an SMS); effect grows from -0.6pp to **-7.2pp** at 15+ day waits |
| 👶 Age | 18–34 is the highest-risk group (23.98% no-show); rate falls steadily to 15.30% for 60+ |
| ⏳ Wait Time | Longer scheduling windows independently associated with higher no-show, on top of the SMS effect |
| 🩺 Chronic Conditions | Patients with hypertension/diabetes/alcoholism show up *more* reliably (17.77% vs. 20.91%) |
| 💳 Scholarship | Subsidy recipients no-show more often (23.74% vs. 19.81%) — a socioeconomic access signal |

**Business impact:** Recommended prioritizing SMS budget toward longer-wait appointments (where the association is strongest), targeted engagement for 18–34-year-olds, and a review of high-no-show neighbourhoods — framed as pilot hypotheses from a correlational analysis, not proven causal effects.

</details>

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages & Databases**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)

**Analytics & Visualization**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

**Python Libraries**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3c6e71?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

</div>

<br/>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=prince2310-97&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="180" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prince2310-97&layout=compact&theme=tokyonight&hide_border=true" height="180" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=prince2310-97&theme=tokyonight&hide_border=true" width="70%" />

</div>

<br/>

## 📬 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Prince%20Kumar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/princekr2310)
[![Gmail](https://img.shields.io/badge/Gmail-princerv0011%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:princerv0011@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-View%20My%20CV-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://drive.google.com/file/d/1h3QRcEfKbf3Bzuc0ffNIAmCLqaeXzs1c/view?usp=drive_link)

</div>

<br/>

<div align="center">

⚡ *"I like solving real-world business problems using data — not just building models."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
