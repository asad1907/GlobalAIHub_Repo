# **Global AI Hub Repository**

Global AI Hub Student Repository includes Homeworks and a Final Project related with Machine Learning 

<img src = "Images/logo.png">

**Course Date: 25.04.2021** <br>
**Name: Asad** <br>
**Surname: Asadzade** <br>
**Email: asadasadzade95@gmail.com** <br>



<h2> Final Project </h2>

In this project, Objetive is to building a model for predicting wine qualities. Our label is quality column. This is a Classification problem. I have applied three ML algorithms (DecisionTreeClassifier, RandomForestClassifier, GradientBoostingClassifier) on the dataset after some preprocessing steps.



<h2>Requirements</h2>

```python
import numpy as np 
import pandas as pd
import seaborn as sns 
import matplotlib.pyplot as plt
from sklearn.ensemble import IsolationForest
from sklearn.preprocessing import StandardScaler, MinMaxScaler 
from sklearn.model_selection import train_test_split
from sklearn.model_selection import  GridSearchCV
from sklearn.metrics import confusion_matrix, accuracy_score,precision_score, recall_score, f1_score, classification_report
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import GradientBoostingClassifier
```
