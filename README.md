

<h1># Survival-Prediction-Using-Logistic-Regression </h1>



<h2>Description</h2>
This project focuses on the famous Titanic dataset to predict passenger survival using a Logistic Regression model. It goes through the key stages of data preprocessing, model training, and evaluation.As this dataset is a great starting point for learning about classification problems and working with real world complex data.
 <br />
 
<h2>Project Goal</h2>
  
The aim is to predict whether a passenger survived or not using : (Survived: 1 = Yes, 0 = No) based on features like their age, sex, fare, class, and point of pick up.

<h2>🔍Steps followed in order to acheive this: </h2>
  
The project follows these steps:  

</b> 1️⃣. Data Cleaning & Preprocessing

- Converted the categorical values such as (Sex, Embarked) into a numerical format

- Filled the missing age values using the median

- Removed the irrelevant features such as (Name, Ticket, Cabin, etc.)

2️⃣. Visualisation

- Plotted the distribution of survivors using Seaborn to understand the class imbalance.

3️⃣. Feature Selection

- Selected the relevant features that may influence survival (e.g. Pclass, Age, Sex, etc.)

4️⃣. Model Training

- Used Logistic Regression for binary classification

- Splitting the data into training and testing sets using train_test_split

5️⃣. Evaluation
</b>
- Evaluated the model using Accuracy and a Classification Report (which includes precision, recall, and F1-score) </b> 
<h2>🔍Output Example: </h2>
</b>  Accuracy: displays how many predictions were correct out of all predictions
   
   Classification Report: provides a more detailed breakdown of the model performance across the different classes
  </b> 



<h2>Languages used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b>
<b>Libraries: pandas, scikit-learn, matplotlib, seaborn</b>

<h2>Program walk-through:</h2>

<p align="center">
Distribution of Survival on Titanic: <br/>
<img src="https://i.imgur.com/CaNgDa7.png"/>
<br />
