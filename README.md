# 🩸 Blood Donation Analytics Project

> A comprehensive data analytics project exploring blood donor demographics, geographic distribution, eligibility trends, and donation patterns across India — built with Excel and interactive dashboards.

---

## 📌 Project Overview

This project analyzes a dataset of **10,000 blood donors** across **20 cities** and **15 states** in India. It uncovers actionable insights about donor eligibility, blood group distribution, medical conditions affecting donation, and center-wise performance — all visualized through an interactive Excel dashboard.

Whether you're a healthcare analyst, data enthusiast, or NGO working in the blood banking space, this project provides a solid foundation for understanding donor trends and improving blood supply chain decisions.

---

## 📊 Dataset Summary

| Attribute | Details |
|-----------|---------|
| Total Records | 10,000 donors |
| Features | 18 columns |
| Geography | 20 cities across 15 Indian states |
| Donation Centers | 10 centers |
| Time Span | Registration & donation dates included |

### 🗂️ Columns

| Column | Description |
|--------|-------------|
| `Donor_ID` | Unique identifier for each donor |
| `Full_Name` | Donor's full name |
| `Gender` | Male / Female / Other |
| `Age` | Age of donor (18–65 years) |
| `Blood_Group` | ABO/Rh blood type (8 types) |
| `Contact_Number` | Phone number |
| `Email` | Email address |
| `City` | Donor's city |
| `State` | Donor's state |
| `Country` | Country (India) |
| `Last_Donation_Date` | Date of most recent donation |
| `Total_Donations` | Cumulative number of donations (0–9) |
| `Eligible_for_Donation` | Current eligibility status (Yes/No) |
| `Medical_Condition` | Reported medical condition (if any) |
| `Weight_kg` | Donor weight in kilograms |
| `Hemoglobin_g_dL` | Hemoglobin level in g/dL |
| `Donation_Center` | Name of the blood bank / donation center |
| `Registration_Date` | Date of donor registration |

---

## 🔍 Key Insights

### 🩸 Blood Group Distribution
- **O+** is the most common blood group — **37.3%** of all donors
- **B+** follows at **31.4%**
- **AB-** is the rarest, with only **101 donors (1%)**

### ✅ Donor Eligibility
- **64.2%** of donors are currently eligible for donation
- **35.8%** are ineligible, often due to medical conditions

### 🏥 Medical Conditions
- Hypertension is the most prevalent condition (614 donors)
- Other notable conditions: Anemia (469), Diabetes (388), Asthma (308)

### 👥 Gender Breakdown
- Female: 4,986 | Male: 4,906 | Other: 108
- Near-equal gender representation across the donor pool

### 🗺️ Geographic Coverage
- 20 major cities across 15 Indian states
- Includes metros and Tier-2 cities for broad representation

---

## 📁 File Structure

```
Blood_Donation_Analytics_Project.xlsx
│
├── About            → Project description and methodology notes
├── Dashboard        → Interactive visual dashboard (charts & KPIs)
├── Demographics     → Age, gender, blood group analysis
├── Geographics      → City/state-wise donor distribution
├── Table1 (2)       → Pivot summary of blood group counts
└── Data             → Raw dataset (10,000 rows × 18 columns)
```

---

## 🛠️ Tools Used

- **Microsoft Excel** — Data storage, pivot tables, charts, and dashboard
- **Excel Slicers & Pivot Tables** — Interactive filtering and aggregation
- **Conditional Formatting** — Highlight eligibility and health flags

---

## 📈 Dashboard Features

The Excel dashboard includes:
- Blood group distribution (donut/bar chart)
- Donor eligibility breakdown
- Gender-wise and age-wise donor analysis
- Geographic distribution across Indian states and cities
- Donation center performance overview
- Medical condition impact on eligibility

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/blood-donation-analytics.git
   cd blood-donation-analytics
   ```

2. **Open the Excel file**
   ```
   Blood_Donation_Analytics_Project.xlsx
   ```
   > Requires Microsoft Excel 2016 or later (for slicer and dashboard support)

3. **Explore the Dashboard tab** for an overview, or navigate to the **Data tab** for raw analysis.

---

## 💡 Use Cases

- **Healthcare NGOs** — Identify donor pool gaps by blood type or region
- **Blood Banks** — Optimize donor outreach campaigns
- **Data Analytics Students** — Practice Excel dashboarding and data storytelling
- **Public Health Researchers** — Study eligibility trends and medical barriers to donation

---

## 🤝 Contributing

Contributions are welcome! If you'd like to extend this project (e.g., Python/Power BI version, predictive eligibility model), feel free to fork and open a pull request.

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push and open a PR

---


## 🙌 Acknowledgements

- Dataset created for educational and analytical purposes
- Inspired by real-world blood donation management challenges in India
- Special thanks to all voluntary blood donors 🫀

---

*If you find this project useful, please ⭐ star the repository!*
