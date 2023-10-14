# HR Attiration Analytics
 ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)  ![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346.svg?style=for-the-badge&logo=Microsoft-Excel&logoColor=white) ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF.svg?style=for-the-badge&logo=Kaggle&logoColor=white)
 
 
 </br>
 
## Overview
This project focuses on  HR Attiration and their associated metrics  , performing exploratory data analysis to generate insights and visualize them with the help of Power BI.

</br>

## Architecture
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/0f453712-ff02-4461-a574-9fddafdd8d58)

</br>

## Dashboard Preview
![1_Dn5fU1c8R_UZCx1GSLrjTg](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/5550c8e6-eaa4-44db-bf78-6f5db7fedc7e)

</br>

## Data Requirement Gathering :
     I intend to answer the following questions through this analysis:
1. Employees who have been 10 years or more since their last promotion will be promoted. What is the number and proportion of these people?
2. How many years of service do the employees have?
3. What is the distribution of occupation levels from 1 to 5?
4. We dismiss people who have spent 18 years in the company, the rest stay. How many people will be laid off and will be actively working?
5. How far are the employees from the office?
6. What is the departmental distribution of employees who will be promoted or fired, and which department will experience the most changes?
7. What are the levels of job satisfaction of the employees?
8. What is the percentage of employees working overtime?
9. When we rate the performance of employees as high or low, what are the ratios?
10. What is the total number and distribution of employees, promotions, and dismissals in occupational roles?
11. Who are the employees who will be promoted or fired?
    
</br>


## Data Collection :
  The data was downloaded from Kaggle, containing two tables — HR Analytics Data (consisting 1470 rows and 35 columns) and HR Employee Data (with 1470 rows and 2 columns). The various columns of the datasets are outlined below:

![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/271e7fa8-f7bc-4dff-ac3a-5fa8b113c243)

</br>

## Data Cleaning and Transformation :
The both datasets were imported to power query in Power BI. Data cleaning and transformation are an important aspect in data analysis process as it ensures accuracy and credibility of the insights generated from the data.

1. Using the data preview feature on Power Query, I was able to identify that there were no null values and errors for each column in the HR Analytics Data’ table.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/b8110932-9167-47ac-b4f8-938b245b50e7)

2. I created a new measure and calculated the total number of employees.

![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/11f96558-f3b8-4198-8bbd-00057250e94f)

3.Then I calculated the total number of men and women and their percentages.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/2466c2c4-82a2-417e-b618-5a29f689e605)

4.I add a new conditional column and write the metrics to identify those who have never been promoted in the last 10 years or more.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/90735e6e-c5f6-434f-8ff3-631bf8c299c0)

5. The company needs retreanch some employees for some reasons, let’s determine who those employees should be. We lay-off people that had spent above 18 years in the organization and the rest people stay.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/9e2ea634-e111-4e22-8e05-c62dc7781db6)

6.  Let’s find the ones that will work actively.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/f4aebb64-7e57-4c36-a729-c457fa4b0e2e)
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/993683dd-5af7-49c1-be70-fa2ef9c8d7e2)

7. I’m creating a conditional column that will set the distances to the employees. Those greater than or equal to 20 are very far, those greater than or equal to 10 are close, and the remainder are very close.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/0fc5c0f9-f9b4-4b14-96a7-19cd34afef51)

8. I create conditional column to determine job satisfactions. I categorize those less than or equal to 2 as high, 3 as medium and the rest as low.

![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/eba4c260-3848-40a9-ad0f-d35b7b0e835d)

9. When determining the performance ratings, I set the ones equal to 3 as high rating and the remaining ones as low grade.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/707aedd8-b368-43d7-819f-c3f4e3c53e18)
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/c23f2abb-6d88-4294-b937-fef1b82145f6)

At the end of this process, the HR Analytics Data table contain same 44 columns and HR Employees Data remain the same. Now the data is ready for exploratory analysis.

</br>

## Exploratory Data Analysis and Visualization:
First of all, I determined a color palette suitable for the design I was considering with the coolors.co tool.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/e8a45ff2-c0fa-442a-bb56-cfaddb0c191c)


Then I created a background to outline my dashboard using PowerPoint. This will provide a visually great look.

