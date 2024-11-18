# task2-data-science
### Data Handling:

Missing values in 'Genre,' 'Director,' and actor columns are replaced with 'Unknown,' and missing 'Rating' values are replaced with the average rating.
Encoding:

Categorical data (like 'Genre' and 'Director') is converted to numbers using Label Encoding.
### Features and Target:

The model uses 'Genre,' 'Director,' and actor columns to predict movie ratings.
### Model Training:

A Random Forest Regressor is trained on 80% of the data and tested on the remaining 20%.
### Model Evaluation:

The Mean Squared Error (MSE) measures prediction accuracy. A lower MSE means better predictions.
