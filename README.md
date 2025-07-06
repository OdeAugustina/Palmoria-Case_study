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
3. Data Cleaning and Formatting
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

<img width="925" alt="Page1 REport" src="https://github.com/user-attachments/assets/5e6b6302-bcdf-4058-bac8-961fcc8ad2ea" />








<img width="923" alt="Report 2" src="https://github.com/user-attachments/assets/fa927107-3ea3-4e6a-97b2-bbec00964630" />

<img width="916" alt="Page 3" src="https://github.com/user-attachments/assets/6292a7f9-75f4-44e2-86a8-ee30b8fbd7f9" />


### INSIGHTS
- The organization's gender is nearly balanced with 49.1 % Male, 46.6% Female, and 4.3% undisclosed. However, a department like Engineering, Legal, and Operations has lower female representation.
- Males earn more on average than females.
- The gender gap is significant in the Human Resources and Support departments.
- Abuja shows the widest salary distribution between males and females across the regions
- About 654 (69%) earn less than the $90000 minimum salary benchmark which indicates a lack of compliance.
- Palmoria paid over $2.2 million in bonuses, with Kaduna receiving the largest share
- The total amount paid by the company exceeded $71.9 million


### RECOMMENDATION
While there are some gender pay gaps within Palmoria Group, especially in departments like HR, Legal, and Support, the data shows that the situation may not be as severe as the media suggests. The disparities aren't widespread, but they do exist and deserve attention.

That said, the company needs to take clear steps toward fairness. We recommend focusing on closing salary gaps in the affected departments and making sure female employees are fairly compensated, especially when they have similar roles and performance to their male colleagues.

Additionally, a significant number of employees earn below the $90,000 minimum wage benchmark. Addressing this will not only help Palmoria stay compliant but also improve employee satisfaction and reputation


