# LSTM Financial Analysis

This is the final project for ECE 465 (Machine Learning for Engineers) taken during the Spring of 2019 at Bradley University. The goal of this research was to identify potential advantages offered by Long Short-Term Memory networks in developing forecasting models for time-series data. The argument behind LSTM approaches is simple: typical ANNs adjust coefficients based on the data that is immediately within the scope of exposure without reference to the preceding data points, potentially blinding the ANN to the broader data trends, LSTM networks "remember" the preceding data and thereby act based on historical context. When approaching a classification problem, such as predicting the risk of heart disease on a case-by-case basis, ANN memory is an undesirable attribute since the preceding patient record is independent of the current record under consideration. Rather, ANN memory becomes useful when the data entries are strongly dependent, such as in a time-series dataset.

The problem in question for this paper was the prediction of US stock market indices. A goal as vain as it was absurd, but this high and haughty hubris was precisely the point. Feeling particularly ironic that spring, I wanted to simultaneously discuss the intricacies and the advantages of LSTM models while debunking the notion that machine learning is some magical "solve-anything" approach that whimsical scientific wizards and hocus-pocus programming professionals brew in the black cauldron of their aggressively dark-themed terminals and then sell for all the riches of Scottland. Don't be fooled, this project is a gorgeous failure.

On that note, the code has been left in its original form, with the exception of breaking changes. This project will require Python 3.7 and older versions of many libraries which, in a few years time, may become inaccessible. However, static HTML exports of all jupyterlab notebooks have been saved into the `static/` folder and may be viewed in a browser.


Stay strange.
*Alice Seaborn.*
