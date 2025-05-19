# END-TO-END-DATA-SCIENCE-PROJECT

**COMPANY:-** CODTECH IT SOLUTIONS

**NAME:-** LOKANATH SATAPATHY

**INTERN ID:-** CT12WTOK

**DOMAIN:-** DATA SCIENCE

**DURATION:-** 12 NEEEKS

**MENTOR:-** NEELA SANTOSH


### **Iris Flower Species Classification Project**

#### **Project Overview**
The Iris Flower Species Classification project aims to develop a machine learning model that can accurately predict the species of an Iris flower based on its physical characteristics. The model utilizes four key features: Sepal Length, Sepal Width, Petal Length, and Petal Width. The three species to be classified are Iris Setosa, Iris Versicolor, and Iris Virginica.

#### **Key Objectives**
- **Data Analysis**: Understand the Iris dataset and its features.
- **Model Training**: Implement a classification model using Logistic Regression.
- **Web Application**: Create a user-friendly web interface using Flask to allow users to input flower measurements and receive predictions.
- **Deployment**: Host the application on a cloud platform for public access.( Sorry for this i would not able to host this application due to python version error But still i will trying to Host.)

#### **Project Structure**
The project is organized into a clear directory structure, which includes:
- **templates/**: Contains HTML files for the web interface.
- **model/**: Contains the trained model and the script for training the model.
- **app.py**: The main Flask application file.
- **requirements.txt**: Lists the necessary Python packages.
- **Procfile**: Used for deployment configuration.

#### **Technical Details**
1. **Data Preparation**:
   - The Iris dataset is loaded using `sklearn.datasets`.
   - The dataset is split into training and testing sets to evaluate model performance.

2. **Model Training**:
   - A Logistic Regression model is trained on the training dataset.
   - The model's accuracy is evaluated on both training and testing datasets, achieving approximately 97% accuracy.

3. **Flask Web Application**:
   - The application allows users to input flower measurements through a web form.
   - Upon submission, the model predicts the species and displays the result on the web page.
   - The interface is designed to be visually appealing, with color-coded species indicators.

4. **Deployment**:
   - The application is deployed on PythonAnywhere, making it accessible via a public URL.
   - The deployment process includes uploading project files and configuring the web app settings.

#### **User  Interface**
The web interface is designed to be intuitive and user-friendly. Users can input the required measurements, and upon submission, they receive a prediction along with a visual representation of the predicted species.

#### **Sample Test Cases**
- **Case 1 (Setosa)**:
  - Input: Sepal Length: 5.1, Sepal Width: 3.5, Petal Length: 1.4, Petal Width: 0.2
  - Expected Prediction: Iris-setosa

- **Case 2 (Virginica)**:
  - Input: Sepal Length: 6.7, Sepal Width: 3.0, Petal Length: 5.2, Petal Width: 2.3
  - Expected Prediction: Iris-virginica

#### **Conclusion**
This project not only demonstrates the ability to build a machine learning model but also showcases skills in web development and deployment. It serves as a comprehensive example of how to take a data science project from conception to a live application, making it an impressive addition to any portfolio.
