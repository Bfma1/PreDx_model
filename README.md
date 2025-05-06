# Preeclampsia_app Overview
The Preeclampsia Prediction App is a machine learning-based tool developed to predict the risk of preeclampsia in pregnant individuals. By utilizing clinical and laboratory data, this app leverages an ensemble model to provide accurate predictions, helping healthcare professionals with early detection and intervention.

# Features 
-Risk Prediction: The app predicts the likelihood of preeclampsia based on input data such as clinical and laboratory features.

-Ensemble Machine Learning Models: Combines XGBoost, logistic regression, and neural networks to enhance prediction accuracy.

-User-Friendly Interface: A simple and intuitive interface for easy data entry and result interpretation.

# Technologies
-Python: The app is developed in Python, utilizing popular libraries for machine learning and data processing.

-Flask/Django (optional depending on implementation): For creating the web-based user interface.

-Pandas, Numpy: Data handling and manipulation.

-Scikit-learn: For implementing machine learning models, including logistic regression.

-XGBoost: For implementing the XGBoost model.

-Keras/TensorFlow: For building and running neural network models.

Matplotlib/Seaborn: Data visualization.


# Dataset
-Younsi Hospital, Korea: The primary dataset used for training and testing the models.

-King Abdullah University Hospital: A merged dataset containing clinical and laboratory data, although the raw dataset cannot be shared due to privacy and confidentiality restrictions.

# Installation
-Clone the repository:

bash

``
git clone https://github.com/Bfma1/Preeclampsia_app.git
``
-Navigate to the project directory:

bash
``
cd Preeclampsia_app
``

-Install required dependencies:

bash
``
pip install -r requirements.txt
``

-Run the application:

bash
``
python app.py

``

# Usage
-Start the app by running the app.py script.

-Input clinical and laboratory data when prompted.

-The app will provide a preeclampsia risk prediction based on the entered information.








