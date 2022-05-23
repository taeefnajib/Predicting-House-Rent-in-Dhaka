# **Predicting House Rent in Dhaka Using Artificial Neural Network (ANN) and PyTorch**

We have developed a Deep Learning model to predict house rent in Dhaka, the capital of Bangladesh, based on features like the location of the house, the area of the house, the number of beds and the number of baths. We used Pandas for Exploratory Data Analysis (EDA) and PyTorch for building the model.

## **Collection of Data**

The dataset used in this project to train and test the model is webscrapped from [bproperties.com](https://www.bproperty.com/)
We have scrapped `the location`, `Area in sqft`, `No of Bedrooms`, `Number of Bathrooms` and `Monthly Rent` from the following website: [https://www.bproperty.com/en/dhaka/apartments-for-rent/?load_all_prop=1](https://www.bproperty.com/en/dhaka/apartments-for-rent/?load_all_prop=1)

### **About The Dataset**

Feature Variables:

* Location
* Area
* No of Bed
* No of Bath

Target Variable:

* Rent

There are 4,13,782 Apartments in Dhaka that are listed on the website, from which we have taken 28,800 apartments.

### **Dependencies**

* Selenium
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit Learn
* PyTorch
