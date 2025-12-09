# Project Management Analysis Dashboard 
This Power BI dashboard provides a comprehensive analysis of organization-wide project performance. It helps understand the number of projects, cost trends, benefits, project phases, and profitability.
The dashboard enables management to make informed decisions by visualizing project progress, performance rate, and financial outcomes.

##  📊 Dataset
The dataset used for this Power BI report can be downloaded from the link below:

➡️ [Click here to download the dataset](https://github.com/DattaChole/PowerBI-Project-/blob/main/Project%20Management%20Dataset.csv)

##  📌 Questions (KPI)
- What is the Total Project Cost and Total Project Benefit by Year for each Department?

- How many Projects exist in each Project Phase?

- Which are the Top 7 Projects in each Project Type based on their Status?

- How many Projects fall into each Process Rate category?

- Which are the Top 10 most profitable Projects and what are their Descriptions?
## Process 

1. **Data Preparation**
   - Cleaned the dataset, fixed missing values, formatted cost/benefit fields.
   - Created calculated columns for Profit, Completion %, and Rate Categories.

2. **Data Modeling**
   - Built a simple star-schema.
   - Created DAX measures for Total Cost, Total Benefit, Total Projects, and Profit.

3. **Dashboard Design**
   - Added KPI cards for high-level metrics.
   - Built visuals: Line chart (Cost vs Benefit by Year), Funnel (Project Phases), Bar (Top Projects), Donut (Process Rate), and a Detailed Table View.
   - Added navigation buttons between Dashboard and Table View.

4. **Insights**
   - Identified top profitable projects.
   - Analyzed department-wise cost & benefit trends.
   - Compared project status, phases, and completion rates.


## Dashboard view 1
<img width="1397" height="735" alt="Screenshot 2024-07-12 155706" src="https://github.com/user-attachments/assets/a0504f70-0c7c-4310-af6a-4d2dcfc4cd5b" />

## Dashboard view (Table View)
<img width="1193" height="624" alt="Screenshot 2024-07-12 161836" src="https://github.com/user-attachments/assets/0d2bd65b-b70e-4c04-bc8a-68fc2404e992" />


## 📈 Key Insights

- Total project cost is **28M**, while total project benefit is **63M**, showing strong positive returns.
- Most projects are in the **Explore, Implement, and Develop** phases.
- The majority of projects fall within the **76–100%** completion rate category.
- Top 7 projects contribute the highest share of overall profit.
- Some departments have high cost but low profit, indicating optimization opportunities.
- Year-wise trend shows benefits remaining consistent while costs decrease.













