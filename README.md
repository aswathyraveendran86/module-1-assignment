# module-1-assignment
Project Title: Healthcare Data Analysis and Insights 
Project Steps and Objectives:
1.Number of missing values calculated by the sheet hospital details and medical examination by using formula countif like this =COUNTIF(A2:A2344,"?")
2.take the year average in excel sheet and fill the year. Then replace the month septemper in missing position using powerquery.
3.Used the Group By feature in Power Query to determine the mode (most frequently occurring value) for the ‘smoker’, ‘Hospital tier’, and ‘City tier’ columns. The missing values in these columns were replaced with their mode values.
4.Used Power Query to identify missing values in the ‘State ID’ column and replaced them with ‘Unknown’.
Data Transformation: 
5.Used Power Query to split the ‘names’ column in the “Customer Names” table into three columns: ‘Title’, ‘First Name’, and ‘Last Name’, making the customer data 
6.Used Power Query to replace non-numeric characters in the ‘NumberOfMajorSurgeries’ column of the “Medical Examinations” table with 0 and converted the column to a numerical data type.
7.Used Power Query to identify inconsistencies in the ‘Heart Issues’ and ‘smoker’ columns and standardized the values by applying proper capitalization to maintain data consistency.
8.Created a new column named ‘Weight Status’ using Power Query’s Conditional Column feature to categorize BMI values into Underweight, Normal Weight, Overweight, and Obesity based on the specified BMI ranges.
9.using if condition diabetic status calculated in normal,prediabetic and diabetic
10.create new date of birth colomn and merge year,month ,date using by powerquery then its changed date formate using excel
11.calculated age  with in the date 8 jun 2023  using powerquery
12.currency changed in excel window
13. crete 6 pivot table and its chart
Created a new worksheet named ‘Healthcare’ and combined the three tables using VLOOKUP with ‘Customer ID’ as the common key. Retained all 17 required columns for further analysis.
Analyzed the distribution of cancer history among smokers and non-smokers using a Pivot Table and Pie/Donut Chart.

Compared the total number of major surgeries and average HbA1C levels between patients with and without a history of transplants using a Pivot Table and suitable chart.
3. Compared healthcare charges across different Weight Status and Diabetes Status categories using Pivot Tables and Column/Bar Charts.

4. Compared average healthcare charges across hospital tiers within different states using a Pivot Table and suitable chart. 5. Explored the correlation between Age and BMI, and between Age and HbA1C, using Scatter Plots.

6. Analyzed the relationship between Age and healthcare charges using a Scatter Plot to identify possible trends and correlations.
