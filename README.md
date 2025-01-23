# Twitter Sentiment Analysis

This project focuses on sentiment analysis of tweets from major companies such as FIFA, Facebook, and Google. The goal is to determine whether the sentiment expressed in these tweets is positive or negative using Natural Language Processing (NLP) techniques and machine learning models.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Related Work](#related-work)
3. [Main Points](#main-points)
4. [Experiments](#experiments)
   - [Data Exploration](#data-exploration)
   - [Data Visualization](#data-visualization)
   - [Data Preprocessing](#data-preprocessing)
   - [Model Building and Evaluation](#model-building-and-evaluation)
5. [Models Used](#models-used)
6. [Results](#results)
7. [How to Use](#how-to-use)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

---

## Introduction

Sentiment analysis is a method of determining whether a text has a positive or negative sentiment. In this project, we analyze tweets from major companies like FIFA, Facebook, and Google to classify them as positive or negative using NLP techniques. The project involves data exploration, preprocessing, model building, and evaluation.

---

## Related Work

Several studies have been conducted on sentiment analysis using various predictive algorithms. Some of the algorithms used in previous experiments include Logistic Regression (70% accuracy), Random Forest (72% accuracy), and KNN (63% accuracy).

---

## Main Points

The main objective of this project is to build models that can analyze tweet texts and predict whether they are positive or negative. We use several machine learning algorithms and compare their performance. The dataset includes both textual data (tweet content) and categorical data (company name, tweet ID, etc.).

---

## Experiments

### Data Exploration

The dataset consists of two parts: a training set and a test set. The training set contains 74,682 rows and 4 columns: `Tweet_UniqueID`, `Entity`, `Sentiment`, and `Tweet_content`. The test set contains 1,000 rows with the same columns.

- **Tweet_UniqueID**: Unique identifier for each tweet.
- **Entity**: The company associated with the tweet.
- **Sentiment**: The sentiment of the tweet (positive or negative).
- **Tweet_content**: The text content of the tweet.

During data exploration, we removed 2,700 duplicate rows and 326 rows with missing values. Additionally, neutral and irrelevant tweets were removed.

---

### Data Visualization

We created visualizations to show the distribution of positive and negative tweets, as well as the number of tweets per company.

![image](https://github.com/user-attachments/assets/f95ccdfc-8f1f-42ab-886f-2d148023182a)

---

### Data Preprocessing

The text data was preprocessed by:
- Converting all text to lowercase.
- Removing links, HTML tags, and special characters.
- Removing stopwords and performing stemming.
- Tokenizing the text.

---

### Model Building and Evaluation

We built and evaluated several machine learning models, including:
- Decision Tree
- Naive Bayes
- KNN
- Logistic Regression
- Random Forest
- SVC
- Bernoulli Naive Bayes
- LinearSVC

The models were evaluated based on accuracy, recall, precision, and F1 score.

---

## Models Used

1. **Decision Tree**: A tree-like model that splits the data based on feature values.
2. **Naive Bayes**: A probabilistic model based on Bayes' theorem.
3. **KNN (K-Nearest Neighbors)**: A non-parametric method that classifies data points based on their proximity to other data points.
4. **Logistic Regression**: A regression model used for binary classification.
5. **Random Forest**: An ensemble method that builds multiple decision trees and combines their outputs.
6. **SVC (Support Vector Classifier)**: A model that finds the optimal hyperplane to separate classes.
7. **Bernoulli Naive Bayes**: A variant of Naive Bayes that works with binary features.
8. **LinearSVC**: A linear support vector classifier optimized for large datasets.

---

## Results

The performance of the models is summarized in the table below:

| Model            | Accuracy | Recall | Precision | F1 Score |
|------------------|----------|--------|-----------|----------|
| Decision Tree    | 0.8931   | 0.8938 | 0.8944    | 0.8931   |
| Naive Bayes      | 0.5377   | 0.5336 | 0.5403    | 0.5156   |
| KNN              | 0.7642   | 0.7654 | 0.7682    | 0.7638   |
| Logistic Regression | 0.5340 | 0.5364 | 0.5385    | 0.5286   |
| Random Forest    | 0.8766   | 0.8723 | 0.8769    | 0.8708   |
| SVC              | 0.5340   | 0.5328 | 0.5333    | 0.5317   |
| BernoulliNB      | 0.5046   | 0.5040 | 0.5040    | 0.5039   |
| LinearSVC        | 0.5230   | 0.5166 | 0.5275    | 0.4670   |

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/FathyHesham/Twitter_Sentiment_Analysis.git
   ```
2. Run the Jupyter Notebook or Python script to explore the data, preprocess it, and train the models.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any inquiries or further information, feel free to reach out:

- **Mail**: [fathyhesham2001@gmail.com](mailto:fathyhesham2001@gmail.com)
- **LinkedIn**: [Fathy Hesham Fathy](https://www.linkedin.com/in/fathy-hesham-fathy/)

---

**Thank you for visiting our project!** 🚀
