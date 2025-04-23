# My Excel Data Analysis Project
## Salary Dashboard
### Salary Analysis
This data jobs salary dashboard was created to help job seekers investigate salaries for their desired jobs and ensure they are being adequately compensated.

![WhatsApp-Video-2025-04-23-at-3 44 42-PM](https://github.com/user-attachments/assets/bd2678b3-8278-412e-b84b-64650fbe28b7)

### Excel skills used
The following Excel skills were utilized for analysis:

📊 Charts

🧮 Formulas & Functions

✅ Data Validation

### Data Jobs Dataset
The dataset used for this project contains real-world Data Science job information from 2023. It was provided through my Excel course, which focuses on building a strong foundation in data analysis using Excel.

The dataset includes detailed information on:

🧑‍💼 Job Titles

💰 Salaries

📍 Locations

🛠️ Skills



### 📊Charts

<img width="350" alt="1" src="https://github.com/user-attachments/assets/07b16fd1-4cec-4820-98df-1ab89d51b590" />

Data science- ob seekers bar chart

🌟 Excel Features Utilized bar chart feature with formatted salary values and optimized layout for clarity.

🎨 Design choice: Horizontal bar chart for visual comparison of median salaries. 

🗂️ Data organization: Sorted job titles by descending salary for improved readability.

📊 Insights gained: This enables quick identification of salary trends noting that senior roles and engineers are higher paying than analysts roles.



### Country Median Salaries - Mapchart


<img width="350" alt="1" src="https://github.com/user-attachments/assets/3fe189f2-a2a6-4dfa-b722-015cde791137" />


🗺️Excel features:  Utilized Excel map chart feature to plot median salaries globally.

🎨Design choice:  Color coded map to visually differentiate salary levels across regions.

📍Data representation:  Plotted median salary for each country with available data.

👁️Visual enhancement:  Improved readability and immediate understanding of geographic salary trends.

💡Insights gained:  Enables quick grasp of global salary disparities and highlights high or low salary regions.





### 🧮 Formulas and Functions

💰 Median salary by job title

=MEDIAN( 
IF( 
  (jobs[job_title_short]=A2)*
  (jobs[salary_year_avg]<>0) * 
  (jobs[job_country]= country) *
  (ISNUMBER(SEARCH(type,     
  jobs[salary_year_avg]     
  )   
) 


🧪 Multi criteria filtering: Checks job title, country, schedule type excludes blank salaries.

📐 Array formula: Utilizes median() function with nested if() statement to analyze an array.

🎯 Tailored insights: Provide specific salary information for job titles, regions and scheduled types.

🧾 Formula purpose: This formula populates the table below returning the median salary based on job title, country and type

### Backgroud table

<img width="350" alt="1" src="https://github.com/user-attachments/assets/c7104eeb-7055-4d38-bb73-d241e56949de" />


### Dashboard Implementation:


<img width="350" alt="1" src="https://github.com/user-attachments/assets/64a0df9f-2120-424f-8876-be811600894a" />




### ✅ Data validation:

📋 Filtered list:

🛡️ Enhanced data validation: Implementing the filter list to as your data validation rule under the job title, country, and type option in the data tab ensures:

1️⃣ User input is restricted to predefined validated scheduled types

2️⃣ Incorrect or inconsistent entries are prevented

3️⃣ Overall usability of the dash bodies enhanced




<img width="350" alt="1" src="https://github.com/user-attachments/assets/5269807e-ac18-4927-a539-025d4f7bfcbd" />




I created this dashboard to showcase insights into salary trends across various data related job titles. utilizing data from my Excel course and this dashboard allows users to make informed decisions about their career paths. Exploring the functionalities to understand how the trend and job type influence salaries.










