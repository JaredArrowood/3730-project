# To-Do List for Stock Price Prediction with KNN

## 1. Define Objective

- [ ] Decide between regression (predict price) or classification (predict up/down).

## 2. Data Preparation

- [x] **Collect Data:** Use APIs like `yfinance` or Alpha Vantage for historical stock data.
- [x] **Clean Data:** Handle missing values and remove outliers.
- [x] **Feature Engineering:**
  - [x] Use past price windows (e.g., last 5 days) and technical indicators (SMA, RSI, etc.).
  - [x] Normalize or standardize features.
- [x] store data in a CSV file so we don't have to download it every time
- [ ] **Split Data:** Time-based split (e.g., 80% train, 20% test).

## 3. Implement KNN

- [ ] Choose \(k\) (start with \(\sqrt{n}\), tune later).
- [ ] Select distance metric (e.g., Euclidean, Manhattan).
- [ ] Predict:
  - [ ] **Regression:** Average neighbors’ values.
  - [ ] **Classification:** Majority vote of neighbors’ labels.

## 4. Evaluate Model

- [ ] **Metrics:**
  - [ ] Regression: MAE, MSE, \(R^2\).
  - [ ] Classification: Accuracy, F1-score, confusion matrix.
- [ ] Visualize predictions vs. actual values.

## 5. Optimize

- [ ] Tune \(k\).
- [ ] Test weighted KNN.
- [ ] Refine features (e.g., window size, indicators).
