# Data Science Projects

Python/Jupyter projects from coursework and personal work:

- **NetflixCustomerChurn.ipynb** — Classifies whether a Netflix customer will churn using a KNN model (k=50) on a stratified 80/20 split. 5-fold cross-validation 0.78, ROC-AUC 0.90, accuracy 0.81. The model is deliberately tuned to favor catching churners (false positives over false negatives).
- **CFPTransferPortal.ipynb** — Predicts which conference a college football transfer-portal player lands in, comparing Random Forest and Logistic Regression. Honest result: the available features carried little signal, and the write-up says so.
- **WavePrediction** — Forecasts significant wave height from NOAA buoy 51001 data (wind speed/gust, pressure, dominant wave period). Trained on 2024 and tested on 2025: linear regression beat random forest out of sample (the forest overfit 2024), a clean example of distribution shift.
