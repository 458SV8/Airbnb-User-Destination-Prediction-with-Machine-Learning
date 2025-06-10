Airbnb User Destination Prediction
This project focuses on solving the Airbnb New User Bookings classification challenge hosted on Kaggle. The goal was to predict the destination country for new users based on their demographic and session data.

Result
Achieved an accuracy score of 92.7, placing in the top ranks of the competition.

Feature Engineering
To enhance model performance, the following feature engineering steps were implemented:

1) Extracted year, month, and day from the date_account_created and date_first_booking fields to capture seasonal and behavioral patterns.

2) Removed the original date columns after decomposing them.

3) Handled missing values by filling them with -1 to ensure numerical stability across features.

4) Applied Label Encoding to convert all categorical text data into numerical form, enabling compatibility with machine learning algorithms.

These steps allowed the model to better interpret user behavior and timing, which contributed to the overall high prediction performance.

Tools Used
Python
Pandas
Scikit-learn
LabelEncoder

