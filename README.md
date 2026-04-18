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
- ETL ( Extract , Transform , Load )

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


<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1.**Negative or Missing Values Detected:
- Checked for missing or zero values in temperature-related fields (e.g., min/max temperature).
- Cleaned or replaced incorrect entries to ensure accurate seasonal analysis.
2.**Outliers Identified:
- Detected extreme temperature values (very high or unusually low readings).
- Reviewed outliers to confirm whether they were valid winter extremes or data errors.
3.**Correlation Analysis:
- Analyzed relationships between variables such as date, region, and temperature.
- Identified trends like temperature drops over time and regional winter patterns.

 
  ```
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard Shows:
- Total Number of Movies and TV Shows
- Content Distribution by Gender
- Release Year Trends
- Country-wise Content Production
- Content Ratings Distribution
- Type of Content Comparison


<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
git clone https:[//github.com/yourusername/](https://github.com/vikas-5381/prime_vidieo_analysis)
```
3. Load the CSVs and ingest into database:
```bash
prime_vidieo_analysis.xlsx  
```
4. Create sales summary table:
```bash
power bi scripts/get_vidieo_summary.xlsx
```
5. Open Power Bi Dashboard:
 ```bash
   - `Weathher Analysis Dashboard.pbix`
```

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Enhance Data Quality:
 Ensure continuous monitoring and cleaning of temperature data to remove missing values and inconsistencies for accurate insights.
- Focus on Extreme Weather Preparedness:
 Use identified extreme temperature patterns to plan for cold waves and improve early warning systems.
- Regional Planning:
 Implement region-specific strategies, as colder areas require more resources for winter preparedness compared to moderate regions.
- Trend-Based Forecasting:
  Leverage historical winter trends to build predictive models for better seasonal planning and decision-making.
- Dashboard Improvements:
 Add real-time data updates and interactive filters (region, date) to enhance usability and deeper analysis.
- Support Decision Making:
 Utilize insights for sectors like agriculture, transportation, and public safety to minimize risks during winter conditions.



<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Vikas Siddheshware**  
Data Analyst      
📧 Email: vikassiddheshware2001@gmail.com 
🔗 [LinkedIn](www.linkedin.com/in/vikas-siddheshware) 
