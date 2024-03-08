
# Predicting Employee Churn with Random Forest: An Analysis on Salifort Motors Data

## Project Overview
This project addresses the challenge of employee churn at Salifort Motors by leveraging machine learning. Using a dataset that captures various aspects of employee engagement, performance, and satisfaction, we developed a predictive model to identify potential churn. The Random Forest algorithm was chosen for its robustness and accuracy, achieving notable results in predicting employee retention outcomes.

## Business Understanding
The primary stakeholder in this project is Salifort Motors' HR department, facing high employee turnover rates. Understanding the factors contributing to churn and identifying at-risk employees can significantly aid in developing targeted retention strategies, thereby reducing recruitment and training costs and maintaining organizational knowledge and morale.

## Data Understanding
The dataset comprises employee records over the past two years, featuring attributes such as satisfaction level, last evaluation score, number of projects, average monthly hours, tenure, and whether the employee left the company. The data also includes categorical variables representing departments and salary levels. Limitations include potential biases in self-reported measures like satisfaction and the lack of external factors such as industry trends.

## Modeling and Evaluation
- **Model Used**: Random Forest Classifier
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, AUC
- **Results**:
  - Accuracy: 97.78%
  - Precision: 94.62%
  - Recall: 91.83%
  - F1 Score: 93.20%
  - AUC: 98.13%

These metrics indicate a high-performing model capable of accurately classifying employees likely to churn.

## Conclusion and Recommendations
The model identified key predictors of churn, such as employee satisfaction levels and workload. Based on these findings, we recommend:
- Implementing career development programs for high-performing yet unsatisfied employees.
- Adjusting workloads to prevent burnout.
- Ensuring fairness and constructiveness in employee evaluations.
- Limiting the maximum number of projects assigned to an individual to avoid overburdening.

## Future Steps
To further refine the model and its predictions, future work could explore:
- Incorporating additional data, such as industry benchmarks and economic factors.
- Testing alternative machine learning algorithms for comparison.
- Conducting a deeper feature importance analysis to uncover more nuanced factors affecting churn.
