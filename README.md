# 2204919_ce888_assignment2

Predicting Stress from Physiological Signals
This project aims to predict stress levels from physiological signals such as Electrodermal Activity (EDA), Heart Rate (HR), and Skin Temperature (TEMP). The dataset used in this project was provided by a hospital, and the project was commissioned by a company that aims to commercialize a stress prediction tool based on physiological signals.

Dataset
Date source: https://datadryad.org/stash/dataset/doi:10.5061/dryad.5hqbzkh6f

Analysis
The data was visualized using scatter plots and a correlation matrix heatmap. It was observed that there was a moderate positive correlation between EDA and stress label, and a moderate negative correlation between HR and stress label. However, there was no clear correlation between TEMP and stress label.

A logistic regression model was trained on the EDA, HR, and TEMP signals to predict stress label. The model achieved an accuracy of 74.23%, a precision of 24.75%, a recall of 33.33%, and an F1-score of 28.40% on the test set.

Conclusion
While there is some evidence of a correlation between physiological signals and stress levels, the model's performance is not strong enough to guarantee good predictions for the hospital. The company should continue to explore other features that could improve the model's performance or consider using more sophisticated machine learning models. Further analysis of the dataset could also reveal additional insights that could be used for future feature development.
