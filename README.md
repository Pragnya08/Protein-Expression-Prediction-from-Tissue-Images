# Protein-Expression-Prediction-from-Tissue-Images

Project Overview: 
This repository contains a comprehensive exploration and implementation of machine learning models designed to predict the level of protein expression from images of biological tissues. Using various regression and deep learning techniques, this project aims to accurately predict protein expression levels across multiple proteins in a given tissue image.

Objective: 
The primary goal is to develop predictive models that can infer the protein expression profile of different proteins within a tissue image. This project leverages image processing, feature extraction, and advanced machine learning methodologies to achieve its objectives.

Data:
The data consists of images from four different biological tissue specimens, each labeled (A1, B1, C1, D1). These images are paired with corresponding protein expression values for 38 proteins. The total dataset comprises 9,921 image spots.

Setup and Installation:
Required Python libraries include:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- PyTorch
- skimage

Repository Contents:
- Protein_Expression_Prediction.ipynb: Main notebook with all exploratory data analysis, model training, and evaluation.

Running the Project:
- Clone the repository to your local machine.
- Install all necessary libraries mentioned under Setup and Installation.
- Open and execute Protein_Expression_Prediction.ipynb in a Jupyter environment.
  
Key Findings:
- Implementation of regression models like Ordinary Least Squares and Support Vector Regression.
- Development and evaluation of a Convolutional Neural Network to predict expression levels directly from images.
- Utilization of "leave one specimen out" cross-validation to ensure robust model validation.
