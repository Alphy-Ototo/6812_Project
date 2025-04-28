#   Home Credit Default Risk Project

## Business Problem and Objective

- Home Credit is focused on expanding financial inclusion by offering loans to individuals with limited credit history. However, assessing default risk accurately remains a critical challenge. 
- The objective of our project was to develop a machine learning solution that predicts the likelihood of a customer defaulting, helping Home Credit make smarter lending decisions while minimizing financial losses.

## Modelling Solution

- We explored and compared several machine learning models, including Logistic Regression, Random Forest, XGBoost, and a Stacking Classifier. After evaluating their performance using AUC-ROC as the primary metric, we found that XGBoost significantly outperformed the others with an AUC-ROC score of 0.76. We experimented with stacking ensembling methods to further enhance predictive power, XGBoost xhowever, remained the most robust model, particularly in handling complex data patterns. We recommended that Home Credit implement the XGBoost model into their lending decision process to improve risk assessment and support more responsible lending.
- Within our team, I was primarily responsible for training, tuning, and evaluating the machine learning models. I handled model selection, hyperparameter optimization, performance analysis, and comparison across different metrics. I also contributed to addressing class imbalance issues and ensuring that model evaluation remained aligned with business goals, balancing both interpretability and predictive performance.

## Recommendation to Home Credit

- By integrating the XGBoost model into their operations, Home Credit can significantly increase the accuracy of its default predictions, leading to better credit risk management, fewer loan defaults, and improved profitability. This will result in estimated savings of $ 1.36 billion. This solution also supports Home Credit’s mission of promoting financial inclusion while maintaining a healthy and sustainable loan portfolio.

## Challenges and Key Takeaways from this Project

- One of the main challenges we faced was the severe class imbalance in the dataset, which caused some models, particularly the Stacking Classifier, to heavily favor the majority class. Logistic Regression also experienced convergence issues due to feature scaling and the complexity of data patterns. These difficulties pushed us to experiment with class weighting, advanced hyperparameter tuning, and thoughtful model selection strategies to achieve better balance and predictive performance.

- Through this project, I learned the importance of aligning technical decisions with business objectives, especially when dealing with imbalanced datasets. I deepened my skills in training, tuning, and evaluating advanced machine learning models and understood the practical challenges of deploying models in real-world settings. This experience reinforced how critical model evaluation is, not just for accuracy, but also for delivering meaningful business value.


  
  

