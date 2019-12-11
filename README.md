# Kaggle-project

#### The goal of this project is the prediction of the price of diamonds based on their characteristics (weight, color, quality of cut, etc.), putting into practice all the machine learning techniques you know.
#### The evaluation metric chosen for this competition is the RMSE (Root Mean Squared Error).

### Input Files
- data.csv: training set
- test.csv: test set
- sample_submission.csv: sample submission

### Features
#### - id: only for test & sample submission files, id for prediction sample identification
#### - price: price in USD
#### - carat: weight of the diamond
#### - cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
#### - color: diamond colour, from J (worst) to D (best)
#### - clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
#### - x: length in mm
#### - y: width in mm
#### - z: depth in mm
#### - depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
#### - table: width of top of diamond relative to widest point (43--95)

### Output Files
#### price: prediction price about test.csv
#### id: diamonds id test.csv

### Techniques, in addition to studying the problem and drawing your conclusions:
#### - Feature Scaling o MinMax Scaler
#### - Standard Scaler
#### - Logarithmic scale
#### - Get dummies
#### - PCA

### Regression models:
#### - LogisticRegression
#### - Support vector regression
#### - Ridge
#### - GradientBoostingRegressor
#### - HistGradientBoostingRegressor
#### - RandomForestRegressor
