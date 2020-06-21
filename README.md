# Student-Admission-Prediction

TEAM MEMBERS:
1. Harish Subramanian
2. T N Varunram
3. Aishwarya K H 



ABSTRACT:

Students are often worried about their chances of admission in a good  graduate school.Our model hopes to solve this issue  by predicting the  output  that gives the user  a fair idea about their admission chances in a particular university. 
This analysis should help students who are currently preparing or will be preparing to get a better idea.
The model plans on using  the supplied predictive variables (GRE score, TOEFL score, University Rating, etc) using which we predict the likelihood of admission of a new candidate.


DATASET: 

The dataset used was Graduate Admission Predition Dataset on Kaggle website. This is the link for reference: 
https://www.kaggle.com/mohansacharya/graduate-admissions


PARAMETERS: 

The following are the parameters present in the dataset, that was taken under consideration.

1. GRE Scores ( out of 340 )
2. TOEFL Scores ( out of 120 )
3. University Rating ( out of 5 )
4. Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
5. Undergraduate GPA ( out of 10 )
6. Research Experience ( either 0 or 1 )
7. Chance of Admit ( ranging from 0 to 1 )


HOW TO USE THE CODE:

1. Download the dataset from the website mentioned above and store in you local drive.
2. Open the Chance_of_Admit.ipynb  file and run it in your python console. Change the extention to .py if run in non-notebook terminal  
3. The code performs initial Exploratory Data Analysis and then runs a Simple Feed Forward Neural Network of 100 epochs
4. User input option is available where any user input value will be tested and admission chance is predicted for the indicidual scores.




