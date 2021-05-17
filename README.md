# Predictive Analytics in Human Resources <br>
### By Praneel Rastogi - 53 <br> 
### Aditya Mohan - 42 <br> 
### Mayank Motwani - 43 <br>

The Human Resources department is in charge of taking care of employee’s well being and ensuring they are happy with their position. With machine learning you can actually predict employee attrition to see what causes a valuable employee to leave or stay with a company. This is perfect for HR managers planning their hiring and auditing employee experience.<br>
<br>
## What is Employee Attrition?
According to Jobzology, “Staff attrition refers to the loss of employees through a natural process, such as retirement, resignation, elimination of a position, personal health, or other similar reasons. With attrition, an employer will not fill the vacancy left by the former employee.”

## Reasons to Predict Employee Attrition
With machine learning, HR managers will be able to foresee vacant positions, team budget needs, what employee benefits they can improve to keep employees happy, what departments are the most and least likely to stay at a position for a length of time, and more. As a business, you can predict questions like,

#### What causes employee churn?
#### Why do we lose valuable employees?
#### When will an employee most likely leave the company?
Predicting these things would save a lot of money in the long run. According to the Center of American Progress,
“For positions that earn between $30,000 and $50,000 per year, the cost of replacement was found to be 20% of annual salary. For executives earning high salaries, the cost of replacement was found to be 213% of annual salary. (Boushey & Glynn, 2012). For example, an executive who earns $100,000 would cost $213,000 to replace.”

With the increasing economic burden on companies due to the chaos created by the COVID-19 Pandemic, it is necessary for the companies to take strategic steps in order to push back the financial distress they could go through. This means reducing the expenditure and one of the ways to do this is by cutting down on the workforce. Cutting down employees or reducing an employee's salary is a tough decision to take. These decisions have a powerful impact on the lives of the people it affects and therefore needs to be taken with utmost care and consideration. Therefore it is necessary to identify the employees whose performance is attriting may lead to sabotaging of both employees' career and the company's reputation in the market.

## Aim of The Project
To predict Employee Attrition by the given data about his/her past history.

The output would be a predicted probabilty between 0 and 1.
Here 1 will indicate that the employee will leave the company 
And 0 will indicate the employee that will stay in the company

To predict how long has the Employee worked in the current company.

The output value would be a floating point integer.


## Data fields
1)Id - an anonymous id given to an Employee <br>
2)Age - Age of an Employee<br>
3)Attrition - Did the Employee leave the company 0-No, 1-Yes <br>
4)BusinessTravel - Travlling frequency of an Employee<br>
5)ContrinutionIndex - Employee performance on an elevated scale <br>
6)DailyRate - Employee's earnings per day <br>
7)Department - Work Department <br>
8)DistanceFromHome - Distance of office from home <br>
9)EducationField - Field of Education <br>
10)EmployeeNumber - Number of Employees in the division of a given Employee <br>
11)EnvironmentSatisfaction - Work Environment Satisfaction <br>
12)Gender - Gender of Employee <br>
13)JobRole - Role of Employee in the company. <br>
14)HourlyRate - Employee's earnings per hour . <br>
15)MartialStatus - Martial Status of an employee <br>
16)MonthlyIncome - Monthly Income of Employee in USD <br>
17)NumCompaniesWorked - Number of Companies in which Employee has worked before joining this Company <br>
18)OverTime - Does The person work overtime <br>
19)PercentSalaryHike - Average annual salary hike in percentages <br>
20)RelationshipSatisfaction - Subjective evaluation of one's relationship <br>
21)StockOptionLevel - Company stocks given to an Employee <br>
22)TotalWorkingYears - Total working experience of an employee <br>
23)TrainingTimesLastYear - No. of trainings an employee went through last year <br>
24)TechnicalExpertise - No. of technical skills the employee is expert in . <br>
25)YearsAtCompany - Number of years worked at this company <br>
26)YearsInCurrentRole - Number of years in current role <br>
27)YearsSinceLastPromotion - Number of years since last promotion <br>
28)YearsWithCurrManager - Number of years with the current manager <br>
29)Education - Educational Qualifications of the Employee . <br>
1 'Junior college' 2 'Diploma' 3 'Degree' 4 'Masters' 5 'PHD' <br>
30)EnvironmentSatisfaction - Level of satisfaction of the employee in the work environment . <br>
1 'Low' 2 'Medium' 3 'High' 4 'Very High' <br>
31)JobInvolvement - Level of involvement the employee has in the respective project . <br>
1 'Low' 2 'Medium' 3 'High' 4 'Very High' <br>
32)JobSatisfaction - Level of satisfaction of the employee with the job . <br>
1 'Low' 2 'Medium' 3 'High' 4 'Very High' <br> 
33)JobLevel - Categories of authority in an organization <br>
1 'Entry' 2 'Intermediate' 3 'Mid' 4 'Senior' 5 'Executive' <br>
34)PerformanceRating - Employee's rating based on performance <br>
1 'Low' 2 'Good' 3 'Excellent' 4 'Outstanding' <br>
35)Behaviour- Employee's behaviour with other colleagues <br>
1 'Good' 2 'Bad' 3 'Not Rated' <br>
36)CommunicationSkill - Employee's level of communication <br>
1 'Bad' 2 'Average' 3 'Good' 4 'Better' 5 'Best' <br>
37)StockOptionLevel - Level of quantity of stocks the employee owns . <br>
0 'No stocks' 1 'Less Stocks' 2 'Moderate Stocks' 3 'A lot of Stocks' <br>
