# UTKFace-Age-Gender-Ethnicity-Prediction
A project that processes the UTKFace dataset to predict age, gender, and ethnicity from face images using CNN and MLP models. It includes data preprocessing, exploratory analysis, model training, evaluation, and performance comparison.

This script loads and preprocesses the UTKFace dataset images, extracts labels for age, gender, and ethnicity from the filenames, and splits the data into training, validation, and test sets. It performs exploratory data analysis (EDA) with visualizations to understand class distributions and potential dataset biases.

It then defines and trains two types of models — a Convolutional Neural Network (CNN) and a Multi-Layer Perceptron (MLP) — separately for age regression, gender binary classification, and ethnicity multi-class classification tasks. Model performance is evaluated and compared using appropriate metrics (MAE for age, accuracy for gender and ethnicity). Confusion matrices are plotted for gender classification to analyze errors.

The project highlights the impact of dataset imbalances and discusses the strengths and weaknesses of CNN vs. MLP approaches on image-based demographic attribute prediction.
