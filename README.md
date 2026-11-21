# Drug Consumption Prediction

## 📌 Project Overview

This project analyses drug consumption patterns using demographic and personality-related attributes. It uses machine-learning techniques to predict alcohol consumption levels among respondents.

## 🎯 Objective

To predict alcohol consumption levels based on demographic details, personality traits, and other substance-use patterns.

## 📂 Dataset

The project uses the **Drug Consumption Dataset**, containing 1,885 respondents and 32 attributes, including:

- Age, Gender, Education, Country and Ethnicity
- Personality scores such as Nscore, Escore, Oscore, Ascore and Cscore
- Impulsivity and Sensation Seeking scores
- Alcohol and other substance consumption levels

## 🛠️ Tools and Libraries

- **Python**
- **Jupyter Notebook**
- **NumPy and Pandas**
- **Matplotlib and Seaborn**
- **Scikit-learn**

## ⚙️ Project Workflow

1. Import libraries and load the dataset.
2. Explore the dataset and understand its structure.
3. Check missing values and duplicate records.
4. Analyse outliers using boxplots and IQR.
5. Perform exploratory data analysis and visualisation.
6. Identify input features and the target variable.
7. Apply feature selection using SelectKBest.
8. Split the dataset into training and testing sets.
9. Group alcohol consumption levels into Low, Moderate and High.
10. Train and evaluate classification models.
11. Compare model performance with a baseline model.

## 🤖 Machine Learning Models

- **Extra Trees Classifier**
- **Random Forest Classifier**
- **Dummy Classifier** (Baseline Model)

## 📊 Evaluation Metrics

- Accuracy
- Balanced Accuracy
- Precision
- Recall
- F1-Score

## ▶️ How to Run

1. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

2. Keep `Drug Consumption Project.ipynb` and `drug_consumption.csv` in the same folder.
3. Open the notebook in Jupyter Notebook.
4. Run the cells to perform the analysis and model evaluation.

## 📝 Conclusion

This project explores alcohol consumption patterns and applies machine-learning classification techniques to predict consumption levels. Different models are evaluated and compared to understand their predictive performance.
