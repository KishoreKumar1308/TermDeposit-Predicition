# Term Deposit Predicition
Machine Learning approach to analyze the trend of Customers Term deposit based on their Financial details

# Models Used

Two models were built for the analysis:
* Decision Tree
* Logistic Regression

Both the models were analyzed based on their outputs and was tuned to get best fit using Search methods.

# Decision Rules and Feature Importance

Decsion rules of the tree were extracted and compared with feature importance. The rules extracted were equivalent to the inferences made from the analysis.

![image](https://user-images.githubusercontent.com/62205360/152161000-2de60216-de13-4980-b169-71047e169005.png)

- Duration attribute has the highest coefficient.
- Postcome of the last campaign is the second highest. 
- Some attributes do have negative coefficients. 
- Housing loan makes the most negative impact.

# Conclusion:

Both Decision Tree and Logistic regression has similar results. They have similar accuracies and ROC curves. The Decision rules formed were in accord with the feature importance plot and the EDA performed. 

To have an successful campaign:

- The target audience must be young age and elderly(retired) people.
- Their previous Outcome to be positive.
- The Customer must be engaged for atleast 6 minutes.
