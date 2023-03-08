The ability to predict the likelihood of a company going bankrupt, or unable to meet its debt obligation, is important to banks, investors and the government.

This project predicts the bankruptcy risk of corporate companies and is a personal project.

It aims to answer two important questions:

What are some important financial ratio determinants in predicting bankruptcy of companies in 1999 to 2009?
Are there any non-bankrupt companies heading for bankruptcy?
There are several assumptions made:

Data is normalised and relvance of timestamp is ignored
Datapoints of 6819 is sufficient to reflect the entirety of companies in Taiwan.
A stand-alone snapshot of financial ratio at given point of bankruptcy reflects its path to bankruptcy
Other factors like political and social factors were ignored.
This data is sourced from Kaggle and originated from the Taiwan Economic Journal from 1999-2009.

Two criteria used in collecting the data samples:

at least three years of complete public information before the occurrence of the financial crisis (IPO ed for 3 years) sufficient number of comparable companies of similar size in the same industry for comparison of the bankrupt and non-bankrupt cases.
manufacturing industry composed of industrial and electronics companies (346), service industry composed of shipping, tourism, and retail companies(39), and others(93), but not financial companies. A total of 478 bankrupt companies.
I used Jupyter notebook for this project and adopted machine learning methods - Decision Tree, Random Forest, Support Vector Classifier and Extreme Gradient Boosting to predict the likelihood of bankruptcy in a company.
