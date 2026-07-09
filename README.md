<div align="center">

# 🩸 Wadzire Village Blood Group Analysis Dashboard

### Interactive Power BI Dashboard for Community Health Data Analysis

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-blue?style=for-the-badge&logo=googleanalytics&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

[![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=flat-square)](#)
![Views](https://komarev.com/ghpvc/?username=GADEKAR328&label=Repo%20Views&color=red&style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/GADEKAR328/Blood-Group-Analysis-Dashboard-PowER-BI?style=flat-square)
![Repo Size](https://img.shields.io/github/repo-size/GADEKAR328/Blood-Group-Analysis-Dashboard-PowER-BI?style=flat-square)
[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-View%20on%20Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://app.powerbi.com/links/tyXQjjOs90?ctid=56c1d497-700b-49cf-8f8d-3dd6b20d522f&pbi_source=linkShare)

**Author:** Yogesh Gadekar

</div>

---

## 📸 Dashboard Preview

<div align="center">
  <img src="https://raw.githubusercontent.com/GADEKAR328/Blood-Group-Analysis-Dashboard-Power-BI/eb7eafb4c88c439f902887104f3e94f39484e859/Blood%20Group%20Analysis%20Dashboard.jpg" alt="Wadzire Village Blood Group Dashboard Preview" width="100%">
</div>

<div align="center">

### 🔴 [**View the Live Interactive Dashboard on Power BI →**](https://app.powerbi.com/links/tyXQjjOs90?ctid=56c1d497-700b-49cf-8f8d-3dd6b20d522f&pbi_source=linkShare)

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Dashboard KPIs](#-dashboard-kpis)
- [Visual Components](#-visual-components)
- [Blood Group Reference Chart](#-blood-group-reference-chart)
- [Tech Stack](#-tech-stack)
- [Data Model](#-data-model)
- [Key Insights](#-key-insights)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)
- [License](#-license)

---

## 🧭 Overview

The **Wadzire Village Blood Group Analysis Dashboard** is an interactive **Power BI** report built to analyze and visualize the blood group distribution of **5,200 residents** of Wadzire village. It provides real-time filtering by **Gender** and **Age Group**, surfaces population-level health statistics (Rh factor, universal donors/recipients), and presents a clean, medically-themed reference guide for blood group compatibility.

This project was designed to demonstrate **end-to-end dashboard development** — from a synthetic dataset, through data modeling and DAX measures, to a polished, recruiter-ready visual story.

**Goals of this project:**
- Practice building KPI cards, donut charts, stacked bar charts, and dynamic tables in Power BI
- Apply DAX for calculated measures (Gender Ratio, Rh Counts, Universal Donor/Recipient logic)
- Design a cohesive, high-contrast visual theme suited for public health reporting
- Simulate a real-world community health analytics use case

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🎛️ **Dynamic Filters** | Slice data instantly by `Gender` and `AgeGroup` |
| 📊 **KPI Cards** | 7 headline metrics updated live with filter selections |
| 🍩 **Donut Chart** | Blood group distribution across the entire population |
| 📶 **Stacked Bar Charts** | Blood group breakdown by Gender and by Age Group |
| 📋 **Searchable Data Table** | Individual-level record view (ID, Name, Gender, Age, Blood Group) |
| 🧬 **Compatibility Reference Grid** | Antigen/antibody chart for Groups A, B, AB, O |
| 🏠 **Navigation Icon** | Home button for multi-page report navigation |
| 🎨 **Custom Theme** | High-contrast red & gold branding for visual impact |

---

## 📈 Dashboard KPIs

| Metric | Value |
|---|---|
| 👥 Total People | **5,200** |
| 🧔 Total Male | **2,600** |
| 👩 Total Female | **2,600** |
| 🩸 Most Common Blood Group | **O+** |
| ⚖️ Gender Ratio (M:F) | **1.00** |
| ➕ Rh Positive Count | **4,764** |
| ➖ Rh Negative Count | **436** |
| 🟢 Universal Donor Count (O−) | **149** |
| 🔵 Universal Recipient Count (AB+) | **346** |

---

## 🧩 Visual Components

### 1. Blood Group Distribution (Donut Chart)
Shows the overall percentage split of all 8 blood groups across the village:

| Blood Group | Share |
|---|---|
| O+ | 36% |
| B+ | 29% |
| A+ | 20% |
| AB+ | 7% |
| O− | 3% |
| B− | 2% |
| A− | ~1–2% |
| AB− | ~1% |

### 2. Blood Group by Gender (Horizontal Bar Chart)
Compares male vs. female counts for each blood group, sorted from most to least common — highlighting that **O+, B+, and A+** dominate the population regardless of gender.

### 3. Total People by Age Group and Blood Group (Stacked Column Chart)
Breaks down blood group composition across five life stages: `Minor`, `18–30`, `31–45`, `46–60`, and `60+`, useful for spotting generational health/demographic patterns.

### 4. Individual Records Table
A scrollable, sortable table listing every resident with their `ID`, `Name`, `Gender`, `Age`, and `BloodGroup` — enabling drill-through to person-level detail.

---

## 🧬 Blood Group Reference Chart

A built-in educational panel summarizing blood typing biology, included directly in the dashboard for viewer context:

| | Group A | Group B | Group AB | Group O |
|---|---|---|---|---|
| **Antibodies in Plasma** | Anti-B | Anti-A | None | Anti-A and Anti-B |
| **Antigens on Red Cells** | A antigen | B antigen | A and B antigens | None |

> This panel doubles as a quick-reference guide for understanding **donor/recipient compatibility** — reinforcing why **O−** is the universal donor and **AB+** is the universal recipient.

---

## 🛠️ Tech Stack

- **Visualization Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Power Query (M) for data shaping
- **Calculations:** DAX (Data Analysis Expressions)
- **Data Source:** Synthetic/self-generated dataset (5,200 simulated resident records)
- **Design:** Custom red & gold theme, card visuals, donut & bar charts, matrix/table visuals

---

## 🗂️ Data Model

The dataset simulates individual resident records with the following schema:

```
Residents Table
├── ID            (Integer, Primary Key)
├── Name           (Text)
├── Gender         (Text: Male / Female)
├── Age            (Integer)
├── AgeGroup       (Text: Minor / 18-30 / 31-45 / 46-60 / 60+)
└── BloodGroup     (Text: O+, O-, A+, A-, B+, B-, AB+, AB-)
```

**Sample DAX measures used:**

```dax
Total People = COUNTROWS(Residents)

Gender Ratio (M:F) =
DIVIDE(
    CALCULATE(COUNTROWS(Residents), Residents[Gender] = "Male"),
    CALCULATE(COUNTROWS(Residents), Residents[Gender] = "Female")
)

Rh Positive Count =
CALCULATE(COUNTROWS(Residents), RIGHT(Residents[BloodGroup], 1) = "+")

Rh Negative Count =
CALCULATE(COUNTROWS(Residents), RIGHT(Residents[BloodGroup], 1) = "-")

Universal Donor Count =
CALCULATE(COUNTROWS(Residents), Residents[BloodGroup] = "O-")

Universal Recipient Count =
CALCULATE(COUNTROWS(Residents), Residents[BloodGroup] = "AB+")
```

---

## 🔍 Key Insights

- **O+ is the dominant blood group**, making up over a third (36%) of the village population — consistent with common global distribution patterns.
- **Rh-positive individuals (91.6%)** vastly outnumber Rh-negative individuals (8.4%), meaning Rh-negative donors are a comparatively scarce and valuable resource locally.
- **Perfect gender balance** (1:1 ratio) in the sample makes it ideal for unbiased demographic comparison.
- Only **149 residents (2.9%)** are universal donors (O−) versus **346 residents (6.7%)** who are universal recipients (AB+) — useful for local blood bank planning and awareness drives.
- Blood group proportions remain **fairly consistent across all age groups**, suggesting no major generational skew in this simulated dataset.

---

## 🚀 How to Use

**Quick Look:** Prefer not to install anything? [**Open the live interactive dashboard**](https://app.powerbi.com/links/tyXQjjOs90?ctid=56c1d497-700b-49cf-8f8d-3dd6b20d522f&pbi_source=linkShare) directly in your browser — filter, hover, and explore just like the original.

**Run it locally:**

1. **Clone this repository**
   ```bash
   git clone https://github.com/GADEKAR328/Blood-Group-Analysis-Dashboard-PowER-BI.git
   ```
2. **Open the `.pbix` file** in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download).
3. Use the **Gender** and **AgeGroup** slicers at the top to filter the entire report interactively.
4. Hover over any chart to see tooltips with exact counts and percentages.
5. (Optional) Publish to **Power BI Service** to share a live, web-based version of the report.

---

## 📁 Project Structure

```
Blood-Group-Analysis-Dashboard-PowER-BI/
│
├── data/
│   └── wadzire_blood_group_data.csv   # Source dataset (synthetic)
│
├── Blood Group Analysis Dashboard.jpg   # Dashboard screenshot (used in README preview)
├── Blood Group Analysis Dashboard.pbix  # Main Power BI file
├── README.md
└── LICENSE
```

---

## 🔮 Future Enhancements

- [ ] Add a village map view (drill-through by household/ward)
- [ ] Integrate real anonymized survey data with proper consent
- [ ] Add year-over-year trend analysis if longitudinal data becomes available
- [ ] Publish a live Power BI Service link for public viewing
- [ ] Add a mobile-optimized report layout

---

## 👤 Author

**Yogesh Gadekar**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yogesh-gadekar-a1231b189/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GADEKAR328)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=aboutdotme&logoColor=white)](https://ysganalyst-portfolio-gem.lovable.app/)


---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and share with attribution. See the [LICENSE](LICENSE) file for details.

---

<div align="center">

⭐ **If you found this project useful or interesting, consider giving it a star!** ⭐

</div>
