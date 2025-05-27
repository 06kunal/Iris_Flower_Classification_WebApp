# Iris Flower Classification WebApp

## Overview
This project is a web application for classifying iris flowers using machine learning models. The application is built using Flask and deployed on Render. The classification is based on the famous Iris dataset.

## Features
- Uses three machine learning models:
  - Logistic Regression
  - Decision Tree
  - K-Nearest Neighbors (KNN)
- Implements Flask to create a web-based user interface.
- Hosted on Render for easy access.

## Dataset
The model is trained on the **Iris dataset**, which consists of features such as:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Project Structure
```
Iris_Flower_Classification_WebApp/
│-- static/
│   ├── IMG/  # Images used in the web application
│-- templates/
│   ├── index.html  # HTML file for the web interface
│-- Iris_Classification.ipynb  # Jupyter Notebook for model training
│-- deploy.py  # Flask application script
│-- requirements.txt  # List of dependencies
│-- saved_model.pkl  # Trained machine learning model
│-- scaler.save  # StandardScaler object for data normalization
│-- README.md  # Project documentation
```

## Installation & Setup
### Prerequisites
Ensure you have Python installed (preferably 3.9 or later). Install dependencies using:
```
pip install -r requirements.txt
```

### Running the WebApp Locally
1. Navigate to the project directory.
2. Run the Flask application:
   ```
   python deploy.py
   ```
3. Open your browser and go to `http://localhost:8080/`.

## Deployment
The application is deployed using **Render**. Follow these steps to deploy:
1. Push your project to GitHub.
2. Create a new **Render Web Service**.
3. Connect your GitHub repository.
4. Set the build command and environment variables as needed.
5. Deploy and access your web application.

## Author
Developed by Kunal Garg.

### Deployed Link: https://iris-webapp.onrender.com

## License
This project is open-source and available under the MIT License.

