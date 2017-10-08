# Data-Visualization

## Summary
This project explored the titanic dataset provided by Udacity for creating an story in Tableau. The dataset contains the details of the people who were onborad that ship. It lists their gender, their class, age, name, passenger id, fare, cabin, survived or not, etc. [The link for the project is](https://public.tableau.com/profile/modassir.bashir#!/vizhome/Titanic_413/Story1). 

The dataset when loaded into the software needed changes in terms of data types. For example, age was a continuous variable which was changed to discrete. Similarly, we changed the data types of pclass, survived, parch ect according to the requirement. Additionally, 'Age[bin]' was created to make the graph look nice and more understandable.

By the end of the story, I have a question in mind which is economic status of the people. If we look at the fare, the difference is 5 times in comprison to the elites but marginally more than the lower class. When titanic sank in 1912, industrial revolution has set in, and hence it looks like the segreagation of middle class has only begun. The true picture can be known by diving into the history deeper. 

## Design
The story tells the relationships between the strata of the society and the position they command. I tried to look at the perspective of survivors based on gender, age and class. 

First plot is a bar chart which shows the average fare amongst the gender for survivors as well as dead ones and with mmore number of females, the avearge is higher for women. Also, if we add class to the plot. we can see that maximum contribution is coming from the 1st class female passengers. To bar chart has been used since it is very easy to compare the number and frequency for discrete categories or groups.

Next plot shows the survior count by ages of people falling in 10-35 Yrs. Clearly we can see from the graph that more men had died than women which is due to the preference that women gets in such situations. 

Third plot shows the plot of survivors with class and we can see now that 300 men of 3rd class had died which is the highest and is expected as well as poor tends to suffer maximum. Next we have a stacked bar chart which shows the breakdown between the male and female based on class in age groups. Stacked charts are great to represent the composition of categories in whole.

The plot that follows the previous one shows the fare distribution with class. By looking at it, we can access the reasons for higher fare of women. The average fare for surviveed women is 105.98 in comparison with 74.64 for men of first class while dead, the figures are 110.60 and 62.89 respectively. for other classes amount is too low to stand for camparison. This also shows the gap between the rich and poor in the society.
Next two plots shows the survivors count by class with gender and class with fare. Pie chart has been used to capture the sense of ratio beacuse that is revealed very clearly in a pie chart.Scatter plot captures the relationship between two variables and that is shown in the plot. By adding trend lines, we see that for 3rd class passengers, a strong relationship exists with survivors count.

##Feedback1
One of the feedback received was to adjust the size of the visualizations. Some charts were small and some had bigger legends. Original dataset had survivors as '1' or '0' which was suggested to be changed to 'Yes' and 'No'. Lastly, analyse the frequecy distribution of age. Based on the suggestions provided, necessary changes have been made.

##Feedback2
Include the reasons for using a particular chart and to provide link for the old workbook to compare the two work and see what improvements have been made. Link is provided below while the necessary changes regarding the choice of charts has been included in the readme file.

[The link for the previous version is](https://public.tableau.com/profile/modassir.bashir#!/vizhome/titanic_1_0/Story1) 
