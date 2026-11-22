# House Price Prediction Using Neural Network

## About the Project

This project investigates how changing the capacity of a neural network affects underfitting and overfitting when predicting house sale prices.

I use the **House Prices - Advanced Regression Techniques** dataset from Kaggle. The experiment focuses on the relationship between a house's living area and its sale price.

## Dataset Source

- **Dataset:** House Prices - Advanced Regression Techniques
- **Platform:** Kaggle
- **Dataset page:** https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
- **File used:** `train.csv`

The `train.csv` file includes house features such as `GrLivArea` (above-ground living area) and `SalePrice` (house sale price).

## Credit and Acknowledgement

I accessed the dataset through Kaggle and used the following Kaggle notebook as a reference for this project.

**Notebook:** House Prices - Advanced Regression Techniques  

**Author:** Serkan Polat

**Notebook Link:**  

https://www.kaggle.com/code/serkanp/house-prices-advanced-regression-techniques/notebook

I would like to acknowledge Serkan Polat for sharing this notebook, which helped me explore the dataset and understand its structure.

The original dataset was prepared by Dean De Cock for educational purposes.

## How I Use the Dataset

For this project, I use:

- **Input feature (`X`):** `GrLivArea`
- **Target (`y`):** `SalePrice`

I prepare the data and split it into training, validation, and test sets. I then train neural networks with different numbers of hidden neurons to investigate model capacity. A second experiment compares different weight decay values to study regularisation.

## Tools and Libraries

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- PyTorch

## Dataset Terms

I access the dataset through Kaggle and use it for this academic project in accordance with the competition rules:

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/rules

## Reference

De Cock, D. (2011). *Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project*. Journal of Statistics Education, 19(3).

https://doi.org/10.1080/10691898.2011.11889627