![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/af2e6ffc-5dce-453a-98ae-314572ff31cd)


In this stage, I answered the questions I raised earlier, in the data requirement gathering process.

Firstly, I displayed a quick summary/ preview of the data which will reveals some Key Performance Indicators (KPIs).

![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/7f4d8e0d-2afb-42aa-91bf-7b43f411e305)

We see that there are 1470 employees in total. The majority of them are male.
![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/9e7afedb-7306-43a9-a971-0c24fda73f16)

When we look at the cards above, it appears that 4.9% of the employees have not been promoted for 10 years or more, and they should be promoted. A total of 72 people are included in this group.

When we consider the years of service, we can see that the majority of employees have either served for 5 years or are in their first year. There are 44 people who have just started, while the number of employees who have served for more than 30 years is quite high.

In the bar chart depicting occupation levels, it is evident that 69 people are at the highest level, while the majority of employees are at level 1–2.

We lay-off people that had spent above 18 years in the organization and the rest people stay. Based on the information provided in the upper right cards, it appears that 117 employees need to be laid off, which corresponds to 0.8% of the total workforce.

The donut chart displays the distance of the employees from the office, and upon examination, it appears that the majority of the employees live very close to the office. 15.58% of the employees may face difficulty in commuting to the office.


Let’s take a look at our details page now

![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/e0d3e6ce-5db3-4a44-b7b2-8500db96f5d1)

The column chart above illustrates the number of retrenches and promotions by department. Notably, changes are expected to occur, particularly in the research and development department. On the other hand, the number of employees who will be promoted in the human resources department is relatively low.

Upon reviewing the job satisfaction graph, it is apparent that while most employees are highly satisfied with their jobs, there is also a significant number of employees with low job satisfaction. It would be beneficial to identify the reasons for this. Initiating studies to increase employee satisfaction and motivation may prove to be helpful.

The pie chart reveals that the majority of employees do not work overtime. Approximately one in four employees work overtime.

On the cards located on the right-hand side, the percentages of performance grades expressed by the numbers 3 and 4 were provided. It appears that 84.6% of the employees received high ratings, which is a positive outcome.

Upon analyzing the table, it is evident that the number of total employees, total promotions, and total number of employees who will be laid off can be easily determined by categorizing them according to their job roles. The horizontal columns make the data more comprehensible.

Finally, when we click on the action page.

![image](https://github.com/Pranjali-d/HR_powerBI_Report/assets/49934575/2463359b-5d34-4899-a483-f2224c53623c)

With the HR Employees Data join we have performed, we can list and display the names of employees who will be promoted or dismissed as a result.

</br>

## Insights:
1. 1470 employees, 72 of whom have not been promoted for 10 years or more, need to be promoted.
2. The majority of the employees have been working for at least 5 years. There are 44 new employees.
3. 117 employees who have been with the company for 18 years or more need to be laid off. The employees’ job levels are mainly 1 and 2.
4. 47 employees in the research and development department will be promoted, and 74 will be laid off. The biggest change is seen in this department.
5. The employees’ job satisfaction levels do not create significant differences. Although there are more employees with high job satisfaction, 459 employees have low job  satisfaction.
6. Approximately 30% of the employees work overtime.
7. 84.6% of the employees have a high performance rating. 15.4% have a low performance rating.
8. The sales manager role has the highest number of employees. The highest number of promotions and layoffs are in the manager role.
  
 </br>
  
## Recommendations :
1. There are 72 employees out of 1470 who will be promoted. This number was determined for those who have not been promoted for 10 years or more. If the chance of promotion is given in shorter periods instead of a minimum of 10 years, employee motivation can be increased.
2. Instead of laying off 117 employees with 18 years or more of service all at once, a performance-based layoff can be implemented.
3. In-service training can be provided to level 1 and 2 employees to improve their skills and advance their levels.
4. Interviews can be conducted with employees who have low job satisfaction levels to analyze the reasons. Then, improvement efforts should be made to address their concerns.

</br>

## Resource
 You can browse the github repository to access the dashboard and backgrounds [here](https://github.com/Pranjali-d/HR_powerBI_Report/blob/main/Resource.md).
