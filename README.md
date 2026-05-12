# Sentiment Analysis on YouTube Comments

This project performs sentiment analysis on real YouTube comments using Machine Learning techniques. Comments are classified as Positive, Neutral, or Negative using TF-IDF feature extraction and a Random Forest Classifier.

## Features
- Exploratory Data Analysis (EDA) with visualizations
- Data cleaning (null removal, deduplication, non-English filtering)
- Class imbalance fix using oversampling
- TF-IDF feature extraction with unigrams and bigrams
- Model training with Random Forest Classifier
- Model evaluation with accuracy score, classification report, and confusion matrix
- Word cloud visualization per sentiment class
- Live sentiment predictor for custom comments
- Model comparison: Random Forest vs Logistic Regression

## Tech Stack
| Tool | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Scikit-learn | ML model, TF-IDF, train-test split, metrics |
| Matplotlib / Seaborn | Data visualization |
| WordCloud | Text visualization |

## Dataset
- Source: Kaggle (YouTube Comments with Sentiment Labels)
- Size: 18,409 comments
- Columns: `Comment`, `Likes`, `Sentiment`, `Video ID`
- Labels: `0.0` = Negative, `1.0` = Neutral, `2.0` = Positive

## Project Workflow
1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. EDA Visualizations
5. Data Cleaning
6. Class Imbalance Fix
7. Feature Extraction (TF-IDF)
8. Model Training
9. Model Evaluation
10. Confusion Matrix
11. Word Cloud Visualization
12. Overall Audience Mood
13. Live Sentiment Predictor
14. Model Comparison (Bonus)
15. Conclusion

## Results
- Final Accuracy: ~78-82%
- Best Model: Random Forest Classifier
- Majority of YouTube comments are Positive

## Future Improvements
- Use BERT (Transformer model) for higher accuracy
- Deploy as a web app using Flask or Streamlit
- Analyze sentiments per YouTube channel or topic

## Author
**Vaibhav Mathur**  
Roll Number: UA2504CDH181  
Degree: B.S.M.S (Computer Science and Data Analytics)
