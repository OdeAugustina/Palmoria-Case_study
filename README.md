# Palmoria-Case_study
A Power BI project investigating gender pay disparity and HR performance metrics at Palmoria Group, a Nigerian-based manufacturing company. 


## PROJECT TITLE: Palmoria Employee Gender Pay Equity and Performance Analysis

[PROJECT OVERVIEW](#project-overview)

[DATA SOURCES](#data-sources)

[TOOLS USED](#tools-used)

[DATA CLEANING AND PREPARATION](#data-cleaning-and-preparation)

[EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)

[DATA ANALYSIS](#data-analysis)

[DATA VISUALIZATION](#data-visualization)

[INSIGHTS](#insights)

[RECOMMENDATION](#recommendation)


### PROJECT OVERVIEW
This project analyzes the HR dataset to gain insights into the gender pay gap, salary distribution, performance rating, and bonus allocations at the Palmoria manufacturing Company. This analysis aims to identify areas of imbalance and make informed decisions based on the recommendations to ensure equity and transparency.

### DATA SOURCES
The source of data used for this analysis is the Palmoria Group Emp_data.csv and Bonus rules.csv, and this is an open-source dataset that can be freely downloaded from open-source online sites such as Kaggle or FRED, or any other data repository site.

### TOOLS USED
Ms Excel for Data Cleaning [Download Here](https://www.microsoft.com/en-us/microsoft-365/download-office)
 - For Data Collection

Power BI [Download here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
- Data Modeling
- Data Visualization
- Power Query (for data Cleaning)
- DAX (for KPI measures)

### DATA CLEANING AND PREPARATION
In the initial phase of the Data Cleaning and preparations, I perform the following actions;
1. Data Loading and Inspection
2. Handling Missing Variables
3. Data Cleaning and formatting
4. Integrated the Bonus Rules
5. Created Salary Bands

### EXPLORATORY DATA ANALYSIS
The objective of this analysis is to produce an interactive Power BI that answers some of the following questions: 
- What is the gender distribution in the organization? Distil to regions and Departments
- What is the gender pay gap
- Does Palmoria meet the minimum Salary requirement of 90000?
- What is the salary Distribution?
- How was the Bonus allocated based on the Performance Rating?
Dashboard was created to visualize the insights  and include;
  -Gender Distribution
  -Performance Ratings
  -Salary Distribution
  -Pay Equity Patterns
  -Bonus Allocation
  

### DATA ANALYSIS
I used Power BI DAX to create measures such as Percentage of Females whose Performance was above or below average, Percentage Male Performance rating below or above average, Average Salary. These measures were used in creating an interactive Dashboard.

```%Female Above Average = Divide([No of Females Rated Above Average],[Total_Male_Female])```

```%Female High Salary = DIVIDE([Female_HighSalary_Count],[Total_Male_Female])```

```%Female Low Salary = DIVIDE([Female_LowSalary_Count],[Total_Male_Female])```

```%Male Above Average = Divide([No of Males Rated Above Average],[Total_Male_Female])```

```%Male High Salary = DIVIDE([Male_HighSalary_Count],[Total_Male_Female])```

```%Male Low Salary = DIVIDE([Male_LowSalary_Count],[Total_Male_Female])```

```Average Salary by Gender = AVERAGE('Palmoria Group emp-data'[Salary])```

```Total Pay = 'Palmoria Group emp-data'[Salary] + 'Palmoria Group emp-data'[Bonus Amount]```

### DATA VISUALIZATION
After cleaning and creating New columns in Power Query, I applied the changes and used the Report Review for data visualization. Several expressions and functions were created to achieve the desired KPIs or metrics, providing a clear and actionable visual for informed decision-making. Some of the visuals are:
- Gender Distribution
- Salary Distribution
- Gender Per Gap and Performance rating
- Salary band and Bonus Distribution


### INSIGHTS

### RECOMMENDATION

