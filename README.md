# Human-Activity-Recognition-using-Machine-Learning-on-Time-series-Data

Developing a model to predict human activities such as Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, and Laying. This time series classification task aimed to accurately classify each activity from new data points using the Human Activity Recognition Dataset from the UCI dataset repository.

The dataset was collected from 30 individuals performing activities with a smartphone attached to their waists. The data, recorded using the smartphone's accelerometer and gyroscope, was labeled based on video recordings.

I approached this project in two phases:

Phase 1: Classical Machine Learning

Data Preprocessing and Exploration: I started with the pre-engineered dataset, performing exploratory data analysis (EDA) to understand the data better.
Model Building: I applied several classical machine learning algorithms including Logistic Regression, Linear SVC, Kernel SVM, Decision Tree, Random Forest, and Gradient Boosting. I used the Confusion Matrix and multi-class log-loss metrics to evaluate these models. Among these, Linear SVC and Kernel SVM showed the highest accuracy, around 96.47%.
Phase 2: Deep Learning

Data Handling: For the raw dataset, I implemented a Long Short-Term Memory (LSTM) network. The LSTM model was used to capture the time series patterns directly from the raw sensor data.
Model Architecture: Initially, I used a single-layer LSTM model, achieving around 90% accuracy. I then developed a two-layer LSTM model with hyperparameter tuning, which improved the accuracy to 91%.
The LSTM models performed exceptionally well, even without feature engineering, demonstrating the power of deep learning in handling raw time series data.

Results and Conclusion:

Machine Learning Models: Logistic Regression, Linear SVC, and Kernel SVM performed well with the pre-engineered features, achieving accuracies around 95-96%.

Deep Learning Models: The two-layer LSTM model with hyperparameter tuning achieved the highest accuracy of 91%. The LSTM models were particularly effective in capturing the complex patterns in the raw sensor data.
