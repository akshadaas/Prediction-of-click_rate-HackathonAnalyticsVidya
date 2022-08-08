# Click rate prediction
The objective is to Predict CTR of an Email Campaign. CTR depends on multiple factors like design, content, personalization, etc.

#Data Exploration: 

1. The target variable is highly skewed.
2. There are many categorical columns , which are in the numeric format they need to be converted.
3. ‘Is_price’ and ‘is_timer’ can be dropped as they are almost unique or unique columns.

#Feature Engineering:
Log transforms the target variable to reduce the skewness , I have added 1 before converting to the log to get rid of zeroes present in the column. The skewness is reduced due to the transformation.
