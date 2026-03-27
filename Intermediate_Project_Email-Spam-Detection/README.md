# Email Spam Detection using Machine Learning

## Description

The objective of this project is to build a machine learning model that classifies emails as **spam** or **ham (not spam)**. The project involves text preprocessing, feature extraction using TF-IDF, and training classification models such as Naive Bayes and Logistic Regression to accurately detect spam messages.

---

## Dataset

* **Source**: Kaggle (Email Spam Dataset)
* **Description**:
  
  The dataset contains email messages labeled as:

  * `0` → Ham (legitimate email)
  * `1` → Spam (unwanted email)
    
  Each record includes:
  * `text`: the email content
  * `spam`: the label indicating whether the email is spam or not

---

## Steps Performed

1. **Data Cleaning**

   * Renamed columns for better readability
   * Removed null values
   * Converted labels into numerical format

2. **Exploratory Data Analysis (EDA)**

   * Checked distribution of spam vs ham emails
   * Analyzed message lengths

3. **Visualization**

   * Count plot for spam vs ham distribution
   * Histogram for message length comparison

4. **Model Building**

   * Text preprocessing (lowercasing, removing special characters, stopword removal, stemming)
   * Feature extraction using TF-IDF
   * Model training using:

     * Naive Bayes
     * Logistic Regression

---

## Results

* **Naive Bayes Accuracy**: ~97.73%
* **Logistic Regression Accuracy**: ~97.82%

### Key Findings:

* The dataset is slightly imbalanced (more ham than spam messages)
* Spam messages tend to have distinct word patterns
* TF-IDF effectively converts text into meaningful numerical features
* Both models performed very well, with Logistic Regression slightly outperforming Naive Bayes

### Metrics:

* High precision and recall for both spam and ham classes
* F1-score close to 1.0 indicating strong model performance

---

## Tools Used

* **Programming Language**: Python
* **Libraries**:

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn
  * NLTK

---

## Conclusion

This project successfully demonstrates how machine learning can be used for spam detection. By applying text preprocessing and TF-IDF vectorization, the models were able to achieve high accuracy. Logistic Regression slightly outperformed Naive Bayes, making it the better choice for this dataset. The project highlights the importance of feature engineering and preprocessing in text classification tasks.

---

## Author

Mohammed Shanan Hasan
