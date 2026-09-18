## What are the features?
A: The features are the following: monthly income, job satisfaction, overtime, years at the company, work-life balance, environment satisfaction, job involvement, and years since the employee's last promotion. These features will help the AI model to find patterns between the employee's working conditions, and if they will leave the company soon.

## What is the label?
A: The label would be Attrition, which would let the company know whether the employee left the company or stayed. The final prediction the AI model will make is Likely to leave or Likely to Stay.

## What would training data contain?
A: The training data would contain historical employee data along with the features and the actual attrition result. For example, it could include the employee's monthly income, job satisfaction, overtime, years at the company, work-life balance, and the other features listed. The AI model could use those and the past data as examples to learn patterns and connect it to employee turnovers. From my dataset, I'd use 40 total employees. The first 20 employees will be used for training the AI model. From looking at the dataset, out of the 20 employees being trained, 3 of the employees already have left the company while the other 17 have stayed. The AI model can learn from these 20 employees and start trying to learn the main pattern.

## Why should testing data be kept separate?
A: The testing data should be kept separate because the AI model should be only tested on employee's information that it did not already see. If the model was tested using the same information that it was already trained on, it could simply memorize that previous data that was trained on and it'll just give the output of what already happened. It can look like it is very accurate but overall, it'll just be outputting answers it already knows. So using different data will make it so you can actually test if the AI model is giving the right prediction of the employee if they will leave or stay. I'd use the first 20 employees as training my AI model, and the other 20 employees for separate testing.

## What could be a false positive?
A: One possible false positive could be that the AI model predicts that the employee is going to leave the company, when in reality the employee actually stays and doesn't leave the company. Like if the AI model predicts that the employee is going to leave because it looked at the employee's low job satisfaction, the amount of overtime worked was high, and in reality the employee actually stayed. The management or anyone who is like their supervisors can spend lots of time and maybe even money to make their job satisfaction go up, and maybe let them not do lots of overtime, in reality it's hurting them by spending that money and the employee stays.

## What could be a false negative?
A: One possible false negative can be that the AI model predicts that the employee is going to stay, but in reality the employee actually leaves the company. This can be a major problem because the company doesn't realize that you're going to be leaving the company, and they couldn't have helped the employee, because all this time they thought that employee was going to stay.

## Would precision or recall be more important?
A: For this AI model I believe that recall is more important, because recall focuses on finding as many of the actual positive cases as humanly possible. In an employee turnover case, the positive is the employee leaving the company. Therefore I think the recall is more important, and it could be worse for the company to completely miss an employee who is at an actual risk of leaving than it would be to have an incorrect flag on an employee who will end up staying. The false positive may cause the company to give an employee some more attention and support, but the actual false negative could mean losing a very experienced employee without even realizing they were going to leave. Out of the 40 employees data, 9 employees left the company while the other 31 stayed. Since fewer employees left, recall is very important since I would want the AI model to identify as many of those employees who may leave as much as possible.

## What types of poor-quality data could affect this model?
A: Some poor quality data would be like very old historical employee data that isn't up to date information on the employee, if the employee provides inaccurate survey responses, and if the employee has missing information in their profile, duplicate records, and even biased data. If the employee's job satisfaction level has changed, and the information hasn't been updated, the AI model could learn wrong patterns which will in the end give the company a bad prediction.

## What could cause this model to overfit?
A: The data that it's trained on, like for example if the AI model is solely trained on 20 employees. It can easily start memorizing the information and outcomes of these specific employees, instead of the model learning the main pattern about employee turnover. The model can perform very well on the training employees but it can perform horribly when it's given new employee data.

## What would make you trust—or not trust—the model's predictions?
A: I would trust the model more if it made very good predictions on the employees that were kept separate for testing and if the employee data is very up to date. I would also look at the model's accuracy, precision, and recall instead of solely relying on one measurement only. I wouldn't trust the model yet since the number of employees that the model is going to be tested on will be very small, and also because the amount of employees leaving is smaller than the employees staying.




