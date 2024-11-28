# Power BI Project: Human Resources KPIs

**Overview**

This repository contains a Power BI report to visualize and analyze key Human Resources (HR) performance indicators. It provides insights into various HR metrics designed to provide actionable insights. By visualizing key metrics and trends, this report empowers HR professionals to make data-driven decisions and optimize workforce strategies.

**Key Features**

* **Executive Overview:**

  - Monitor employee Headcount : Total number of employees, active employees, and terminated employees.
  - Visualize employee distribution by status(active, terminated), position and department.
  - Track number new hires per day, month, quarter or year.
  - Monitor Hire-Termination trend : Number of terminations VS number of new hires.

* **Employee Demographics:**

  - Visualize employee distribution by age, gender, marital status, location.
  - Track employee performance : Results from ratings and goals achieved.
  - Track employee satisfaction: Results from employee surveys or feedback mechanisms.

* **Experience:**

  - Identify Long-standing employee :  The employee who is still active and was the first hired employee.
  - Identify Junior employee : The employee who is still active and  is the latest hired employee.
  - Track employee distribution by number of years of experiecnce rangs(0-2, 2-4, 4-6, ....) 
  - Track employee experience by employee status(active, terminated voluntarily, terminated for cause).
  - Analyze the relationship between salaries and number of years of experience.

* **Turnover:**

  - Analyze talent retention, Leaver Staff and  turnover rate trends.
  - Monitor current staff vs retention variation.


**Technical Details**

* **Data Model:** A Dimension-Only Model is used to organize the data.
* **DAX Measures:** Several DAX measures are created to calculate key metrics, such as employee turnover rate, talent retention, leaver staff, Last Hired Active Employee, ...
* **Visualizations:** The report includes various visualizations, including bar charts, line charts, pie charts, card visuals, scatter chart, stacked/clustered column chart, map and area chart.
* **Slicers:**  slicers allow users to drill down into specific data segments by date(turnover section), Hiring year and department.
* **Drill-Down Capabilities:** Explore data at different levels of granularity (hierarchies) : department-position, date-month-quarter-year.

 **How to Use:**
 Follow the demo video to know how to use the report well.
 demo video link : https://www.youtube.com/watch?v=t2JuBpXXwmA
 

**Future Enhancements**

* **Predictive Analytics:** Incorporate predictive modeling to forecast employee attrition and identify potential high-performers.
* **Advanced Analytics:** Utilize advanced analytics techniques to uncover deeper insights into workforce trends.
* **Integration with Other Systems:** Integrate the dashboard with other systems, such as payroll and learning management systems.

By leveraging the power of Power BI, this dashboard provides a valuable tool for HR professionals to make informed decisions and drive organizational success.
