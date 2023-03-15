# Language-Detection-with-Machine-Learning
This project aims to detect the language of a given text using machine learning techniques. The system is able to classify text into one of several languages, such as English, Spanish, French, German, Portuguese, and so on.

The most important part of training a language detection model is data. The more data you have about every language, the more accurate your model will perform in real-time. The dataset that I am using is collected from Kaggle, which contains data about 22 popular languages and contains 1000 sentences in each of the languages, so it will be an appropriate dataset for training a language detection model with machine learning.

# Prerequisites
<h3>To run this project, you will need the following:<br></h3>

Python 3.x<br>
Jupyter Notebook<br>
scikit-learn library<br>
pandas library<br>
numpy library<br>


# How did I do?

<h3>Let’s start the task of language detection with machine learning by importing the necessary Python libraries and the dataset:<br></h3>
import pandas as pd<br>
import numpy as np<br>
data = pd.read_csv('dataset.csv')<br>
data.head()<br>

![result](https://github.com/Sanketarali/Language-Detection-with-Machine-Learning/blob/main/1.png)<br>

  <h3>Now let’s have a look at all the languages present in this dataset:<br></h3>

data["language"].value_counts()<br>

![result](https://github.com/Sanketarali/Language-Detection-with-Machine-Learning/blob/main/2.png)<br>

# Language Detection Model
![result](https://github.com/Sanketarali/Language-Detection-with-Machine-Learning/blob/main/3.png)<br>

  <h3>Now let’s use this model to detect the language of a text by taking a user input:<br></h3>
![result](https://github.com/Sanketarali/Language-Detection-with-Machine-Learning/blob/main/4.png)<br>

<h3>So as you can see that the model performs well. One thing to note here is that this model can only detect the languages mentioned in the dataset.</h3>

![result](https://github.com/Sanketarali/Language-Detection-with-Machine-Learning/blob/main/Screenshot%20(3012).png)


