<a name="top"></a>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=A%2FB%20Testing%3A%20Landing%20Page&fontSize=32&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&pause=1000&color=F2C811&center=true&vCenter=true&width=650&lines=Statistical+Experimentation+%26+A%2FB+Testing;Python+%2B+Power+BI+Analytics;Conversion+Lift%3A+%2B51.18%25;Data-Driven+Decision+Making" />
</p>

> An end-to-end **A/B testing and business intelligence project** built with Python and Power BI to evaluate whether a new landing-page experience improves conversion and revenue compared with a Control experience.

The project combines **statistical experimentation, behavioral analysis, segmentation, DAX, interactive Power BI dashboards, and business decision-making** into a single portfolio-ready workflow.

<!-- TECH BADGES (static) -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/A%2FB%20Testing-Experimentation-blueviolet" />
  <img src="https://img.shields.io/badge/Statistics-Hypothesis%20Testing-success" />
</p>

<!-- LIVE REPO STATS — replace YOUR-USERNAME (and the repo name below if it differs) once pushed -->
<p align="center">
  <img src="https://img.shields.io/github/last-commit/Art-655/Landing-Page-Optimization-Analytics?style=flat-square" />
  <img src="https://img.shields.io/github/repo-size/Art-655/Landing-Page-Optimization-Analytics?style=flat-square" />
  <img src="https://img.shields.io/github/license/Art-655/Landing-Page-Optimization-Analytics?style=flat-square" />
  <img src="https://img.shields.io/github/stars/Art-655/Landing-Page-Optimization-Analytics?style=flat-square&color=yellow" />
</p>

---

## 📑 Table of Contents

