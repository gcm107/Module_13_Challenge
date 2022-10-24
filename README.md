# Module_13_Challenge
Neural Networks

## Overview
We created a binary classifier model that predicts whether applicants will be successful if funded by Alphabet Soup. We then tried to optimize the model two more times, and saved each model. 

---

## Usage
* We will run this notebook in Google Colab. Upload the GC_venture_funding_with_deep_learning.ipynb to colab to begin. 

* The data used to train the model is located in the 'Resources' folder. 
    > Resources/applicants_data.csv


_Here are the steps we followed in this notebook._

1. Prepare the data for use on a neural network model.

2. Compile and evaluate a binary classification model using a neural network.

3. Optimize the neural network model.

---

## Technologies
The first cell of this notebiook will install and run the libraries and packages. See below:
```
import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.layers import LSTM, Dropout 
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```


---

## Contributors

G. Cale McDowell



[@gcm107](https://github.com/gcm107)

---

## License

