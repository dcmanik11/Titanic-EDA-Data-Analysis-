# TITANIC-EDA
Dataset https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

At this time, I will try to do Data Preprocessing first so that the data becomes clean and good to use. After the Data Preprocessing is done, Exploratory Data Analysis is carried out which will get useful insights, including:
> - How many passengers are still alive?
> - What gender is the most victimized?
> - What age has survived the most?
> - Is the passenger class aware of safety?
## DESCRIPTION
> Input Variable
- pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd
- sex	Sex	
- Age	Age in years	
- sibsp	# of siblings / spouses aboard the Titanic	
- parch	# of parents / children aboard the Titanic	
- ticket	Ticket number	
- fare	Passenger fare	
- cabin	Cabin number	

> Output Variable
- survival - Survival	0 = No, 1 = Yes

> Variable Notes

> pclass: A proxy for socio-economic status (SES)
- 1st = Upper
- 2nd = Middle
- 3rd = Lower

> age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

> sibsp: The dataset defines family relations in this way...
- Sibling = brother, sister, stepbrother, stepsister
- Spouse = husband, wife (mistresses and fiancés were ignored)

> parch: The dataset defines family relations in this way...
- Parent = mother, father
- Child = daughter, son, stepdaughter, stepson
- Some children travelled only with a nanny, therefore parch=0 for them.
