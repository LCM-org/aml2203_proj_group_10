STUDENT SCORE PREDICTOR

This Project is to Predict the Final Score of the Student based on the previous grades and other external factors which affects the studies. The actual dataset is available on https://archive.ics.uci.edu/ml/datasets/student+performance and it is collected by using school reports and questionaires of 2 schools who are following the same pattern for grading. A 20 point grading scale is used in the dataset, where 0 is the lowest and 20 is the highest score. Students are evaluated in 3 periods(G1,G2, and G3). G3 corresponds to the final grade. 

Goal: 
The intention of this project is to predict the final score(G3) of Students.

Approach :
We prepared a simple UI to interact with the user. And the students are requested to answer the questionaire inorder to get their final score predicted.
The dataset is not having any null values. But we have to convert the categorical features into numerical to get the correlation of features properly. And we calculated corelation between the final grade and other features.Based on that we extracted the most positively and negatively impacting features for the final score. Using linear regression, we trained our model to Predict the final score. 

Technologies:
Python packages: Streamlit( for UI),pandas, scikit-learn

Conclusion:
Our model is able to predict the Final score based on the questionaire filled by Students. And accuracy of our model is 84%.



Group Members :
- Abbas Ismail
- Megha Chauhan
- Karthi Kuthalingam
- Gitik Kaushik
- Enrique Gonzalez Zepeda
