# EDA-on-Jobsites
Performed Web Scrapping on Job sites like Indeed, Monster, SimplyHired . Exploratory Data Analysis was further performed on the dataset to draw meaningful insights.
Summary

Objectives:

Exploratory data analysis of data science job listings
Understand top skill combinations and job locations
Salary distribution and it's relationship to top skills and job locations
Clarify analysis by segmenting the job listings by job type: job titles with "Data Scientist" segmented from "Data Engineer", "Data Analyst", and "Data Science Intern"

Approach:

For this analysis the dataset is from job postings scraped from three job sites: SimplyHired.com, Monster.com and Indeed.com

Insights/Conclusion:
What are the typical job titles listed in Data Science? And their distribution
*   Top job titles are very straightforward and align to the defined broader job categories: "Data Scientist", "Data Engineer", and "Data Analyst"

Geographical distribution of jobs in this segment?

Salary range and its correlation to location if any.

*   Within sample dataset, the states with highest amount of jobs were California, Virginia, and Massachusetts
*   Looking at average salary by state and job category:
    *   Virigina had the most number of job openings for a Data Analyst, the jobs in Massachussettes pay roughly \$10,000 more than jobs in Virigina
    *    California had the most number of job openings for a Data Scientist, however the jobs in Massachussettes pay roughly \$10,000 more
    
Most common skill combinations in this segment. E.g., Python, Jupyter, Spark, Hadoop etc.

*   Reviewing the frequency that job skills show up in job descriptions, then drilling down to Data Scientist salary by skill: key skills include statistics, machine learning, python, SQL, Spark and Hadoop
   *    Statistics is mentioned in almost 70% of Data Scientist job descriptions while in less than half of the other job categories
            *    For those Data Scientist job descriptions referencing statistics skills, the distribution skews to higher salaries
   *    Machine learning mentioned in almost 60% of data scientist job descriptions and in just under 30% of data engineer job descriptions
            *    For those Data Scientist job descriptions referencing machine learning skills, the distribution skews to higher salaries
   *   Python is the most common programming language mentioned in job descriptions. Python is mentioned in 60% of Data Scientist job descriptions and in just under half of the other job categories.
           *    For those Data Scientist job descriptions referencing Python, the distribution skews to slightly higher salaries 
   *    Most common data warehousing and processing skils referenced were SQL, Spark, Hadoop, and Hive. SQL was mentioned in 40%-50% percent of job postings. For Data Scientist and Data Engineer job categories, Hadoop and Spark were referenced in approximately 20% of job descriptions
            *    For those Data Scientist job descriptions referencing SQL skills, the distribution is concentrated in a narrower range of salaries
            *    For those Data Scientist job descriptions referencing Hadoop or spark the distribution skews to higher salaries





