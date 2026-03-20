# 🧾 Weather Analysis Dashboard
The Winter Temperature dashboard provides a focused analysis of seasonal weather conditions, tracking key environmental metrics like humidity,
temperature levels, and rainfall. It uses interactive features and visualizations—including thermometers and location-based reports—to help users
monitor climate trends and geographic temperature variations.

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

Designed an interactive Power BI dashboard to analyze key metrics and trends, enabling clear visualization of insights and supporting data-driven business decisions.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

- Analyze temperature trends across different locations and time periods to understand climate patterns.
- Identify regions with extreme temperature variations that may impact environmental or planning decisions.
- Examine seasonal temperature changes to support forecasting and climate analysis.
- Detect temperature anomalies or unusual patterns that may indicate climate change effects.
- Compare average, minimum, and maximum temperatures to evaluate overall weather conditions and trends.

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Dataset Size:
  Contains temperature records across multiple locations and dates used to analyze winter climate patterns.
- Key Variables:
  Includes fields such as Date, City/Location, Minimum Temperature, Maximum Temperature, and Average Temperature.
- Time Period:
  Data covers winter season months across different years to track seasonal temperature variations.
- Data Source:
  Temperature data is collected from weather monitoring systems or meteorological databases.
- Purpose of Dataset:
  Used to analyze temperature trends, compare locations, and identify extreme cold patterns during winter.

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Power Bi 
- Dax Function
- Charts & Graphs
- GitHub

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
vrinda-store-analysis/
│
├── README.md
├── .gitignore
├── requirements.txt
├── Weather Analysis.pdf
│
├── dashboard/                  # POWER BI File
│   └── weather_analysis_dashboard.pbi

```

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Removed Missing & Null Values – Handled blank temperature records using imputation and filtering techniques.
- Eliminated Duplicate Records – Identified and removed duplicate entries to maintain data accuracy.
- Standardized Data Formats – Unified date formats and temperature units (°C/°F) for consistency.
- Cleaned Column Names – Renamed columns and removed spaces/special characters for better usability.
- Transformed Data – Processed and reshaped data using Power BI.
- Handled Outliers – Removed unrealistic temperature values to ensure accurate analysis.
- Created Calculated Fields – Derived metrics like average, minimum, and maximum temperature.

```

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Negative or Missing Values Detected:
- Checked for missing or zero values in temperature-related fields (e.g., min/max temperature).
- Cleaned or replaced incorrect entries to ensure accurate seasonal analysis.
**Outliers Identified:
- Detected extreme temperature values (very high or unusually low readings).
- Reviewed outliers to confirm whether they were valid winter extremes or data errors.
**Correlation Analysis:
- Analyzed relationships between variables such as date, region, and temperature.
- Identified trends like temperature drops over time and regional winter patterns.

```

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

- Identified clear seasonal trends with temperatures dropping significantly during peak winter months.
- Certain regions consistently recorded lower temperatures compared to others.
- Detected a few extreme temperature values indicating possible cold waves.
- Temperature patterns showed gradual decline and rise across the winter timeline.
- Data analysis revealed consistent correlations between time and temperature variation.

  ```
