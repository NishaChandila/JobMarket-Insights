# Job Market Analysis Project

## **Introduction**

My project focuses on **Job Market Analysis**, where I analyze trends related to job roles, salaries, industries, and company characteristics. The dataset includes key metrics such as average salary by job title, company size, industry, along with company ownership, revenue, and job counts. The goal is to provide insights into salary distributions, job market demand, and how company characteristics impact salaries, helping job seekers and employers make data-driven decisions.

As a data analyst, I first cleaned and prepared the dataset to ensure its accuracy, removing duplicates, handling missing values, and standardizing formats. Afterward, I created an interactive **Power BI dashboard** designed for non-technical stakeholders. The dashboard uses clear visuals like charts, KPIs, and slicers to provide an easy-to-understand overview of job market trends and key metrics, allowing stakeholders to explore the data and make informed decisions.

[Data Cleaning & EDA](https://github.com/NishaChandila/Data-cleaning/blob/main/Data%20Cleaning%20and%20Transformatin%20%5BDS%20jobs%5D.ipynb)  
[Dataset here](https://github.com/NishaChandila/Data-cleaning/blob/main/Dsjobs_cleaned.csv)  
[Power BI Dashboard](#)

## **Data Structure**

The dataset used in this project contains detailed job market information, focusing on various factors such as job roles, salaries, company characteristics, and industry trends. It offers insights into how different industries, company sizes, and ownership types influence salaries and job demand. The data provides a comprehensive view of the job market, which is valuable for job seekers, employers, and analysts. By analyzing this dataset, I was able to uncover trends related to salaries, job availability, and company dynamics, offering valuable insights for decision-making.

### **Dataset Preview**

![Dataset](https://github.com/NishaChandila/project-assets/blob/main/jobs-data.PNG)

### **Columns in the Dataset:**

- **Job Title**: The specific role or position in the company.
- **Salary Estimate**: The estimated salary range for the job role.
- **Rating**: The rating given to the company, typically by employees.
- **Company Name**: The name of the company offering the job.
- **Location**: The geographical location of the job.
- **Headquarters**: The location of the company's main office.
- **Size**: The size of the company (number of employees).
- **Type of Ownership**: The ownership structure of the company (private, public, etc.).
- **Industry**: The industry to which the company belongs.
- **Sector**: The broader sector in which the company operates (e.g., tech, healthcare).
- **Revenue**: The annual revenue of the company.
- **Competitors**: Other companies that are competitors in the same industry.
- **Min Salary**: The minimum salary offered for the job role.
- **Max Salary**: The maximum salary offered for the job role.
- **Avg Salary**: The average salary for the job role.
- **Company Age**: The age of the company (years since establishment).
- **Same State**: Indicates whether the job is in the same state as the company headquarters.
- **Python**: Indicates if the job requires Python as a skill.
- **Excel**: Indicates if the job requires Excel as a skill.
- **Hadoop**: Indicates if the job requires Hadoop as a skill.
- **Spark**: Indicates if the job requires Spark as a skill.
- **AWS**: Indicates if the job requires AWS as a skill.
- **Tableau**: Indicates if the job requires Tableau as a skill.
- **Big Data**: Indicates if the job requires Big Data skills.

[Dataset here](https://github.com/NishaChandila/Data-cleaning/blob/main/Dsjobs_cleaned.csv)  

## **Executive Summary**

This project focuses on analyzing **job market trends**, with a particular emphasis on salary distribution, job availability, and the characteristics of companies across various industries. The dataset analyzed includes over **600 job listings** from different industries, providing a detailed view of salary ranges, job titles, company sizes, and other key metrics. The analysis aims to help **job seekers** and **employers** make informed decisions based on current job market conditions.

![Home](https://github.com/NishaChandila/project-assets/blob/main/jobs1.PNG)

### **Key findings include:**

![Sales](https://github.com/NishaChandila/project-assets/blob/main/jobs2.PNG)

- **Top Industries**: The **Investment Banking** and **Asset Management** industries have the highest job counts, with **13%** of the total job listings.
- **Salary Trends**: **Data Scientists** and **Computer Scientists** both command an average salary of **$271,000**, making them among the highest-paid roles.
- **Company Ownership**: There are **397 private companies** and **153 public companies** in the dataset, with private companies having a higher presence in the market.
- **Industry Salary Comparisons**: The **Publishing** industry offers the highest average salary of **$271,000**, while the **Health, Beauty, and Fitness** sector offers an average of **$204,000**.
- **Company Size**: Companies with **51–200 employees** offer an average salary of **$127,200**, while those with **5001–10000 employees** offer **$126,400** on average.
- **Top Companies**: The top five companies offering the highest average salary of **$271,000** are **CompuForce**, **10x Genomics**, **Creative Circle**, **Alaka**, and **Aptive**.

In conclusion, the insights derived from the dataset provide valuable guidance for job seekers and employers. Job seekers can focus on high-paying industries like **Investment Banking** or **Publishing**, while employers can use the data to benchmark salaries and understand industry-specific trends.

[Power BI Dashboard](#)

## **Data Cleaning & EDA**

The first step in the analysis was cleaning the dataset to ensure accuracy and consistency. This involved handling missing values, removing irrelevant symbols, and standardizing formats. Additionally, key skills were extracted from job descriptions to enrich the data for more targeted analysis.

- **Dropped NA Values**: Removed rows with missing critical data like salary estimates and job titles.
- **Removed Irrelevant Symbols**: Eliminated unnecessary symbols and extra spaces from columns like salary and company names.
- **Extracted Skills**: Key skills such as Python, Excel, and AWS were extracted from job descriptions and added to the dataset.

[Data Cleaning & EDA](https://github.com/NishaChandila/Data-cleaning/blob/main/Data%20Cleaning%20and%20Transformatin%20%5BDS%20jobs%5D.ipynb) 

## **Recommendations**

- **Target High-Demand Industries**: 
  - **Investment Banking** and **Asset Management** account for **13% of job listings**. Job seekers should focus on these industries for more opportunities.
  
- **Pursue High-Paying Roles**: 
  - **Data Scientists** and **Computer Scientists** earn an average salary of **$271,000**, making these positions highly attractive for job seekers. Employers should offer competitive salaries to attract top talent.
  
- **Consider Private Companies**: 
  - There are **397 private companies** compared to **153 public companies**, indicating that private companies present a significant opportunity for job seekers.
  
- **Salary Benchmarking by Industry**: 
  - The **Publishing industry** offers the highest average salary of **$271,000**. Job seekers should target this industry for higher-paying roles.
  
- **Optimal Company Size**: 
  - Companies with **51–200 employees** offer an average salary of **$127,200**, while those with **5001–10000 employees** offer **$126,400**. Mid-sized companies can offer a more dynamic work environment.
  
- **Top Companies for High Salaries**: 
  - Companies like **CompuForce**, **10x Genomics**, **Creative Circle**, **Alaka**, and **Aptive** offer the highest average salaries of **$271,000**. Job seekers should target these companies for high-paying opportunities.

These recommendations provide a roadmap for both job seekers to target lucrative opportunities and for employers to stay competitive in the job market.

# **Conclusion**

In conclusion, this job market analysis project has provided valuable insights into salary trends and job availability across different industries. After cleaning the dataset and creating an interactive Power BI dashboard, the complex data is now easily accessible for both job seekers and employers. Key findings include that **Data Scientists** and **Computer Scientists** earn an average salary of **$271,000**, while **Investment Banking** and **Asset Management** industries have the highest job counts, with **13%** of all listings. The dashboard highlights trends such as the higher salaries offered by **private companies** (**397** listings) compared to **public companies** (**153** listings), and the significant salary variations across industries, with **Publishing** offering the highest average salary of **$271,000**. This project offers stakeholders a data-driven approach to make informed decisions on salary expectations, hiring strategies, and career planning, making it a valuable tool for navigating the job market.

[Data Cleaning & EDA](https://github.com/NishaChandila/Data-cleaning/blob/main/Data%20Cleaning%20and%20Transformatin%20%5BDS%20jobs%5D.ipynb)  
[Dataset here](https://github.com/NishaChandila/Data-cleaning/blob/main/Dsjobs_cleaned.csv)  
[Power BI Dashboard](#)
