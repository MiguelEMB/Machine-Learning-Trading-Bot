# Machine-Learning-Trading-Bot
Enhancing algorithmic trading systems using machine learning. I establish a baseline performance, tune the trading algorithm by adjusting parameters, evaluate a new machine learning classifier, and create an evaluation report. Results are summarized in the README.md file with PNG images for analysis.

### Impact of Increasing Training Window

#### Support Vector Classifier (SVC)

When the training window was increased from 3 months to 18 months, the SVC classifier performed better with the new training dataset. The following plots demonstrate the difference in performance:

##### Training Window: 3 Months

![SVC 3-month training window](./Resources/Images/Adam_3_monthd.png)

##### Training Window: 18 Months

![SVC 18-month training window](./Resources/Images/adam_18_months.png)

The results indicate that the increased training window allowed the SVC classifier to capture more historical patterns and make more accurate predictions.

#### AdaBoost Classifier

Contrary to the SVC classifier, the AdaBoost classifier performed worse with the new training dataset of 18 months. The following plots illustrate the difference in performance:

##### Training Window: 3 Months

![AdaBoost 3-month training window](path/to/adaboost_3_months_plot.png)

##### Training Window: 18 Months

![AdaBoost 18-month training window](path/to/adaboost_18_months_plot.png)

The results suggest that the AdaBoost classifier struggled to generalize well with the increased training window, potentially indicating overfitting or an imbalance between the historical patterns and the current market conditions.
