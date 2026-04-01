# 📊 Marketing Campaign Performance Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Objective

To analyze the effectiveness of various marketing campaigns, track key performance indicators (KPIs), and provide actionable insights to optimize future marketing strategies.

---

## 📂 Project Structure

```
Marketing_Campaign_Performance_Analysis/
│
├── 📁 Images/                          # All EDA visualizations
├── 📓 Marketing_Campaign_Performance_Analysis.ipynb
└── README.md
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data cleaning, transformation & aggregation |
| **Matplotlib & Seaborn** | Data visualization |
| **NumPy** | Numerical computation |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 🔄 Steps Involved

**1. Data Import & Extraction** — Imported libraries and extracted the dataset from a zip file.

**2. Basic Analysis** — Confirmed no missing values; identified categorical features for encoding.

**3. Data Cleaning** — Fixed data types and converted categorical features to optimize memory and efficiency.

**4. Exploratory Data Analysis (EDA)** — Created visualizations to investigate campaign types, target audiences, channels, and customer segments.

---

## 📈 Visualizations

> EDA plots generated inside the notebook — all saved in the [`Images/`](./Images) folder.

![EDA Plots](https://github.com/rishavm003/Marketing_Campaign_Performance_Analysis/raw/main/Images/campaign_type_roi.png)

> 💡 Open the notebook to interact with all visualizations end-to-end.

---

## 🔍 Key Findings

- 📱 **Channel Performance:** Social Media ranks highest in engagement — Influencer ≈ Email > Display ≈ Search. Social Media drives ~**50% of total ROI**.
- 💰 **Email Campaigns** deliver strong ROI at significantly lower acquisition costs.
- 👩 **Target Audience:** Women aged 25–34 show the strongest engagement and conversion rates.
- 🌐 **Non-English segments** show high conversion rates, reflecting successful localization strategies.
- 📅 **Seasonality:** Conversion dips in **February & November**; peaks in **May–June** and **Oct–Nov**.
- 🗺️ **Geography:** Dallas & Chicago show best ROI; Houston & New York have the highest acquisition costs.
- 🗓️ **Campaign Duration:** 30-day campaigns are most common; 60-day campaigns show untapped potential.

---

## 💡 Recommendations

- **Prioritize Social Media & Influencer Marketing** for high ROI — don't overlook Email for cost efficiency.
- **Strengthen CTAs** in February and November to counter seasonal conversion dips.
- **Expand localization** for non-English markets where conversion efficiency is proven.
- **Reassess strategies** in San Francisco and New York — high traffic but lower returns.
- **Extend campaign durations** during high-engagement months (April, July) for better lead nurturing.
- **Sharpen targeting** to reduce acquisition costs in high-ROI segments.

---

## 📊 Dataset Features

| Feature | Description |
|---------|-------------|
| `Campaign_Type` | Email, Social Media, Influencer, Display, Search |
| `Target_Audience` | Age/gender-based segments |
| `Channel_Used` | Email, YouTube, Website, Google Ads, Social Media |
| `Customer_Segment` | Tech Enthusiasts, Fashionistas, Foodies, Health & Wellness, Outdoor Adventurers |
| `ROI` | Return on Investment per campaign |
| `Acquisition_Cost` | Cost to acquire each customer |
| `Conversion_Rate` | Percentage of users who converted |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/rishavm003/Marketing_Campaign_Performance_Analysis.git
cd Marketing_Campaign_Performance_Analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch notebook
jupyter notebook Marketing_Campaign_Performance_Analysis.ipynb
```

---

## 📌 Project Learnings

- Executed a full EDA pipeline from raw data to actionable insights
- Identified high-performing channels and customer segments through visual analysis
- Practiced categorical data encoding and memory optimization techniques
- Built multi-dimensional analysis across time, geography, and audience segments

---

## ⚠️ Note

> This analysis is based on a **fictional dataset** and should be validated and customized based on specific business contexts and objectives.

---

## 🤝 Contributing

Contributions and suggestions are welcome! Feel free to open an [issue](https://github.com/rishavm003/Marketing_Campaign_Performance_Analysis/issues) or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Rishav M**  
[![GitHub](https://img.shields.io/badge/GitHub-rishavm003-181717?style=flat&logo=github)](https://github.com/rishavm003)

---

⭐ **If you found this project useful, please give it a star!** ⭐
