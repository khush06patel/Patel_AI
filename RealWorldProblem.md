Part One

What is the business problem?
A: The business problem I chose is employee turnover, which happens when an employee leaves the company that they work at and then they need to be replaced. A high employee turnover can make it very difficult for the company to keep experienced workers and maintain a stable workforce. A company can also have lots of trouble knowing which employees are likely to leave before they actually resign or quit. Therefore, AI can help by analyzing employee information, and finding patterns that are connected to employee turnovers. The final goal for the AI model would be to identify employees who are or may be at a higher risk of actually leaving their company.

Why is this problem important to the organization?
A: Employee turnover is very important because finding replacement employees can cost the company lots of time and money. The company needs to spend money on recruiting, interviewing, and training the new employees, and then keeping up on paying the employees is a completely different issue, so it costs lots of money. When an employee leaves, other employees may need to take on the responsibility of what the employee did before they left, until that position is filled. High turnover rates can also lower the productivity in the company, and it makes it harder for each employee to complete their work. If the company can actually understand why the employee leaves their company, it can be very helpful for the company to understand why they leave, and in turn it’ll help them reduce their high turnover rates.

Who is affected by this problem?
A: The employee turnover rate actually affects the working employees, management, the human resource department, and also affects the entire company as a whole. Employees may actually have to take on additional work when their coworkers leave, which can also affect that employee because they now have to manage two different things. Managers may also have a hard time keeping their teams fully staffed and productive. Human resources has to spend more time finding and hiring replacement employees. The company as a whole can also lose experienced workers who have very valuable knowledge and skills working there. Which hurts the company's stocks, their main income, and many other things.

Part Two

Question
Answer
What data set would you need?
I would need the employee information that actually explains why some employees leave the company while others stay. The Kaggle dataset includes information such as age, attrition, business travel, daily rate, department, distance from home, education, education field, employee count, employee number, environment satisfaction, gender, hourly rate, job involvement, job level, job role, job satisfaction, marital status, monthly income, monthly rate, number of companies worked, over 18, over time, percent salary hike, performance rating, relationship satisfaction, standard hours, stock option level, total working years, training times last year, work life balances, years at company, years in current role, years since last promotion, and years with current manager. The main thing is the attrition column which shows whether the employee has left the current company, this is very good information that could be used to help the AI system to find patterns related to an employee turnover. 
Where could the data come from?
For this, the date comes from the IBM HR Analytics Employee Attrition & Performance dataset on Kaggle. In an actual company like in a random place in Pennsylvania, this information could come from human resource records, payroll systems, attendance records, employee surveys, and even performance reviews. These sources provide useful information about employees and their actual work history at a certain company.
How much historical data might be useful?
The current dataset from Kaggle, has approximately 1,470 employee records, which gives the AI model plenty of information to learn from. In a real business, several years of employee data can be very useful, because it would include employees who stayed and employees who may have left. Having more historical data will help the AI model find stronger patterns of employee turnover and make better decisions based off of these records.
What would be the most important variables?
Some of the most important variables could be monthly income, job satisfaction, overtime, the years worked at the company, work life balances, the environment satisfaction, their job involvement, and years since their last promotion. All of these variables could help show whether their certain work conditions are connected to the employees leaving that company. 
What could be missing or inaccurate?
What can be missing or even inaccurate is the possibility of employee data being outdated. Like for example the job satisfaction ratings can be different from when they last took a survey, and it won’t actually show what the employee feels about their current position. Information such as income, job position, and even work-life balance could also change over time. Since the Kaggle dataset is fictional, it may not represent every single situation that could actually happen at a real company.

Part Three
What information would you give the model?
A: Some of the information that I would give to the AI model would be the employee features that could help show whether the employee is likely to leave the company. Here are the features that I would add from the Kaggle dataset:
Monthly Income
Job Satisfaction
Over Time
Years at Company
Work Life Balances
Environment Satisfaction
Job Involvement
Years Since Last Promotion
These features can help the AI model to look for patterns between employee’s work conditions and then make a decision on if they will leave the company in the future.

What would you want the model to determine?
I would like the model to determine the target/output of the attrition column. Which shows whether the employee left the company or stayed. The model will use the employee features to help determine if they will leave or stay.

