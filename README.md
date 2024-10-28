# H-1B Visa Data Analysis: Impact of COVID-19

*Note: The main report was developed for my bachelor's degree project, which influenced its structure.*

This project provides an in-depth analysis of the H-1B visa landscape, focusing on the impact of COVID-19 on visa applications, job roles, wage trends, and approval rates across key industries in the United States. Utilizing Python and Power BI, this project translates data from Q1 2019 to Q3 2024 into actionable insights relevant to policymakers, businesses, and economic stakeholders.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources and Tools](#data-sources-and-tools)
- [Usage](#usage)
- [Data Structure](#data-structure)
- [Analysis and Key Findings](#analysis-and-key-findings)
- [Future Scope](#future-scope)

---

## Project Overview
The H-1B visa program is crucial for industries in the U.S. that depend on highly skilled foreign talent. This project explores the trends in H-1B visa applications and approvals over pre-COVID, during-COVID, and post-COVID periods. Key objectives include:
- Analyzing H-1B visa application trends across different phases.
- Investigating wage patterns and identifying impacted industries.
- Presenting findings through an interactive Power BI dashboard.

## Data Sources and Tools
- **Data Range:** Q1 2019 – Q3 2024
- **Data Source:** U.S. Department of Labor H-1B data (2018-2024)
- **Tools Used:** 
  - **Python**: Data cleaning, statistical analysis
  - **Power BI**: Interactive dashboard for visualization
  - **MS Office**: Documentation and reporting

## Usage
### Running the Analysis
1. Ensure all CSV files are in the `/data` directory.
2. Execute `analysis_script.py` to process the datasets and generate summary statistics.
3. Open `dashboard.pbix` in Power BI to view interactive visualizations of the results.

### Power BI Dashboard
The Power BI dashboard provides the following insights:
- **Application Trends Over Time**: Visualizes the number of H-1B applications from 2018 to 2024.
- **COVID-19 Impact**: Shows case outcomes by year, highlighting how the pandemic affected application approvals and denials.
- **Wage Trends**: Displays the average wage offered to H-1B applicants across different years.
- **Industry Analysis**: Identifies top industries employing H-1B visa holders and their respective wage offerings.

## Data Structure
The datasets used in this analysis contain the following key columns:
- `CASE_NUMBER`: Unique identifier for the visa application
- `DECISION_DATE`: Date of visa application decision
- `CASE_STATUS`: Status of the application (Certified, Denied, etc.)
- `EMPLOYER_NAME`: Name of the sponsoring employer
- `WAGE`: Salary offered to the visa applicant
- `JOB_TITLE`: Title of the job position offered to the applicant

For a full description of all data fields, refer to the main report.

## Analysis and Key Findings
### Key Insights
- **Trends in Applications**: Applications surged in 2021, likely due to pent-up demand from the COVID-19 impact.
- **Wage Trends**: Wages offered to H-1B holders increased consistently, even during the pandemic, reflecting sustained demand for foreign talent in tech fields.
- **Top Industries**: The technology sector remained the leading employer, especially in software engineering and computer programming roles.

### COVID-19 Impact on Industries
1. **Increase in Withdrawn Applications**: Withdrawal rates rose during the pandemic, potentially due to economic uncertainties.
2. **Resilient Wages**: Despite the pandemic, wages continued to climb, underscoring the high demand for skilled labor in the U.S. market.

## Future Scope
This analysis can be expanded by:
- Incorporating data beyond 2024 for trend continuation.
- Conducting deeper industry-specific analyses on how wage offerings have adapted post-pandemic.
- Analyzing policy impacts on H-1B visa processes and outcomes in future U.S. administrations.

---

For additional information, contact [Shashank Sinha](https://www.linkedin.com/in/theshashanksinha/).
```
