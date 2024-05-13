<div align='center'> <h1>  GOV.UK JOB LISTING DATA </div>
<div align='center'> <h1> Data Cleaning and Transformation </div>

#### Tools Used: Excel

**Dataset Used: [Click to View](https://www.kaggle.com/datasets/mohammedderouiche/gov-uk-job-listing-data)**

  ## About

  Introducing the GOV.UK Job Listing Data Cleaning and Transformation project! The goal is to refine and enrich the dataset, making it ideal for detailed analysis and research into job market trends and patterns. The project involves a comprehensive data cleaning process and transformation of key features to improve data quality and usability. 

## About Data

The dataset contains job listings data from the UK government job portal, GOV.UK and was retrieved from Kaggle. It is made up of 14 columns and 15,655 rows.

| Column               | Description                                           | 
| :------------------- | :---------------------------------------------------- |
| id                   | Unique identifier for each job listing                |
| title                | Title of the job listing                              |
| postingDate          | Date when the job was posted                          |
| salary               | Salary offered for the job                            |
| hours                | Number of working hours for the job                   |
| closingDate          | Application closing date                              |
| location             | Job location                                          |
| state                | State or region                                       |
| city                 | City                                                  |           
| company              | Hiring company                                        |
| jobType              | Type of job (e.g., full-time, part-time)              |
| category             | Job category or field                                 |
| jobReference         | Reference code for the job listing                    |
| additionalSalaryInf  | Additional salary information, if available           |

## Applied Steps

1)	**Data Collection**: Data used for this project was retrieved from Kaggle. 

2)	**Exploratory Data Analysis**: EDA was done to understand the structure, content, and quality of the data, and to detect potential issues such as missing values, duplicates, and other inconsistencies.

3)	**Data Cleaning and Transformation:** 

- **Handling Duplicates**: Data was checked for duplicate values, and none was found.

- **Converting Date Format**. The posting_date and the closing_date columns which were originally in the (day-month-year) format ‘7-Nov-23’, was converted to the standardized format, (YYYY-MM-DD) ‘2023-11-07’ to make it suitable for analysis.
  
![image](https://github.com/Weefred/GOV.UK_Job_Listing_Data-/blob/main/pic%202.png) 

![image](https://github.com/Weefred/GOV.UK_Job_Listing_Data-/blob/main/pic%201.png)

- **Replaced Values**: Some unnecessary values were removed, and misspelt words were replaced with their correct forms.

![image](https://github.com/Weefred/GOV.UK_Job_Listing_Data-/blob/main/pic%203.png)

![image](https://github.com/Weefred/GOV.UK_Job_Listing_Data-/blob/main/pic%204.png)

![image](https://github.com/Weefred/GOV.UK_Job_Listing_Data-/blob/main/pic%205.png)

![image](https://github.com/Weefred/GOV.UK_Job_Listing_Data-/blob/main/pic%206.png)







