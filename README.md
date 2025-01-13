# Workforce-Analytics-Dashboard-Project-using-Microsoft-Power-BI

### **Project Overview**  
This project involves the creation of an interactive **HR Analytics Dashboard** in Power BI to analyze and visualize key workforce metrics. The dashboard provides actionable insights into employee demographics, job-related statistics, and organizational trends, enabling data-driven decision-making for HR professionals. The interactive features of the dashboard allow users to filter and drill down into specific details, making it a powerful tool for human resource management.  

---

### **Key Features and Insights**  
1. **Employee Demographics**  
   - Analysis of staff distribution by **gender** and **age groups** to understand workforce diversity.  
   - Insights into the company's headcount trends over time.  

2. **Compensation Analysis**  
   - Visualization of **average salaries** segmented by job titles and qualifications.  
   - Correlation between employee qualifications and compensation levels, identifying potential disparities or trends.  

3. **Leave and Attendance Metrics**  
   - Overview of average **leave balances** across the workforce.  
   - Identification of employees with leave balances exceeding 20 days, providing insights into unused leave trends.  

4. **Organizational Growth Trends**  
   - Year-over-year comparison of **company size**, enabling tracking of workforce expansion or contraction.  

5. **Interactive Dashboard Features**  
   - Drill-through capabilities to explore specific segments, such as job titles or departments.  
   - Cross-highlighting of visuals to analyze interdependent metrics (e.g., gender vs. salary distribution).  
   - Dynamic slicers for real-time filtering by departments, years, and other attributes.

---

### **Technical Implementation**  

1. **Data Sourcing and Preparation**  
   - Data imported from multiple sources, including Excel files and SQL databases.  
   - **Power Query** used for cleaning and transforming data (e.g., removing duplicates, handling missing values).  
   - Relationships created between tables to enable seamless analysis across multiple dimensions.  

2. **Data Modeling and DAX**  
   - Creation of calculated columns and measures using **Data Analysis Expressions (DAX)** for advanced analytics, such as:  
     - Average salary per qualification.  
     - Year-over-year changes in headcount.  
     - Leave utilization trends.  

3. **Visualizations**  
   - Bar and column charts for distribution metrics (e.g., age, gender, and job titles).  
   - Line charts for historical trends in company growth.  
   - KPI cards for key metrics like total headcount, average salary, and leave balance.  
   - Interactive slicers for dynamic filtering of visuals.  

4. **Time Intelligence**  
   - A calendar table created for time-based analysis, supporting trends by year and month.  
   - Utilized DAX functions like `SAMEPERIODLASTYEAR` and `TOTALYTD` for time-based comparisons.  

5. **Performance Optimization**  
   - Data model optimized to reduce load time and improve responsiveness.  
   - Aggregation techniques used to handle large datasets efficiently.  

---

### **Skills and Tools Utilized**  
- **Power BI:** End-to-end dashboard creation, including data transformation, modeling, and visualization.  
- **DAX:** Advanced measures for calculations and custom KPIs.  
- **Power Query:** Data cleaning and transformation.  
- **Data Analytics:** Interpretation of workforce trends and deriving actionable insights.  
- **Visualization Design:** Creating a user-friendly, interactive interface for HR professionals.  
- **Time Series Analysis:** Tracking organizational growth and trends over time.

---
![WhatsApp Image 2025-01-12 at 03 21 55](https://github.com/user-attachments/assets/122b038e-9a15-4221-bf6d-87105ca535b5)

---

### **Impact and Learnings**  
- Improved understanding of workforce demographics, compensation structures, and leave utilization trends.  
- Enhanced decision-making capabilities for HR teams by presenting complex data in a simple, interactive format.  
- Strengthened skills in data preparation, visualization design, and performance optimization in Power BI.  

---

### **Future Scope**  
- Integrate real-time data feeds for live dashboard updates.  
- Incorporate predictive analytics to forecast workforce trends.  
- Enhance interactivity by adding natural language query (NLQ) features available in Power BI.

---

### **Repository Contents**  
- **Power BI File (.pbix):** Includes the data model, DAX measures, and the final dashboard.  
- **Sample Data:** Anonymized sample datasets for reproducibility.  
- **Documentation:** Step-by-step explanation of the project, including screenshots of the dashboard.  
- **ReadMe:** Comprehensive project overview with deployment instructions.  
