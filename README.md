# Kaggle-House Prices Prediction

## Description
This project stemmed from the 
[House Prices Prediction competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) 
in Kaggle

**Goal:** Given the training data of 1,500 houses with 72 features and their prices, predict the house prices in the test data with **lowest possible root mean square error**.

## How I approach the problem
1. **Understand the data**
	- One for **predicting the actions** of the lunar lander
	- The other for **setting the target actions**
2. **Preprocess the data**
3. **Build and train the model**
	- Number of episodes: Maximum epochs the environment should reset for training.
	- Number of time steps: Maximum number of actions the lunar lander takes in a single epoch
	- Epsilon: A parameter to **balance exploration and exploitation**
	- TAU: A soft update parameter for the Q network.
	- You can find more hyperparameters in the source code
4. **Evaluate the model**
	- The model is trained by updating weights in both Q networks
	- As the model is trained, the average reward in one environment gets higher.
5. **Make Predictions**

## How to Install and Run the project

### 1. [Install Jupyter Notebook]()

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

Also, don't forget [Google](https://www.google.com/)\
[ChatGPT](https://openai.com/blog/chatgpt/) is also a option, but be careful to inspect what it answers.

## License

[MIT](https://choosealicense.com/licenses/mit/)