- [📊 Project Overview](#project-overview)
- [🎯 Business Problem](#business-problem)
- [🧠 Analytical Approach](#analytical-approach)
- [📈 Power BI Dashboard](#powerbi-dashboard)
- [🧮 Key DAX Measures](#key-dax-measures)
- [🎨 Interactive UX](#interactive-ux)
- [⚡ Performance Analysis](#performance-analysis)
- [🛠️ Tools & Technologies](#tools-technologies)
- [📁 Repository Structure](#repository-structure)
- [📂 Project Documentation](#project-documentation)
- [🔍 Key Insights](#key-insights)
- [💼 Business Recommendation](#business-recommendation)
- [🚀 What This Project Demonstrates](#what-this-project-demonstrates)
- [🖼️ Dashboard Preview](#dashboard-preview)
- [👤 About the Developer](#about-the-developer)
- [📌 Final Project Status](#final-project-status)

---

<a name="project-overview"></a>
## 📊 Project Overview

The experiment compares two groups:

* **Control** — existing landing-page experience
* **Treatment** — new landing-page experience

The analysis focuses on:

* Conversion rate
* Conversion lift
* Revenue
* Session duration
* Pages visited
* Device performance
* Location performance
* Customer segmentation
* Statistical significance

### Experiment size

| Metric                   |                       Value |
| ------------------------ | --------------------------: |
| Total users              |                 **294,478** |
| Control users            |                 **146,926** |
| Treatment users          |                 **147,552** |
| Converted users          |                  **43,928** |
| Control conversion       |                  **11.87%** |
| Treatment conversion     |                  **17.95%** |
| Relative conversion lift |                 **+51.18%** |
| Absolute conversion lift | **+6.08 percentage points** |
| Conversion significance  |               **p < 0.001** |

### Executive result

> **Treatment outperformed Control.**

Conversion increased from **11.87% to 17.95%**, representing a **51.18% relative improvement**. The difference is statistically significant at **p < 0.001**.

Revenue also showed a statistically significant difference, while **session duration and pages visited did not show statistically significant differences**.

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="business-problem"></a>
## 🎯 Business Problem

A business has introduced a new landing-page experience and wants to determine whether it should replace the existing experience.

Simply observing that Treatment has a higher conversion rate isn't enough.

The analysis needs to answer:

1. Does Treatment actually improve conversion?
2. Is the improvement statistically significant?
3. Does the improvement translate into revenue?
4. Does Treatment behave consistently across devices and locations?
5. Did user engagement change?
6. Which segments respond best?
7. Should the business roll out Treatment?

This project addresses those questions through a combination of statistical analysis and interactive BI.

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="analytical-approach"></a>
## 🧠 Analytical Approach

The project follows four stages:

```text
Experiment
    ↓
Behavior & Segmentation
    ↓
Statistical Validation
    ↓
Business Decision
```

### 1. Experiment Analysis

Compare **Control vs Treatment** on the primary conversion outcome.

### 2. Behavioral & Segment Analysis

Investigate performance across:

* Device Type
* Location
* Age
* Gender
* Session Duration
* Pages Visited
* Purchase Amount

### 3. Statistical Validation

Statistical tests are used to determine whether observed differences are likely to represent genuine treatment effects.

Tests include:

* **Two-Proportion Z-Test** — Conversion
* **Welch's T-Test** — Revenue
* **Welch's T-Test** — Session Duration
* **Welch's T-Test** — Pages Visited

### 4. Business Decision

Translate the statistical findings into an actionable recommendation.

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="powerbi-dashboard"></a>
## 📈 Power BI Dashboard

The final Power BI report contains **four pages**.

<details>
<summary><strong>01 — Executive Experiment</strong> — click to expand</summary>

> **Did Treatment win?**

The executive page summarizes the experiment using:

* Control conversion rate
* Treatment conversion rate
* Conversion lift
* Revenue / visitor
* Statistical significance
* Comparison visuals

The page is designed for a stakeholder who needs the answer quickly.

![Executive Experiment](Power%20BI/Screenshots/01-executive-experiment.png)

</details>

<details>
<summary><strong>02 — Customer & Segment Intelligence</strong> — click to expand</summary>

> **Who responded, how did users behave, and where did Treatment perform best?**

Key analysis includes:

* Conversion by device
* Location ranking
* Location × Device heatmap
* Age vs purchase behavior
* Audience distribution

The page intentionally uses multiple visual types rather than relying exclusively on bar and column charts.

![Customer & Segment Intelligence](Power%20BI/Screenshots/02-customer-segment-intelligence.png)

</details>

<details>
<summary><strong>03 — Experiment & Statistical Analysis</strong> — click to expand</summary>

> **Can we trust the observed result?**

This page combines:

* Conversion funnel
* Statistical test summary
* Session-duration comparison
* Engagement vs purchase-value analysis

The statistical summary distinguishes between significant and non-significant outcomes.

| Metric           | Test                  | Result              |
| ----------------- | --------------------- | -------------------- |
| Conversion        | Two-Proportion Z-Test | **Significant**     |
| Revenue           | Welch's T-Test        | **Significant**     |
| Pages Visited     | Welch's T-Test        | **Not significant** |
| Session Duration  | Welch's T-Test        | **Not significant** |

![Experiment & Statistical Analysis](Power%20BI/Screenshots/03-experiment-statistical-analysis.png)

</details>

<details>
<summary><strong>04 — Decision Intelligence</strong> — click to expand</summary>

> **What should the business do?**

The final page converts the analysis into a business recommendation. It includes:

* Experiment winner
* Treatment conversion
* Conversion lift
* P-value
* Revenue significance
* Key findings
* Business recommendations
* Interactive Decomposition Tree

### Recommendation

> **Roll out the Treatment experience**, while continuing to monitor conversion and revenue after deployment.

The report also recommends continued experimentation and optimization using the strongest-performing segments identified during the analysis.

![Decision Intelligence](Power%20BI/Screenshots/04-decision-intelligence.png)

</details>

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="key-dax-measures"></a>
## 🧮 Key DAX Measures

<details>
<summary>View representative measures</summary>

```DAX
Total Users =
DISTINCTCOUNT(FactABTest[User ID])
```

```DAX
Conversion Rate =
DIVIDE(
    [Converted Users],
    [Total Users]
)
```

```DAX
Control Conversion Rate =
CALCULATE(
    [Conversion Rate],
    FactABTest[Group] = "control"
)
```

```DAX
Treatment Conversion Rate =
CALCULATE(
    [Conversion Rate],
    FactABTest[Group] = "treatment"
)
```

```DAX
Conversion Lift % =
DIVIDE(
    [Treatment Conversion Rate] -
    [Control Conversion Rate],
    [Control Conversion Rate]
)
```

```DAX
Conversion Lift (pp) =
[Treatment Conversion Rate] -
[Control Conversion Rate]
```

```DAX
Experiment Winner =
IF(
    [Treatment Conversion Rate] >
    [Control Conversion Rate],
    "Treatment",
    "Control"
)
```

The complete measure documentation is maintained separately in the repository.

</details>

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="interactive-ux"></a>
## 🎨 Interactive UX

The report includes:

### Navigation

Users can move between all four analytical pages through a consistent navigation system.

### Reset Filters

Interactive filtering can be reset to the intended default state.

### Dynamic Tooltips

Three report-page tooltip systems provide additional contextual information:

* **TT – Device**
* **TT – Location**
* **TT – Segment**

The tooltips respect the filter context of the hovered visual.

For example, hovering over **Mobile** displays Mobile-specific Control/Treatment conversion, lift, users, and revenue metrics rather than values from every device.

### Decomposition Tree

The final page includes an interactive decomposition tree for exploring conversion performance across dimensions such as:

```text
Group
 ↓
Device Type
 ↓
Location
 ↓
Gender
 ↓
Age Group
```

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="performance-analysis"></a>
## ⚡ Performance Analysis

Power BI Performance Analyzer was used to identify report bottlenecks rather than optimizing the dashboard blindly.

The main performance hotspot identified was:

> **Engagement vs Purchase Value**

The visual generated a relatively expensive query and sampled approximately 3,500 points.

The **Age vs Purchase Behavior** visual was not the primary bottleneck and was therefore left unchanged.

### Future optimization opportunity

If performance becomes a priority, the Engagement vs Purchase Value visual can be aggregated to a smaller analytical grain rather than plotting a large number of sampled points.

The finished report prioritizes preserving analytical value while documenting the known performance consideration.

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="tools-technologies"></a>
## 🛠️ Tools & Technologies

### Python

Used for:

* Data analysis
* Experiment validation
* Statistical testing
* Exploratory analysis
* Result preparation

### Power BI

Used for:

* Data modeling
* DAX
* Interactive dashboards
* Segmentation
* Statistical result presentation
* Tooltips
* Decomposition Tree
* UX/navigation

### Statistical Methods

* Two-Proportion Z-Test
* Welch's T-Test
* P-value analysis
* Conversion lift analysis

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="repository-structure"></a>
## 📁 Repository Structure

<details>
<summary>Click to expand folder tree</summary>

```text
Landing-Page-Optimization-Analytics
│   AB-Testing-README.md
│
├── Analysis
│       01_Data_Cleaning.ipynb
│       02_Exploratory_Data_Analysis.ipynb
│       04_Statistical_Analysis.ipynb
│
├── Dataset
│       AB Testing Data.csv
│
├── Documentation
│       Power_BI_Report_Documentation_AB_Testing.pdf
│
├── Output
│       cleaned_data.csv
│       experiment_summary.csv
│       hypothesis_test_results.csv
│
└── Power BI
    │   A-B testing.pbix
    │
    └── Screenshots
            01-executive-experiment.png
            02-customer-segment-intelligence.png
            03-experiment-statistical-analysis.png
            04-decision-intelligence.png
```

</details>

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="project-documentation"></a>
## 📂 Project Documentation

The repository should contain separate documentation for:

* **Data Model** — tables, relationships, and modeling decisions
* **DAX Measures** — calculated measures and their purpose
* **Power BI Report** — page-by-page dashboard documentation
* **Performance Analysis** — Performance Analyzer findings and optimization opportunities

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="key-insights"></a>
## 🔍 Key Insights

### 1. Treatment significantly improves conversion

| | Rate |
|---|---:|
| Treatment | **17.95%** |
| Control | **11.87%** |
| Relative lift | **+51.18%** |
| Absolute lift | **+6.08 pp** |

### 2. The conversion improvement is statistically significant

The conversion test produced **p < 0.001** — strong statistical evidence against the hypothesis that the two experiences have the same conversion rate.

### 3. Revenue also shows a significant difference

The revenue analysis produced a statistically significant result, supporting the business value of the Treatment experience beyond conversion alone.

### 4. Engagement did not materially change

Neither Session Duration nor Pages Visited showed statistically significant differences — the conversion improvement wasn't simply caused by users spending substantially more time on the site or visiting more pages.

### 5. Treatment performs strongly across devices

Treatment outperformed Control across Desktop, Tablet, and Mobile — the improvement isn't isolated to a single device category.

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="business-recommendation"></a>
## 💼 Business Recommendation

Based on the experiment results:

### **Recommend rolling out the Treatment experience.**

The decision is supported by:

* Higher conversion
* +51.18% relative conversion lift
* +6.08 percentage-point absolute lift
* p < 0.001 for conversion
* Statistically significant revenue difference
* Consistent device-level performance

After rollout, the business should continue monitoring:

* Conversion rate
* Revenue per visitor
* Segment performance
* Device performance
* Long-term stability of the observed uplift

The experiment should also serve as a baseline for future landing-page optimization tests.

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="what-this-project-demonstrates"></a>
## 🚀 What This Project Demonstrates

<details>
<summary>View skills demonstrated</summary>

* A/B testing
* Experimental design analysis
* Statistical hypothesis testing
* Python
* Pandas
* Statistical analysis
* Power BI
* Data modeling
* DAX
* KPI design
* Data visualization
* Segmentation
* Interactive dashboards
* Report-page tooltips
* Decomposition Trees
* Performance Analyzer
* Business intelligence
* Data-driven decision-making

</details>

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="dashboard-preview"></a>
## 🖼️ Dashboard Preview

### 01 — Executive Experiment
![Executive Experiment](Power%20BI/Screenshots/01-executive-experiment.png)

### 02 — Customer & Segment Intelligence
![Customer & Segment Intelligence](Power%20BI/Screenshots/02-customer-segment-intelligence.png)

### 03 — Experiment & Statistical Analysis
![Experiment & Statistical Analysis](Power%20BI/Screenshots/03-experiment-statistical-analysis.png)

### 04 — Decision Intelligence
![Decision Intelligence](Power%20BI/Screenshots/04-decision-intelligence.png)

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="about-the-developer"></a>
## 👤 About the Developer

**Arunraj Tawalke**

Aspiring Data Analyst passionate about transforming raw data into actionable business insights using **Power BI**, **SQL**, **Excel**, and **Python**.

* **GitHub:** [@Art-655](https://github.com/Art-655)
* **LinkedIn:** [arunraj-tawalke-5a079828a](https://www.linkedin.com/in/arunraj-tawalke-5a079828a/)
* **Email:** [rajtawalke2004@gmail.com](mailto:rajtawalke2004@gmail.com)

<div align="right"><a href="#top">⬆️ Back to top</a></div>

---

<a name="final-project-status"></a>
## 📌 Final Project Status

| Component            | Status     |
| --------------------- | ---------- |
| Experiment analysis   | ✅ Complete |
| Statistical testing   | ✅ Complete |
| Power BI model        | ✅ Complete |
| Dashboard             | ✅ Complete |
| 4 report pages        | ✅ Complete |
| Navigation            | ✅ Complete |
| Tooltips              | ✅ Complete |
| Reset/filter UX       | ✅ Complete |
| Performance analysis  | ✅ Complete |
| Documentation         | ✅ Complete |
| GitHub packaging      | 🚀 Ready   |

---

## Final takeaway

> **The Treatment landing-page experience significantly outperformed the Control experience, increasing conversion from 11.87% to 17.95% (+51.18% relative lift, p < 0.001). The evidence supports rolling out Treatment while continuing post-launch monitoring and iterative experimentation.**

---

## ⭐ If you found this project useful, consider giving it a star on GitHub! ⭐
