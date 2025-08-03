# 🧠 Palmoria Group HR Data Analysis - Power BI Project Report

### 📈 PROJECT OVERVIEW

This report details the development of a Power BI dashboard for the Palmoria Group, a manufacturing company in Nigeria. The objective of this project was to analyze the company's HR data to identify key areas of concern related to gender equality, salary structure, performance, and bonus distribution, and to provide actionable insights for management.

### 🔎 PROJECT OBJECTIVE
The project encompassed the following key areas:

- Data Extraction and Cleaning: Transforming raw employee data and bonus rules from image formats into structured, usable datasets.

- Data Analysis: Performing comprehensive analysis on gender distribution, salary structures, performance ratings, regulatory compliance (minimum salary), and bonus calculations.

- Data Visualization: Creating a series of interactive visualizations within Power BI to present the analytical findings clearly and concisely.

- Power BI Dashboard Development: Designing and structuring a multi-page Power BI dashboard to facilitate easy exploration and understanding of HR insights.

### 🗂️DATA SOURCES:

The primary data sources for this project were:
- Employee Data: Provided as an image (simulating an Excel spreadsheet), containing employee names, gender, department, salary, location, and performance ratings.

- Bonus Rules: Provided as an image, outlining the bonus multipliers applicable to different departments.

### 🗂️ Data Preparation and Modeling
The dataset has shown the real HR data from Palmora Group and includes the following fields:
Data Cleaning Steps:

1. Gender Imputation: Employees with undisclosed gender were assigned a 'Undisclosed' category to ensure all records were accounted for.

2. Salary Validation: Records with missing or zero salaries were removed, as these indicated employees no longer with the company or invalid data.

3. Department Standardization: 'NULL' values in the department field were removed to maintain data integrity.

### 📈 Data Model:

The Power BI data model consists of two main tables:

- EmployeeData: This table contains the cleaned employee information, including calculated fields for individual bonus amounts and total pay inclusive of bonuses. It also includes a Meets_Min_Salary flag and Salary_Band for compliance and distribution analysis.

- BonusRules: This table contains the departmental bonus multipliers.

 A Many-to-One relationship was established between EmployeeData[Department] and BonusRules[Department] to link bonus rules to individual employees.

 ### 📈 Key Performance Indicators (KPIs)

 The Power BI dashboard prominently displays several key KPIs to provide an immediate overview of the HR landscape:

• TOTAL EMPLOYEE: 875

• TOTAL AVERAGE SALARY: 73.64K

• TOTAL SALARY: 64M

• TOTAL BONUS RATE: 30

• TOTAL EMPLOYEE GENDER: 3 (Female, Male, Undisclosed)

• TOTAL DEPARTMENT: 12

• TOTAL EMPLOYEE REGION: 3 (Abuja, Kaduna, Lagos)

### 🧠 Dashboard Structure and Visualizations

The Power BI dashboard is organized into multiple pages, each focusing on specific aspects of the HR data:

### Page 1: Overview and Gender Distribution
This page provides a high-level summary of the workforce and detailed insights into gender distribution.

• Gender Distribution by Region: A bar chart illustrating the number of male, female, and undisclosed employees across Abuja, Kaduna, and Lagos.

• Overall Gender Distribution: A Pie chart showing the proportion of Female (406), Male (431), and Undisclosed (38) employees company-wide.

• Gender Pay Gap: A bar chart comparing the average salaries of Female, Male, and Undisclosed genders, highlighting potential disparities.

• Average Salary by Department and Region: Bar charts displaying average salaries broken down by department and gender, and by region and gender, to pinpoint specific areas of salary differences.

• Total Bonus Payout by Region: A bar chart showing the total bonus amounts distributed in each region.

• Rating Distribution by Gender: A stacked bar chart presenting the counts of employees across different performance ratings (Average, Good, Poor, Very Good, Very Poor) for each gender.

• Employees Below Minimum Salary Threshold by Region: A bar chart indicating the number of employees in each region who do not meet the $90,000 minimum salary requirement.

### Page 2: Salary and Bonus Details
This page delves deeper into salary distribution and individual bonus calculations.

• Salary Distribution by 10,000Band∗∗:Abarchartvisualizingthenumberofemployeeswithineach10,000 Band**: A bar chart visualizing the number of employees within each 
10,000Band∗∗:Abarchartvisualizingthenumberofemployeeswithineach
10,000 salary bracket, providing a clear picture of the company's salary structure.

• Ratings Comparison by Gender: A bar chart showing the total counts of employees by gender across all ratings.

• Individual Employee Bonus Payments Table: A detailed table listing each employee's name, department, salary, performance rating, bonus rate, and calculated bonus amount.

### 📌 Conclusion

The Power BI dashboard serves as a powerful tool for the Palmoria Group's HR department and management to gain actionable insights into their workforce data. It facilitates the identification of gender disparities, salary gaps, compliance issues, and informs strategic decisions regarding compensation and talent management. The interactive nature of the dashboard allows for dynamic exploration of data, enabling a deeper understanding of the HR landscape within the organization.

### Dashborad Screenshot Preview and Overall Layout

