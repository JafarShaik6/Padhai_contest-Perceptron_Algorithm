# Padhai_contest-Mobile Phone Like/Unlike Classification Using Perceptron Algorithm

# Introduction:- 
  Solution for Padhai Perceptron contest on kaggle to predict whether the users like the mobile phone or not using Perceptron Algorithm.

# Data  :-  
Mobile Dataset from https://www.91mobiles.com/

# Libraries 
  Scikit-learn :- For splitting train data into train and evaluation set(train_test_split), for standardization of data(StandardScaler), 
                  for finding loss(mean_squared_error_loss) and for calculating accuracy on test and train dataset(accuracy_score).
  
  Numpy : For scientific computing.
  
  Pandas:  For Data Manipulation and Preprocessing.
  
  Matplotib,Seaborn : For Data_Visualization
  
  LightGBM : Used it to only to show Important Features in the train dataset.
  


# Task :-  
The goal is to  predict whether users like the mobile phone or not.

# Loss :-  
 Mean squared error Loss Function.
# HyperParameters:-
Learning Rate : The learning rate is perhaps the most important hyperparameter. If you have time to tune only one hyperparameter, 
                tune the learning rate.Low learning rate slows down the learning process but converges smoothly. Larger learning 
                rate speeds up the learning but may not converge.
                
Epochs :  Number of epochs is the number of times the whole training data is shown to the network while training.
          Increase the number of epochs until the validation accuracy starts decreasing even when training accuracy is increasing(overfitting).

# Evaluation Metrics :-
To find the accuracy on test and train data we use accuracy_score function from sklearn.metrics.

                    Accuracy = No.of Correct Predictions/Total no of predictions
                    
 Scored 91.5% accuracy on public leaderboard and 79% accuracy on private leaderboard
