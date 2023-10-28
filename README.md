## Data Jobs Salaries

This dataset was retrieved from this [page](https://ai-jobs.net/salaries/download/)</br>
This dataset is on [kaggle](https://www.kaggle.com/datasets/lorenzovzquez/data-jobs-salaries)

This repository contains analysis about data jobs globally across different experience levels and different backgounds, the main process for these analysis starts from cleaning and wragling data using the Pandas library in Python, then, the output has been used to create a report using the Power BI tool for business intelligence.


## Data elements

Our dataset contains the columns as shown below:

**work_year**: The year the salary was paid.

**experience_level**: The experience level in the job during the year with the following possible values:
 - EN: Entry-level / Junior 
 - MI: Mid-level / Intermediate 
 - SE: Senior-level / Expert 
 - EX: Executive-level / Director

**employment_type**: The type of employement for the role, mainly: 
- PT: Part-time 
- FT: Full-time 
- CT: Contract 
- FL: Freelance

**job_title**: The role worked in during the year.

**salary**: The total gross salary amount paid.

**salary_currency**: The currency of the salary paid as an ISO 4217 currency code.

**salary_in_usd**: The salary in USD (FX rate divided by avg. USD rate of respective year via data from fxdata.foorilla.com).

**employee_residence**: Employee's primary country of residence in during the work year as an ISO 3166 country code.

**remote_ratio**: The overall amount of work done remotely, possible values are as follows: 
- 0: No remote work (less than 20%) 
- 50: Partially remote/hybrid 
- 100: Fully remote (more than 80%)

**company_location**: The country of the employer's main office or contracting branch as an ISO 3166 country code.

## Key questions

These questions below and visualizations should help us to get started with out data visualization report:

**General Analysis:**</br>
   1. What is the distribution of salaries across different years?</br>
   2. How does salary vary by experience level?</br>
   3. What is the most common employment type in the dataset?</br>
   4. What are the top job titles in the dataset?</br>
   5. What is the distribution of salaries by job title?</br>
   6. How does salary vary by employee residence country?</br>
   7. Is there a correlation between the remote work ratio and salary?</br>

**Currency Conversion:**</br>
   8. How does the salary in USD vary across different years?</br>
   9. What is the distribution of salaries in USD by experience level?</br>
   10. How does salary in USD vary by job title?</br>

**Remote Work:**</br>
   11. What is the distribution of remote work ratios in the dataset?</br>

**Geographic Analysis:**</br>
   12. How does the company's location relate to the salary in USD?</br>

**Time-Series Analysis:**</br>
   13. Are there any seasonal trends or patterns in salaries over the years?</br>

**Combining Factors:**</br>
   14. How does the combination of experience level and employment type affect salary?</br>
   15. Is there a relationship between remote work and salary, considering experience level and employment type?</br>



https://chat.openai.com/share/3740fff8-ef5f-4553-a71e-710791dfce51