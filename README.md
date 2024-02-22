
# Oasis Info Byte  Internship - Data Science Internship Projects

Welcome to the OIBSIP (Online Internship Projects) repository! This repository contains the projects completed during my Data Science internship at Oasis Info Byte. I was assigned different tasks  each with its own set of projects to complete.




# TASKS

- Task 1 : IRIS FLOWER CLASSIFICATION

- Task 2 : CAR PRICE PREICTION WITH MACHINE LEARNING 

- Task 3 : EMAIL SPAM DETECTION WITH MACHINE LEARNING



# Task 1

### IRIS FLOWER CLASSIFICATION

The Iris Flower Classification project is a machine learning application designed to classify iris flowers into one of three species (setosa, versicolor, or virginica) based on the size of their sepals and petals. This project is part of an internship program and showcases the use of various machine learning algorithms to solve a classification problem.



![iris img1](https://github.com/ShubhamKumbhar28/OIBSIP/assets/133940544/15231480-8e25-4eda-b751-ddfcf40de9b0)



### Dataset

The dataset used in this project is the famous Iris Flower Dataset, which includes 150 samples with four features each: the length and the width of the sepals and petals, in centimeters, for each flower. The dataset is split into a training set and a testing set to evaluate the performance of the model.

link : https://www.kaggle.com/datasets/saurabh00007/iriscsv



### Features


- Four features: sepal length, sepal width, petal length, and petal width.

- Target classes: Iris setosa, Iris versicolor, Iris virginica.

### Machine Learning Model

This project uses the  Logistic Regression to train the model. The choice of algorithm(s) is based on their suitability for handling small datasets with high accuracy.


###  Requirements

List all the libraries and tools required to run your project. For example:

- Python >= 3.6
- scikit-learn
- numpy
- pandas
- matplotlib / seaborn (for data visualization)

# Task 2

### CAR PRICE PREICTION WITH MACHINE LEARNING

The Car Price Prediction project is a machine learning model designed to predict the selling price of cars. This model takes into account various features such as the car's brand and model, its age, original price, mileage, fuel type, selling type (e.g., dealer or individual), transmission type, and the number of previous owners. This project aims to provide valuable insights for both sellers and buyers in the used car market, helping them to make informed decisions.

![cars](https://github.com/ShubhamKumbhar28/OIBSIP/assets/133940544/b524dbee-f897-4cc8-b1aa-a2550f5da34b)

### Dataset 

The dataset for this project comprises several attributes for each car listing:

- Car_Name: The name of the car

- Year: The year of manufacture

- Selling_Price: The price the owner wants to sell the car at (this is the target variable)

- Present_Price: The current ex-showroom price of the car

- Driven_kms: Number of kilometers the car has been driven

- Fuel_Type: The type of fuel used by the car (Petrol/Diesel/Electric/CNG)

- Selling_type: The type of seller (Dealer/Individual)

- Transmission: The type of transmission (Manual/Automatic)

- Owner: The number of previous owners

link : https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars


### Features and Target Variable

- Features: Car_Name, Year, Present_Price, Driven_kms, Fuel_Type, Selling_type, Transmission, Owner

- Target Variable: Selling_Price

### Machine Learning Model

This project uses the Linear Regression to train the model. We can  choice different algorithm(s)  based on their suitability.


# Task 3

### Email Spam Detection with Machine Learning

This project focuses on the development of a machine learning model capable of accurately identifying spam emails. Utilizing a dataset of email messages that have been labeled as either ham or spam, the model learns to distinguish between these two categories. This project aims to enhance email filtering techniques and provide a reliable tool for maintaining the integrity of inboxes by minimizing unwanted messages.

![email](https://github.com/ShubhamKumbhar28/OIBSIP/assets/133940544/90c02d4e-69d5-49ca-8be1-f7627677a86e)

### Dataset

The dataset used in this project consists of email messages with the following attributes:

- Email Text (v2) : The body text of the email.
- Label (v1) : Whether the email is ham or spam 

link : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

### Machine Learning Model
This project employs GaussianNB ,BernoulliNB ,MultinomialNB
for spam detection. The text data is preprocessed and transformed into a suitable format (e.g., TF-IDF vectors) for model training.

### Requirements

List the libraries and their versions required to run the project

- Python >= 3.7
- NumPy
- Pandas
- scikit-learn
- matplotlib / seaborn (for data visualization)
- NLTK (for text preprocessing)



# Conclusion

These projects provided valuable hands-on experience and helped me enhance my skills. Each project presented unique challenges and opportunities for growth. I am grateful for the learning experience and the chance to contribute to real-world Data Science projects.