`![alt text](<img width="1366" height="768" alt="Screenshot (10)")`

`![alt text](<img width="1366" height="768" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/c17fffd2-8963-4edd-a651-7591976c4d15" />
)`

### Overall Layout

• Key performance indicators (KPIs) at the top:

• TOTAL EMPLOYEE: 875

• TOTAL AVERAGE SALARY: 73.64K

• TOTAL SALARY: 64M

• TOTAL BONUS RATE: 30

• TOTAL EMPLOYEE GENDER: 3

• TOTAL DEPARTMENT: 12

• TOTAL EMPLOYEE REGION: 3

### Visualizations:

Filters pane "Joined Data" (Employee Data) which is the merging of both Bonus rules and Palmoria Employee data. which has the these headings: "Annual Bonus", "Bonus Rate", "Department", "Dept Rating", "Gender", "Location", "Name", "Rating", "Salary", "Salary Band", "Total Pay".

1 Gender Distribution by Region (Bar Chart):

• Shows number of Female, Male, and Undisclosed employees per region (Kaduna, Abuja, Lagos).

• Kaduna: Female (153), Male (170), Undisclosed (137).

• Abuja: Female (147), Male (149), Undisclosed (102).

• Lagos: Female (106), Male (112), Undisclosed (226).

2 Overall Gender Distribution (Pie Chart):

• Female: 406

• Male: 431

• Undisclosed: 38

3 Gender Pay Gap (Bar Chart):

• Compares average salary between Female, Male, and Undisclosed genders.

• Male average salary appears higher than Female.

4 Average Salary by Department and Region (Bar Chart):

• Shows average salary for Female, Male, and Undisclosed genders across different departments.

• Departments listed: Training, Business Development, Accounting, Services, Marketing, Support, Product Management, Sales, Legal, Human Resources, Engineering, Research and Development.

• Salaries range from ~50K to ~100K+.

5 Total Bonus Payout by Region (Bar Chart):

• Kaduna: 11.1M

• Abuja: 11.0M

• Lagos: 7.4M

6 Rating Distribution by Gender (Stacked Bar Chart):

• Shows counts of employees by rating (Average, Good, Poor, Very Good, Very Poor) for Female, Male, and Undisclosed genders.

• Average: ~400, Good: ~200, Poor: ~100, Very Good: ~50, Very Poor: ~20.

7 Employees Below Minimum Salary Threshold by Region (Bar Chart):

• Shows the number of employees below the minimum salary threshold (presumably $90,000 as per the case study).

• Kaduna: 28480

• Abuja: 28130

• Lagos: 28130

Four main visual sections:

• Gender filter on the left.

• Salary Distribution by $10,000 Band (bar chart).

• Ratings Comparison by Gender (bar chart).

• Individual Employee Bonus Payments (table).

### Gender Filter:

• Options: Female, Male, Undisclosed.

• Locations: Abuja, Kaduna, Lagos.

• Departments: Accounting, Business Development, Engineering, Human Resources, Legal, Marketing, Product Management, Research and Development, Sales, Services, Support, Training.

### Salary Distribution by $10,000 Band:

• A bar chart showing salary distribution in bands (e.g.,0−10,000, 10,000−10,000-10,000−20,000, etc.).

• The x-axis represents salary bands, and the y-axis represents the count of employees.

• Visually, most employees seem to fall into higher salary bands, with a significant number in the 100,000−100,000-
100,000−110,000 and 110,000−110,000-110,000−120,000 range.

### Ratings Comparison by Gender:

• A bar chart comparing ratings between Male, Female, and Undisclosed genders.

• Shows counts for each gender.

• Male: 481, Female: 406, Undisclosed: 38.

### Individual Employee Bonus Payments Table:

• Columns: Name, Department, Salary, Rating, Bonus Rate, Bonus Amount.

• Shows detailed information for individual employees regarding their salary, rating, bonus rate, and calculated bonus amount.

• Example entries visible: Abigail Esin (Business Development, 116200, Good, 0.05, 6371.6), Adanna Okoro (Product Management, 65600, Average, 0.05, 9780.56).

### Key Insights from Dashboards:

• Gender Distribution: Relatively balanced overall, but significant undisclosed gender count. Regional and departmental distributions vary.

• Salary: Average salary is 73.64K. There appears to be a gender pay gap, with males earning more on average. Salary distribution shows a concentration in higher bands.

• Performance: Rating distribution is skewed towards Average and Good. Performance ratings vary by gender.

• Bonus: Total bonus payout is substantial, with Kaduna and Abuja having higher payouts than Lagos.

• Compliance: A significant number of employees across all regions are below the minimum salary threshold, indicating a compliance issue.

### 🛠️TOOLS USED
- Power BI Desktop – for data modeling, visualization, and interactivity
- Power Query – for data transformation and cleaning
- DAX (Data Analysis Expressions) – for calculated metrics
- Excel – for initial data structuring

 ### 🤝Let’s Connect
  ***FAITH UDOKANMA IHUEZE***
 ##### Github: [http://github.com/faith79-create]
 ##### Email: faithamaefule@yahoo.com
 ##### Phone: +234 703 083 4411


