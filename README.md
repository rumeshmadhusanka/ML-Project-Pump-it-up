# Pump-it-up
URL: https://github.com/rumeshmadhusanka/ML-Project-Pump-it-up

### EDA
Mainly used Pandas Profile Report to investigate data.<br>
Most of the variables were categorical.<br>
There were varibales with high correlation.<br>
Some of them were not usable due to high amount of zero values.<br>
Target varible was imbalanced.<br>

### Feature Engineering
Removed the uniqe varibales, high correlated variables, and unusable ones.<br>
Imputed missing values with mode, median.<br>
Scaled the numerical variables.<br>
Label encoded the categorical varaibles.<br>

### Models used
Random Forest, SVM, CatBoost<br>
Feature importance was calculated using the trained models.<br>

### Score
0.8129<br>
![score](https://user-images.githubusercontent.com/32504465/133809558-1f2be476-ee3b-4eda-b5f6-4fb000055061.png)
