# Breast Cancer Prediction App

This is a machine learning project that predicts breast cancer using a dataset of breast cancer diagnoses. The project includes a Jupyter Notebook file `breast-cancer.ipynb` which contains the data preparation, feature engineering, and model creation steps. The resulting model is then saved as a pickle file `model.pkl`.

This project also includes a Flask web application that allows users to input their own breast cancer data and obtain a prediction of their diagnosis. The web application is located in the `app.py` file and is supported by the `request.py` file.

## Files included in this project:

- `static/css` - folder containing the CSS file used in the web application
- `templates/index.html` - HTML file for the web application
- `data_breast-cancer-wiscons.csv` - dataset used for model training
- `model.py` - Python file containing the machine learning model
- `model.pkl` - pickle file containing the saved machine learning model
- `request.py` - Python file containing the HTTP requests for the web application
- `requirenemts.txt` - file containing the required dependencies for running the web application
- `scaler.pkl` - pickle file containing the saved scaler used for feature scaling

## Running the project:

To run the web application locally, follow these steps:
1. Clone the repository onto your machine
2. Navigate to the project directory in your terminal
3. Install the required dependencies by running `pip install -r requirements.txt`
4. Start the web application by running `python app.py`
5. Navigate to `http://localhost:5000/` in your web browser to use the application

Alternatively, the web application can be deployed to Heroku by following the instructions in the `Procfile`. 

## Conclusion:

This project demonstrates how to build a machine learning model for breast cancer prediction and deploy it as a web application using Flask. The resulting web application allows users to input their own data and obtain a prediction of their breast cancer diagnosis.

##Demo
![](https://github.com/morteza-sharifi1/breast-cancer-prediction-app/blob/eb714a948ff3f4ede1adce46770db3ad37c69d80/static/demo.jpg)