Target: Attrition → Simple Yes or No
It would return as: Likely to Leave or Not likely to Leave.


Part Four
Would you choose supervised or unsupervised learning?
A: Supervised Learning, because the Kaggle dataset already shows whether each employee has already left the said company and or has stayed at the said company. The attrition column gives the AI model the right answer for each employee as a simple yes or no. The model can also use historical data to learn patterns between employee features and their final outcome. The AI model can compare things like if they were frequent in overtime, or what their job satisfaction level is, what their monthly income is, and how long they have worked at said company, and finally if they have left or stayed at the company. After the AI model learns these patterns it’ll be easier for it to determine if their current employee is at a risk of leaving or not.

Would the problem involve classification or prediction?
A: Classification, because the model will place employees into two different categories. The first category will have employees who are likely to leave, and the second category is those employees who are likely not to leave the company. Again the model will use the employee features to help decide which category an employee falls under. Since the output of the target is a simple yes or no for the attrition, it makes it a classification problem. Then the company can use these results to help identify those employees who may need to have more attention or even have some support.

Part Five
Identify three possible data-quality problems.
A: Here are the three possible data-quality problems that it can face, very outdated information about an employee, inaccurate employee survey responses, and biased or unrepresented data. 

What could happen if the data is poor:
A: If the data is very poor, or very inaccurate, the AI model that we train could make a bad decision about which employees are likely to leave the company. Like if the job satisfaction feature is outdated or income information, it can cause the model to misunderstand the data and also the employees current situation, and in return it can make a very bad decision. The inaccurate survey answers could also make the model learn weird patterns that aren’t actually connected to an employee’s situation which it can interpret as it is correct and move on. If the company uses the data given by the AI model and trusts it to the point where they rely heavily on this, it can cause the managers to make very poor decisions. The company should have accurate and updated data before using an AI model to help with the employee turnover. 

Part Six
Business Problem: 
A: The business problem I chose is employee turnover, which happens when an employee leaves the company that they work at and then they need to be replaced. A high employee turnover can make it very difficult for the company to keep experienced workers and maintain a stable workforce. A company can also have lots of trouble knowing which employees are likely to leave before they actually resign or quit. Therefore, AI can help by analyzing employee information, and finding patterns that are connected to employee turnovers. The final goal for the AI model would be to identify employees who are or may be at a higher risk of actually leaving their company.

Data Needed:
A: The data needed would be the employees information from the Kaggle dataset such as monthly income, job satisfaction, overtime, years at the company, work-life balance, environment satisfaction, job involvement, and years since the last promotion. The attrition column also would be important because it shows whether an employee has stayed at the company or has left the company.

AI/ML Approach:
A: The AI/ML approach would be the use of employee information to train the AI model, and its main purpose is to find patterns connected to employee turnovers. The model would actually need to compare the employee features such as job satisfaction, their monthly income, how long they have stayed at the company, and if they have left before or even stayed. Eventually after the AI model trains and learns off of those things, it’ll then help the company determine if their current set of employees are at a risk of leaving their company, and it can determine it based off of the trained datasets it has been given.

Type of Learning:
A: I would use supervised learning because the Kaggle dataset already shows if an employee has left their company or even stayed at the company. The attrition column gives the AI model the actual answer for each employee as a simple yes or no. This will allow the AI model to learn from previous examples and use those examples and pattern finding skills on the current working employee.

Model Output:
A: The model output would be actually based on the attrition target and would return a simple classification of: 
Likely to Leave / Likely not to Leave.

The model will use the employee features to help determine which category to put the employee in.

Business Benefit:
A: The business benefit would help the company identify hard working employees who may be at a higher risk of leaving before they quit or resign. The company can look at things as job satisfaction, overtime, work-life balances, their monthly income, or opportunities for promotion to understand why that employee may want to leave. This can eventually help the company reduce employee turnover, and it’ll help keep experienced workers, and it can save time and money from having to constantly recruit new employees just for them to leave in the future. 

Potential Risk:
A: One potential risk is that the AI model can make incorrect decisions about whether an employee is actually going to leave or not. Like if the information for that employee is heavily outdated, and inaccurate, the model could learn those incorrect patterns and can make incorrect decisions, and later on the managers can heavily rely on this information and then it can cost them lots of money. 

