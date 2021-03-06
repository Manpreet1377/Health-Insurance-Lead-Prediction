# Health-Insurance-Lead-Prediction (An intermediate's approach)
Your Client FinMan is a financial services company that provides various financial services like loan, investment funds, insurance etc. to its customers. FinMan wishes to cross-sell health insurance to the existing customers who may or may not hold insurance policies with the company. The company recommend health insurance to it's customers based on their profile once these customers land on the website. Customers might browse the recommended health insurance policy and consequently fill up a form to apply. When these customers fill-up the form, their Response towards the policy is considered positive and they are classified as a lead.

Once these leads are acquired, the sales advisors approach them to convert and thus the company can sell proposed health insurance to these leads in a more efficient manner.

Now the company needs your help in building a model to predict whether the person will be interested in their proposed Health plan/policy given the information about:

- Demographics (city, age, region etc.)
- Information regarding holding policies of the customer
- Recommended Policy Information

![data dictionary](https://user-images.githubusercontent.com/51187449/110295896-ad001900-8017-11eb-8d58-022150f78574.PNG)


## Evaluation Metric
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

After using several combinations of models, features, and hyperparameter tuning, an LGBM Classifier was used for predicting the values of Response column(Target Variable).

- Since it was my first time participating in a hackathon with a classification problem, I read extensively and referred various articles and notebooks to boil down to this approach. Sharing my perspective/approach as an intermediate (for classification models), I believe that this notebook can serve as a starting point for beginners in their exploration of binary classification problems. 
