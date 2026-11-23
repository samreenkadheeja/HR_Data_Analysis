# HR Employee Data Analysis (MNC Dataset)

This is my first data analysis project in Python using Google Colab, focused on exploring and cleaning human resources (HR) employee records across departments, job titles, experience levels, employment statuses, and salaries in INR.

## Tools & Libraries Used
- **Python** & **Google Colab**
- **Pandas** & **NumPy** (data cleaning, filtering, grouping, aggregations, and feature engineering)
- **Matplotlib** & **Seaborn** (data visualizations)

## What's Inside (`Python_project.ipynb`)
1. **Data Inspection & Cleaning:** Converted `Hire_Date` to datetime, removed `Unnamed: 0`, checked nulls and duplicates, and handled missing values (`Work_Mode`, `Status`, `Experience_Years`, and `Salary_INR` filled using the average salary for IT Software Engineers).
2. **Dataset Properties, Filtering & Feature Creation:** Checked DataFrame properties and slices, filtered by department and salary threshold, renamed `Full_Name` to `Full_Name_Of_Employee`, and created a `Bonus` column (`0.1%` of `Salary_INR`).
3. **Salary Ranking, Group Comparisons & Correlation:** Ranked top and bottom salaries, grouped by performance rating and department/job title, built a department summary table, and checked correlations among numeric columns.
4. **Data Visualizations:** Created scatter, line, bar, histogram, box, and strip plots using Seaborn to explore salary, experience, departments, and employment status.
5. **Conclusion & Key Takeaways:** Summarized findings and next steps for future analysis.
