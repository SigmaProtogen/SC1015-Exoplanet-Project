# SC1015_Project
## About
This is the repository containing all relevant files for the SC1015 (Introduction to Data Science and Artificial Intelligence) Mini Project.<br>
The Jupyter .ipynb notebooks should be explored in this order: <br> 
1) dataCleaning
2) EDA
3) ML

## Contributors
[@SigmaProtogen](https://github.com/SigmaProtogen) - Data Collection, Cleaning, Exploratory Data Analysis, Presentation <br>
[@susnirvik](https://github.com/susnirvik) - Random Forest, Gradient Boosting, Naive Bayes, Presentation<br>
[@tmukh001](https://github.com/tmukh001) - Data Sourcing, Presentation <br>

## Problem Definition
> "How can we identify whether a planet is habitable or not, and what metrics of a planetary system make it habitable?"

## Machine Learning models Used
- Random Forest Classifier <br>
- Gradient Boosting Classifier <br>
- Naive Bayes <br>

## Conclusion
- Models are successful in classifying planets as habitable/uninhabitable.
- Certain physical characteristics are able to be modeled by mathematical formulas.
- Planetary Equilibrium Temperature (P_TEMP_EQUIL) is important in predicting habitability, according to Random Forest classifier.
- Habitability depends on a lot of factors, not just based on one; All features should be equally important for our survival.

## New Learning/Insights Gained
- New knowledge of multiple machine learning algorithms beyond the scope of this course.
- Gradient Boosting machine would require more regulation to prevent overfitting.
- Current level of study isn't enough, more features are currently inaccessible (eg. Atmospheric Composition, very important for humans).

## References
- Dataset Source: https://www.kaggle.com/datasets/chandrimad31/phl-exoplanet-catalog
- Outlier removal function: https://stackoverflow.com/questions/55471750/how-do-i-remove-outliers-using-multiple-columns-pandas
- Random Forest Classifier: https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/
- Gradient Boosting Classifier and Naive Bayes: https://www.analyticsvidhya.com/blog/2017/09/common-machine-learning-algorithms/
