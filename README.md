# Project 1 - Excel Salary Dashboard

![1_Salary_Dashboard.png](/0_Resources/Datasets/Images/1_Salary_Dashboard_Final_Dashboard.gif)

## Introduction

This job salary dashboard was designed to assist job seekers in exploring salary data for their desired roles and ensuring they are receiving fair compensation.

The data comes from [Luke Barousse](https://www.lukebarousse.com/) course, which offers a solid foundation in data analysis using this powerful tool. It includes detailed information on job titles, salaries, locations, and key skills, all of which are featured in this dashboard.

### Dashboard File
Final dashboard is in [Salary_Dashboard](Project_1-Dashboard/Salary_Dashboard.xlsx).

### Excel Skills Used

The following Excel skills were utilized for analysis:

- **Charts**
- **Formulas and Functions**
- **Data Validation**

### Data Jobs Dataset

The dataset used in this project features real-world data science job information from 2023. The dataset provides detailed insights into:

- **Job titles**
- **Salaries**
- **Locations**
- **Skills**

## Conclusion

I developed this dashboard to highlight salary trends across different data-related job titles. It helps users make informed decisions about their career paths by exploring how factors like location and job type impact salaries.

# Project 2 - Analysis

## Introduction

As a former job seeker, I’ve always been curious about the lack of data on the most in-demand jobs and skills in the data science field. This led me to explore what skills top employers are seeking and how to secure higher pay.

### Key Questions for Analysis

To gain insights into the data science job market, I explored the following questions:

1. **Do more skills get you better pay?**
2. **What’s the salary for data jobs in different regions?**
3. **What are the top skills of data professionals?**
4. **What’s the pay for the top 10 skills?**

### Excel Skills Used

The following Excel skills were utilized for analysis:

- **Pivot Tables**
- **Pivot Charts**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Power Pivot**

### Data Jobs Dataset

The dataset used in this project features real-world data science job information from 2023. The dataset provides detailed insights into:

- **Job titles**
- **Salaries**
- **Locations**
- **Skills**

## 1. Do more skills get you better pay?

### Skill: Power Query (ETL)

#### Extract

- I began by using Power Query to extract the original data (`data_salary_all.xlsx`) and create two separate queries:
    - The first query contained all the data job information.
    - The second query listed the skills associated with each job ID.

#### Transform

- Next, I transformed each query by adjusting column types, removing irrelevant columns, cleaning the text to remove specific words, and trimming any excess whitespace.
    - data_jobs_salary

        ![Transform_Screen1](0_Resources/Datasets/Images/Transform_Screen1.png)

    - data_job_skills

        ![Transform_Screen2](0_Resources/Datasets/Images/Transform_Screen2.png)

#### Load

- Finally, I loaded both transformed queries into the workbook, establishing the foundation for my next phase of analysis.
    - data_jobs_salary

        ![Load_Screen1](0_Resources/Datasets/Images/Load_Screen1.png)

    - data_job_skills

        ![Load_Screen2](0_Resources/Datasets/Images/Load_Screen2.png)

### Analysis

#### Insights

- A positive correlation exists between the number of skills listed in job postings and the median salary, especially for positions such as Senior Data Engineer. Roles that require fewer skills, like Business Analyst, typically offer lower salaries, indicating that more specialized skill sets are associated with higher market value.

![Chart1](0_Resources/Datasets/Images/Chart1.png)

#### So What

- This trend highlights the importance of gaining a diverse set of relevant skills, especially for those aspiring to secure higher-paying positions.