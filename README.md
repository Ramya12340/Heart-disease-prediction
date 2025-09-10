# Heart-disease-prediction

Tech Stack: Python 3.8.5
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
Frameworks/Tools: Jupyter Notebook, Streamlit (for deployment).

Heart disease remains one of the leading causes of death globally. Early detection and risk prediction can help in preventing severe health issues. Doctors often rely on medical test results, but analyzing multiple risk factors at once is challenging.This project aims to assist healthcare professionals and patients by predicting the likelihood of heart disease using machine learning models.

Existing Work

Heart disease prediction has been a major focus in medical data mining and machine learning due to the large amount of patient data available. Traditionally, prediction models were based on statistical techniques like regression analysis. More recent approaches involve:

Machine learning algorithms (Decision Trees, Random Forest, SVM, Neural Networks)
Data mining methods to analyze patient health attributes
Clinical decision support systems that help doctors assess risks
While previous models achieved reasonable accuracy, challenges remain in balancing interpretability, accuracy, and computational efficiency.

Proposed Work

This project proposes a machine learning-based system to predict whether a patient is at risk of heart disease based on health attributes.
The dataset used is the UCI Heart Disease Dataset.
Data is preprocessed and analyzed for feature correlations.
Multiple ML algorithms are trained and compared to identify the most effective model.
Results show that Random Forest provided the best performance in terms of accuracy and generalization.
A simple Streamlit web app was built, allowing users to input medical parameters and get a risk prediction instantly.

Results

Random Forest achieved the highest accuracy among tested models.
Visualizations (heatmaps, bar charts, accuracy comparison graphs) highlight the importance of features like cholesterol, age, resting blood pressure, and maximum heart rate.
