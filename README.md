# Rain Prediction Using Artificial Neural Networks (ANN) 🌧️

## Overview  
- This project leverages Artificial Neural Networks (ANN) to predict whether it will rain the next day based on historical weather data. Using over 10 years of daily observations from various locations in Australia, the model was trained to make accurate predictions with a focus on data preprocessing, feature engineering, and visualization.

---

## Features  
- **Data Preprocessing:**  
  - Handled missing values for both categorical and numerical data using mode and median strategies.  
  - Encoded cyclic features for date columns using sine and cosine transformations.  
  - Removed outliers to ensure cleaner data for training.

- **Data Visualization:**  
  - Heatmaps to display correlations between attributes.  
  - Line plots and scatter plots for trends in rainfall and wind speeds.

- **Model Development:**  
  - Multi-layer ANN with Dropout and Batch Normalization for better generalization.  
  - Optimized using the Adam optimizer and a learning rate of 0.00009.  
  - Achieved **85% training accuracy** and effective validation results.

---

## Dataset  
The dataset contains 10 years of daily weather observations from various Australian locations, with 23 attributes including:  
- `Date`, `Location`, `Rainfall`, `MinTemp`, `MaxTemp`, `Humidity`, etc.  
- Target variable: **RainTomorrow** (Yes/No).

---

## Technologies Used  
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Data Analysis: `Pandas`, `NumPy`  
  - Visualization: `Matplotlib`, `Seaborn`  
  - Machine Learning: `scikit-learn`  
  - Deep Learning: `Keras`, `TensorFlow`

---
## Results
- Training Accuracy: 85%
- Validation Accuracy: 85.67%
- Precision, Recall, and Confusion Matrix are provided for detailed evaluation.
## Visualization Samples
- Heatmaps showing correlations between numerical features.
- <img width="405" alt="image" src="https://github.com/user-attachments/assets/4c0dca58-a47a-45a0-81c2-71fa6366c636">

- Line and bar plots for year-wise trends in rainfall and wind gust speeds.
- <img width="175" alt="image" src="https://github.com/user-attachments/assets/da5d00c6-58e6-4c5e-ad29-43c7b94c120e">

- Box plots to visualize data distributions before and after outlier removal.
- <img width="409" alt="image" src="https://github.com/user-attachments/assets/7c52e5df-46d0-4a47-aa63-11ec14c58838">

## Conclusion  
- This project demonstrates the effective use of Artificial Neural Networks (ANN) for weather prediction. By thoroughly preprocessing the data, engineering features, and optimizing the model, we achieved a robust prediction accuracy. The insights and techniques from this project can be applied to other time-series and classification problems, showcasing the versatility of machine learning in solving real-world challenges.

