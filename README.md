The notebook is divided into two main parts:

1.  **Part 1: Train the Model**
    *   This cell handles all the necessary setup, data loading from an online source, feature engineering, and training of the Gradient Boosting model.
    *   Run this cell first and wait for it to complete.

2.  **Part 2: Interactive TrafficTelligence Predictions**
    *   This cell provides an interactive form with sliders and dropdowns.
    *   Adjust the parameters to create a traffic scenario (e.g., time of day, weather, holiday).
    *   Run this cell to get an instant traffic volume prediction from the trained model.

## Dataset

This model is trained on the [Metro Interstate Traffic Volume dataset](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume) from the UCI Machine Learning Repository. It contains hourly traffic data along with weather and holiday features.

## Dependencies

All required libraries are installed directly within the Google Colab notebook.
- pandas
- scikit-learn
- numpy
- matplotlib
- seaborn
