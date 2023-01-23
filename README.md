# Kaggle-House Prices Prediction

## Description
This project stemmed from the 
[House Prices Prediction competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) 
in Kaggle

**Goal:** Given the training data of 1,500 houses with 72 features and their prices, predict the house prices in the test data with **lowest possible root mean square error**.

## How I approach the problem
1. **Understand the data**
	- Visualize the relationships between features and prices
	- Understand which features affect house prices more than others
2. **Preprocess the data**
	- Fill in missing values in the data
	- Use one-hot encoding for non-numerical features
	- Normalize numerical features
3. **Build and train the model**
	- Start with shallow model
	- Increase the depths of the model for better optimization
	- Use validation data for generalization purpose
	- Visualize the training process by plotting graphs on metrics
4. **Evaluate the model**
	- Ensure the generalization ability of the model
5. **Make Predictions**
	- Take the test data as the input and output the predictions
	- Output predictions to a CSV file

## How to Install and Run the project

### 1. Install Jupyter Notebook

```shell
pip install notebook
```
As an alternative, you could also use [Anaconda](https://www.anaconda.com/)
as it automatically install useful data science/machine learning packages for you. 

### 2. Install Required Python Modules

```shell
pip install -r requirements.txt
```

### 3. Clone the repository

### 4. Run every cell in the "House-prices.ipynb"

## Helpful Links
It is always useful to look up API references:
[Numpy](https://numpy.org/doc/stable/reference/index.html)
[Matplotlib](https://matplotlib.org/stable/api/index.html)
[Pandas](https://pandas.pydata.org/docs/reference/index.html)
[Tensorflow](https://www.tensorflow.org/api_docs)
[Keras](https://keras.io/api/)

Also, don't forget your best friend: [Google](https://www.google.com/) \

[ChatGPT](https://openai.com/blog/chatgpt/) is also a option, but be careful to inspect what it answers.

## License

[MIT](https://choosealicense.com/licenses/mit/)