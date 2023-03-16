# Language-Detection-with-Machine-Learning
The goal of this project is to build a machine learning model that can detect the language of a given text. The model is trained on a dataset of texts in different languages and is then used to predict the language of new texts.

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


