# MT-Cars-Mileage-Prediction

This project focuses on exploratory data analysis and regression modeling using the MT-Cars dataset to predict a car’s mileage (mpg) based on its technical and design features.

Project Workflow

Data Ingestion & Libraries
Imported essential Python libraries for data ingestion, cleaning, visualization, and machine learning.
Loaded the MT-Cars dataset using the pydataset library.

Data Understanding & Cleaning
Explored the dataset structure, feature meanings, and data types.
Checked for missing values, data inconsistencies, and ensured the dataset was clean and model-ready.

Exploratory Data Analysis (EDA)
Analyzed relationships between mileage and numerical features such as engine displacement, horsepower, weight, and number of cylinders.
Used statistical summaries and visualizations to identify patterns and correlations influencing fuel efficiency.

Feature Selection
Selected relevant predictor variables based on domain understanding and correlation analysis to improve model performance and interpretability.

Train–Test Split
Split the dataset into training and testing sets to evaluate model generalization on unseen data.

Model Training
Trained regression models (e.g., Linear Regression / Tree-based models) to learn the relationship between vehicle features and mileage.

Model Prediction
Generated mileage predictions on the test dataset using the trained models.

Model Evaluation
Evaluated model performance using metrics such as R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) to assess accuracy and reliability.
