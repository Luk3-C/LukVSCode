# Data Science Projects

Projects I've done in Python and Jupyter, from classes and on my own.

- **NetflixCustomerChurn.ipynb** — Predicts whether a Netflix customer will churn. I used a KNN model (k=50) with a stratified 80/20 train/test split. 5-fold cross-validation was 0.78, ROC-AUC 0.90, accuracy 0.81. I set it up to catch more churners, even if that means more false positives.
- **CFPTransferPortal.ipynb** — Predicts which conference a transfer-portal football player will end up in. I compared random forest and logistic regression. The features I had didn't predict it well, so this one mostly shows what didn't work.
- **WavePrediction** — Predicts wave height from NOAA buoy 51001 data (wind speed, gusts, pressure, wave period). I trained on 2024 and tested on 2025. Linear regression did better than random forest on the test year because the forest overfit 2024.
