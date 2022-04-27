## Project Title
### Machine Learning Bootcamp
It is a project where I had to make a Machine Learning library consisting of all the basic algorithms.
## Motivation for the project
My motivation for the project was to understand the concept behind the working of basic ML algorithms.I have implemented various Machine Learning algorithms from scratch in my project. It helped me understand the working principle behind these algorithms better when I coded it from scratch rather than using libraries for that purpose.I have made classes for each algorithm containing all the necessary functions inside it.
## Features
I have implemented the following algorithms:
#### Linear Regression
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20.png)
The above is my screenshot of the hyperparameters I used and the cost plot obtained for linear regression.
#### Polynomial Regression
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(1).png)
The above is for polynomial regression.
#### Logistic Regression
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(3).png)
The above visual shows the working of my one-vs-all type logistic regression classifier on the EMNIST data provided for my project. I have trained and tested the model only for the alphabet A. I have made a loop where we can specify the number of alphabets we want to train and test on.
#### KNN
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(4).png)
The above is te screenshot of the training and testing on EMNIST Data for my KNN model. I have used K as 1 because the model takes too long to run for higher values of K due to the size of the data provided
#### KMeans Clustering
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(5).png)
The above shows the working of the KMeans algorithm where the distances between the updated and original centroids are printed out and we can see that the distances are reducing with each iteration. I wasn't able to visualize the clusters due to the large amount of data points.
#### Neural Networks
##### Classification
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(6).png)
The above shows the accuracy and working of my neural networks classifier. I have also added a function to visualize the accuracy plot.
##### Linear Regression
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(7).png)
The above shows the rmse and working of my neural networks linear regressor. I have also added a function to visualize the cost plot.
##### Polynomial Regression
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(8).png)
The above shows the rmse and working of my neural networks polynomial regressor. I have also added a function to visualize the cost plot.
##### Support Vector Machine
![alt text](https://github.com/Thiruloksundar/thirurep1/blob/main/2022-04-20%20(9).png)
The above shows my SVM Classifier trained on the EMNIST data but due to large size of data I couldn't run the predict function properly to obtain the accuracy of my classifier. I will improve this code in the next commit.
## Technologies/libraries Used
NumPy                                                                                                                                                                   
Pandas                                                                                                                                                                 
Matplotlib (for visualization)
## Build Status
I have completed these algorithms successfully with a good accuracy. The performance of the models can be improved by further tuning the hyperparameters. The data provided was a large one so the training takes some amount of time and the size of the dataset also influenced the performance of the models.
## License
[MIT](https://choosealicense.com/licenses/mit/)
