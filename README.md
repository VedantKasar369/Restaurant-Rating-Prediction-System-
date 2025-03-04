# Restaurant-Rating-Prediction-System-
This project builds a machine learning model to predict restaurant ratings based on various features like Average cost for two, has table booking, has online delivery, price range.
Restaurant Rating Prediction System

Project Overview
This project builds a **Machine Learning model** to predict restaurant ratings based on various features such as **average cost, table booking availability, online delivery options, and price range**. Additionally, a "Streamlit web app" has been developed to provide an interactive interface for users to predict restaurant ratings.


 Project Structure

├── Dataset.csv                 # Raw dataset used for training the model
├── Restaurant Recommendation System.ipynb  # Jupyter Notebook with data preprocessing & model training
├── app.py                      # Streamlit web application for rating prediction
├── mlmodel.pkl                 # Trained Machine Learning model
├── Scaler.pkl                  # Standard Scaler for input preprocessing
├── requirements.txt            # List of dependencies required to run the project
└── README.md                   # Project documentation


Features
- Data preprocessing (handling missing values, encoding categorical variables, feature scaling)
- Model training using regression algorithms (Linear Regression, Decision Tree, etc.)
- Model evaluation using Mean Squared Error (MSE) & R-Squared (R²)
- Deployment-ready "Streamlit Web App"
- Interactive UI for rating predictions based on user input

 Installation & Setup
 1. Clone the repository

git clone [https://github.com/VedantKasar369/Restaurant-Rating-Prediction-System-.git](https://github.com/VedantKasar369/Restaurant-Rating-Prediction-System-.git)
cd restaurant-rating-prediction

 2. Run the Streamlit Web App

streamlit run app.py

The app will open in your browser, allowing you to input restaurant details and predict ratings interactively.

 Model Training & Evaluation
The model was trained in "Jupyter Notebook" using:
- Data Preprocessing: Handling missing values, encoding categorical variables, feature scaling.
- Algorithms Tested: Linear Regression, Decision Tree Regressor.
- Evaluation Metrics: Mean Squared Error (MSE) and R-Squared (R²).
- Best Performing Model: Decision Tree Regressor was chosen for deployment based on evaluation.

Usage
Using the Jupyter Notebook
1. Open `Restaurant Recommendation System.ipynb`
2. Run all cells to preprocess the dataset and train the model.
3. Save the trained model (`mlmodel.pkl`) for use in the web app.

Using the Web App
1. Enter restaurant details (e.g., average cost, booking status, delivery status, price range).
2. Click the "Predict the review!" button.
3. The app will return the predicted rating category (**Poor, Average, Good, Very Good, Excellent**).

Future Enhancements
- Improve feature selection using correlation analysis
- Train advanced models like RandomForestRegressor, XGBoost
- Deploy the app on cloud platforms like Heroku or AWS

 Contributing
Feel free to contribute to this project by creating pull requests or reporting issues.
