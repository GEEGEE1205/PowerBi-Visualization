### Power BI Project: HR Attrition Analysis & Nigerian Census Mapping

  **Project Overview**

This Power BI report showcases a dual-purpose analysis project combining:

   - A Geographic Census Analysis using a Nigerian Map Dataset
   - An HR Attrition Analysis using employee-related data

The project demonstrates practical knowledge of Power BI visualizations, data modeling, conditional logic, and insightful metrics tracking using both geographic and organizational data.

---

 **Dataset 1:** Nigerian Map & Population Census (2006 & 2019)

   - Dataset Description:
     - Fields Used: State, Latitude, Longitude, Population (2006), Population (2019)
     - Source Context: Nigerian states with geolocation data and population figures from two census periods

  - Objective:

     - To visualize population distribution and growth across Nigerian states using Power BI’s map-based visualizations.
     
 - Visual Techniques Used:

     - Map Visuals: Used Latitude and Longitude to plot each state on the Nigerian map.
 - Data Points Displayed:

   - Population 2006: For historical baseline
   - Population 2019: For growth comparison
    
 - Tooltip Enhancements: Displayed state names and population on hover.

**Insights Achieved**

   - Easy identification of states with the highest population density
   - Comparison of demographic growth across regions
   - Visual distinction between northern and southern population clusters

---

#### Dataset 2: HR Attrition Analysis

**Dataset Description**

   - Fields Used: Age, Gender, Department, Attrition Status, Educational Field, Job Role, Job Satisfaction
   - Focus: Understanding patterns of employee attrition across departments, roles, gender, and age groups.

 **Objectives**

   - Calculate core HR metrics
   - Create conditional and calculated columns
   - Explore attrition by different demographic and departmental splits
   - Identify age groups with the highest attrition rates

---

 **Key Metrics Created (Using DAX & Conditional Logic)**

| Metric                   | Description                                       |
| ------------------------ | ------------------------------------------------- |
| Total Employees          | Count of all employees                            |
| Current Employees        | Count of employees not marked as “Attrition”      |
| Total Attrition          | Count of employees who left                       |
| % Attrition              | Percentage of employees who left out of the total |
| Average Age              | Mean age of all employees                         |
| Age Group Classification | Created age bands (Under 25, 25–34, 35–44, etc.)  |

---

 **Analytical Views & Visuals**

1. Overall Counts:

   - Used cards and tables to show totals and key figures.
     
2. Attrition Breakdown by Department:

   - Used clustered column chart to show where attrition is highest.
     
3. Attrition by Age and Gender:

   - Used bar charts and stacked visuals to compare male vs. female attrition across age groups.
     
4. Educational Field vs Attrition:

   - Used pie chart and doughnut charts to show which academic backgrounds had higher turnover.
     
5. Job Satisfaction by Role:

   - Used tables and bar visuals to examine how job satisfaction correlates with roles and attrition.
     
6. Attrition Rate by Age Band & Gender:

   - Created age segments:

     - Under 25
     - 25–34
     - 35–44
     - 45–54
     - Over 55
  - Measured gender-based attrition within these groups using bar and column charts.

---

**Insights Derived**

   - High attrition rate observed in certain age bands and genders
   - Certain departments and job roles have more frequent attrition
   - Younger employees (Under 25, 25–34) tend to leave more often
   - Job satisfaction scores correlate with attrition trends
   - Identified education fields with higher employee turnover

---

 **Skills & Features Demonstrated**

   - Creating Calculated Columns and Conditional Columns using DAX.
   - Working with categorical groupings (e.g., Age Bands)
   - Aggregating data with COUNT, COUNTROWS, AVERAGE, and custom measures
   - Using Map Visuals, Clustered Column Charts, Bar Charts, Pie Charts, Doughnut Charts, and Tables
   - Enhancing reports with clean layout and interactivity

---

 **File Information**

   - Software Used: Power BI Desktop
   - Datasets Included:

     - Map Dataset (Nigeria Census)
     - HR Attrition Dataset
- **Primary Features**: Data modeling, calculated fields, KPI tracking, demographic filtering

---

- **What I Learned**:

    - How to prepare and visualize geographic data using Latitude and Longitude.
    - How to calculate and present attrition KPIs using DAX.
    - How to segment employee data by age, gender, department, and job role.
    - Building interactive visuals to tell data stories.
    - Combining multiple datasets in a single Power BI report.

---

This project was developed as part of my Power BI learning journey, where I applied multiple transformation, modeling, and visualization techniques to real-world business datasets.

