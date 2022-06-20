# Capstone project - Product Drift

## Project Goal

The goal of this capstone project is to determine a rule that identifies seasonal products starting from the customers purchases. 
If the customers purchase specific products only in specific periods, these products are labelled as seasonal. Usually seasonal products are purchased massively some months in a row and in the remaining periods are not purchased or rarely purchased. [from Capstone project sheet]

## Note

The code was developed by using [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb) platform. 

## Some Details of the Files / Folder

* Capstone_Project.ipynb : It contains the pre-processing and processing part of the project

* Rule.ipynb : It uses the output produced by Capstone_Project.ipynb and provides a function that can be used to determine if a product is seasonal or not. It was created with the idea of not re-execute the model every time the company wants to understand if a product is seasonal or not

* Data folder : It contains the output of Capstone_Project.ipynb. Seasonal_product.csv contains only seasonal products instead No_seasonal_product.csv contains only no seasonal products