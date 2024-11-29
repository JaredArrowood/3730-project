# To-Do List for Stock Price Prediction with KNN

## 1. Define Objective

- [x] Classification problem (predict up/down).

## 2. Data Preparation

- [x] **Collect Data:** Use APIs like `yfinance` or Alpha Vantage for historical stock data.
- [x] **Clean Data:** Handle missing values and remove outliers.
- [x] **Feature Engineering:**
  - [x] Use past price windows (e.g., last 5 days) and technical indicators (SMA, RSI, etc.).
  - [x] Normalize or standardize features.
- [x] store data in a CSV file so we don't have to download it every time
- [x] **Split Data:** Time-based split (e.g., 80% train, 20% test).

## 3. Data Visualization (before normalization)

- [x] **Plot:** Stock price over time.
- [ ] Histograms
  - [ ] Close
  - [ ] Volume
- [ ] Boxplot of features to check for outliers.

## 4. Data Visualization (after normalization)

- [ ] **Correlation Matrix:** Heatmap of feature correlations.

## 5. Implement KNN

- [ ] Choose \(k\) (start with \(\sqrt{n}\), tune later).
- [ ] Select distance metric (e.g., Euclidean, Manhattan).
- [ ] Predict:
  - [ ] **Regression:** Average neighbors’ values.
  - [ ] **Classification:** Majority vote of neighbors’ labels.

## 6. Evaluate Model

- [ ] **Metrics:**
  - [ ] Regression: MAE, MSE, \(R^2\).
  - [ ] Classification: Accuracy, F1-score, confusion matrix. Using test data.
- [ ] Visualize predictions vs. actual values.

## 7. Optimize

- [ ] Tune \(k\).
- [ ] Check the ratio of Increase/Decrease in the stock price.
  - [ ] If the ratio is not balanced, use weighted KNN.
- [ ] visualize predictions vs. actual values after optimization.
