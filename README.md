# MediSense
**Disease Prediction Model**

MediSense is an advanced predictive model designed to identify potential diseases based on user-provided symptoms. In addition to disease prediction, the application offers tailored health management solutions, including precautions, diet recommendations, medication suggestions, and workout plans.

## Features

- **Accurate Disease Prediction**: Predicts potential diseases with high accuracy using machine learning models trained on a robust dataset of 4,919 entries.
- **Health Management Recommendations**: Provides personalized precautions, dietary guidance, medication suggestions, and workout plans to support user health.
- **Dual Model Accuracy**:
  - Achieved **96.72% accuracy** with the **MultinomialNB** model.
  - Achieved **83.60% accuracy** with the **GradientBoostingClassifier**.
- **Interactive User Experience**: A seamless interface to input symptoms and receive actionable insights.

## Technologies Used

- **Machine Learning Libraries**:
  - **Pandas** and **NumPy**: For data preprocessing and manipulation.
  - **Matplotlib**: For visualizing data and performance metrics.
  - **Scikit-learn**: For implementing and evaluating machine learning models.
- **Models**:
  - Multinomial Naive Bayes (MultinomialNB)
  - Gradient Boosting Classifier


## Dataset

The model is trained on a comprehensive dataset comprising 4,919 entries, which includes a wide range of symptoms and corresponding diseases. Data preprocessing was carried out to ensure high-quality training and evaluation.

## Folder Structure
```
MediSense/
├── data/           # Dataset and preprocessing scripts
├── models/         # Trained machine learning models
├── static/         # Static files for the interface (if applicable)
├── templates/      # HTML templates (if applicable)
├── app.py          # Main application script
├── requirements.txt# Python dependencies
├── README.md       # Project documentation
```



---

### Contributors

- **Siddhant Chatse** - [GitHub](https://github.com/sid1309)

