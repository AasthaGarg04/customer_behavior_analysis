# customer_behavior_analysis
# Data Analytics Project

**Overview**

This project demonstrates an end-to-end data analytics workflow, starting from data loading and exploratory analysis in Python to SQL-based analysis, Power BI visualization, reporting, and presentation.

The objective is to transform raw data into meaningful insights using industry-relevant analytics tools and present the findings through interactive dashboards and business-focused reports.


**Dataset**

The project uses a structured dataset containing relevant business/customer/transactional information.

The dataset was:

* Loaded and inspected using Python
* Checked for missing values and duplicates
* Cleaned and transformed for analysis
* Used for both Python-based analysis and PostgreSQL queries


**Tools & Technologies**

| Tool                 | Purpose                                 |
| -------------------- | --------------------------------------- |
| Python               | Data loading, cleaning and EDA          |
| Pandas               | Data manipulation and analysis          |
| Matplotlib / Seaborn | Data visualization                      |
| PostgreSQL           | SQL querying and data analysis          |
| SQL                  | Business and analytical queries         |
| Power BI             | Interactive dashboard                   |
| Gamma                | Project presentation / PPT              |
| MS Excel             | Supporting data analysis                |



**Project Workflow**

**1. Data Loading**

The dataset was imported into Python using Pandas.

Key activities:

* Dataset inspection
* Understanding data types
* Checking dataset dimensions
* Identifying missing values
* Identifying duplicate records
* 
**2.Exploratory Data Analysis (EDA)**

EDA was performed to understand patterns, trends, and relationships within the data.

Activities included:

* Descriptive statistics
* Distribution analysis
* Category-wise analysis
* Correlation analysis
* Trend analysis
* Data visualization

**3. Data Cleaning**

The raw dataset was cleaned to improve data quality and prepare it for further analysis.

Steps included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing categorical values
* Handling inconsistent or invalid data
* Creating calculated/derived columns where required

**4. PostgreSQL & SQL Analysis**

The cleaned data was loaded into PostgreSQL for structured querying and deeper analysis.

SQL analysis included:

* Filtering and sorting
* Aggregations
* `GROUP BY` and `HAVING`
* `JOIN` operations
* Subqueries
* Common Table Expressions (CTEs)
* Window functions
* Business-focused analytical queries

The SQL queries were designed to answer practical business questions and identify key trends from the dataset.

**5. Power BI Dashboard**

The analyzed data was connected to Power BI to create an interactive dashboard.

The dashboard focuses on:

* Key Performance Indicators (KPIs)
* Trends and patterns
* Category-wise performance
* Comparative analysis
* Interactive filters and slicers
* Data-driven business insights


**6. Report**

A detailed project report was prepared to document the complete analytical process.

The report covers:

* Business problem
* Dataset description
* Data cleaning
* EDA findings
* SQL analysis
* Dashboard insights
* Key conclusions
* Recommendations


**7. Presentation**

A concise presentation was created using Gamma to communicate the project's methodology, findings, and recommendations in a business-friendly format.

**Dashboard**

The Power BI dashboard provides an interactive view of the major findings from the analysis.

**Key Dashboard Features**

* KPI cards
* Trend analysis
* Category-level performance
* Interactive slicers
* Comparative visualizations
* Business insights


**Results & Key Insights**

The analysis generated several actionable insights from the dataset.

Key findings include:

* Identified important trends and patterns in the data
* Highlighted high- and low-performing categories
* Identified relationships between key variables
* Used SQL analysis to answer important business questions
* Created an interactive dashboard for easier decision-making
* Converted analytical findings into business recommendations

The project demonstrates how raw data can be transformed into actionable insights through a structured analytics workflow.


**Project Structure**

Data-Analytics-Project/
│
├── data/
│   └── dataset.csv
│
├── python/
│   └── EDA_Analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── Project_Report.pdf
│
├── presentation/
│   └── Project_Presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md

**How to Run**

**Step 1: Clone the Repository**

**Step 2: Install Python Libraries**

**Step 3: Run the Python Analysis**

Open the Jupyter Notebook:
Run the cells sequentially to perform data loading, cleaning, EDA, and visualization.

**Step 4: PostgreSQL Analysis**

1. Install PostgreSQL.
2. Create a database.
3. Import the cleaned dataset.
4. Open the SQL file:
5. Execute the queries in PostgreSQL/pgAdmin.

**Step 5: Power BI**
Refresh the dataset if required and explore the interactive dashboard.

**Step 6: View the Report & Presentation**
The final report and presentation are available in the repository.



**Skills Demonstrated**

This project demonstrates practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* Data Visualization
* SQL
* PostgreSQL
* Power BI
* Dashboard Development
* Business Analysis
* Data Storytelling
* Report Writing
* Presentation Development



**Conclusion**

This project showcases an end-to-end approach to data analytics by combining Python, SQL, PostgreSQL, Power BI, and business reporting.

It demonstrates the ability to work with raw data, identify meaningful patterns, perform analytical queries, build interactive dashboards, and communicate insights clearly to support data-driven decision-making.
