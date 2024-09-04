
Steps
The project involves the following steps:
1.	Data exploration: try to know data and represents statistics for the important features among the features and the target attribute.
2.	Preprocessing the data. The goal of this step is to extract features from records in the training set and use these features to test data sets. Note that the data have “unknown” values need to be cleaned. 
3.	Use classification-learning methods provided by Python to learn models from the set of training examples. You can use any of the classification methods (decision tree, regression, KNN, …) for this purpose. You should build at least two different and fundamentally distinct models (e.g., one decision tree and one regression). Note that two decision trees with different attributes count as one model.
4.	Test the learned models on the test set and report the testing results.


Attribute Information:
1.	age (numeric)
2.	job: type of job (categorical: 'admin.', 'blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired', 'self-employed', 'services', 'student', 'technician', 'unemployed', 'unknown')
3.	marital: marital status (categorical: 'divorced', 'married', 'single', 'unknown'; note: 'divorced' means divorced or widowed)
4.	education: (categorical:  'basic.4y', 'basic.6y', 'basic.9y', 'high.school', 'illiterate', 'professional.course', 'university.degree', 'unknown')
5.	housing: has housing loan? (categorical: 'no', 'yes', 'unknown')
6.	loan: has personal loan? (categorical: 'no', 'yes', 'unknown')
7.	contact: contact communication type (categorical: 'cellular', 'telephone')
8.	month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
9.	day_of_week: last contact day of the week (categorical: 'mon', 'tue', 'wed', 'thu', 'fri')
10.	duration: last contact duration, in seconds (numeric). 
11.	campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
12.	pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
13.	poutcome: outcome of the previous marketing campaign (categorical: 'failure', 'nonexistent', 'success')
14.	nr.employed: number of employees - quarterly indicator (numeric)
15.	Target Attribute: Subscribed - has the client subscribed a term deposit? (binary: 'yes','no')

