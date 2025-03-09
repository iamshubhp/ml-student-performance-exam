# Student Exam Performance Indicator

## Project Overview
This project is a web application built using Flask that predicts students' math scores based on various input features such as gender, race/ethnicity, parental education level, lunch type, test preparation course status, reading score, and writing score. The dataset used for training the model is sourced from Kaggle: [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).

## Features
- **Web Interface**: Users can input student details through a web form.
- **Machine Learning Model**: The application uses a trained machine learning model to predict students' math scores.
- **Data Preprocessing**: Features are preprocessed using a standard scaler to normalize input values.
- **Model Deployment**: A trained model is saved and loaded dynamically for making predictions.
- **Flask Backend**: The backend is implemented in Flask, handling user input, preprocessing, and prediction.

## How It Works
1. The user provides input through a web form.
2. The `CustomData` class converts the input into a DataFrame.
3. The `PredictPipeline` class loads the trained model and preprocessor.
4. The input data is preprocessed and passed to the model for prediction.
5. The predicted math score is displayed on the web page.

## Technologies Used
- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- Matplotlib
- Seaborn

## Dataset
The dataset consists of student performance records, including demographic details and exam scores. The model is trained to predict the math score based on these features.

## Future Improvements that i would do if i can
- Enhance the UI for better user experience.
- Deploy the model using cloud services.
- Add more features to improve prediction accuracy.

## Tutorial is attached below for the project!



https://github.com/user-attachments/assets/cec61ca8-d1bc-4d40-b1e3-ab16f412d7f0



