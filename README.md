# Email Spam Classification Case Study

This project focuses on building a classifier to identify spam emails using a dataset containing both spam and ham (non-spam) emails. The objective is to leverage machine learning techniques to accurately distinguish between spam and legitimate emails.

---

## Key Highlights

### 1. Exploratory Data Analysis (EDA)
- **Percentage Analysis**: Analyzed the proportion of spam and ham emails in the dataset.
- **Visualization**: Created word clouds to visualize the most common words in spam and ham emails, providing insights into their distinguishing features.

### 2. Text Preprocessing
- **CountVectorizer**: Employed CountVectorizer for text vectorization, converting the raw text data into numerical features suitable for machine learning.

### 3. Model Training and Testing
Four machine learning classifiers were trained, tested, and evaluated for performance:

| Model                  | CPU Time (Wall)  | Training Accuracy | Testing Accuracy |
|------------------------|------------------|-------------------|------------------|
| **Naive Bayes**        | 73.7 ms         | 98.69%           | 97.58%           |
| **Logistic Regression**| 2.91 s          | 99.95%           | 98.16%           |
| **Decision Tree**      | 5.37 s          | 100%             | 94.98%           |
| **Random Forest**      | 8.89 s          | 100%             | 97.39%           |

---

## Observations
- **Naive Bayes** performed well with a quick runtime and reliable accuracy.
- **Logistic Regression** achieved the best balance between training and testing accuracy, making it a strong candidate for deployment.
- **Decision Tree** perfectly fit the training data but slightly underperformed during testing, indicating possible overfitting.
- **Random Forest** demonstrated high accuracy, though at the cost of longer training times compared to Naive Bayes.

---

## Future Scope
- **Feature Engineering**: Experiment with advanced text vectorization techniques like TF-IDF to improve feature representation.
- **Deep Learning Models**: Explore LSTM or Transformer-based models (e.g., BERT) for further performance improvement.
- **Metrics**: Incorporate additional evaluation metrics such as precision, recall, and F1-score for a more holistic analysis.

---

