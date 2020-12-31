<img src="pic/K nearest neighbours.JPG" width="500px"> 
<strong>The K-Nearest Neighbors algorithm is a classification algorithm that takes a bunch of labeled points and uses them to learn how to label other points.This algorithm classifies cases based on their similarity to other cases.</strong><br><br> 
Here, k means number of neighbors we need to consider.
<br><br><br>



# calculting distance from neighbours:
<img src="pic/K nearest neighbours.JPG" width="1000px"> 


<br><br><br>

# to select best value of k:
<br>Here, k means number of neighbors we need to consider.<br>
start from k=1 <br>
and measure the accuracy<br>
now k=2<br>
and measure the accuracy<br> . . . . . . 
by this find the best accuracy and value of k



<br><br><br>

<a href="https://www.geeksforgeeks.org/k-nearest-neighbours/">watch this website to know more</a>

<br><br><br>



# Evaluation Metrics in Classification:
let's imagine that we have an historical dataset which shows the customer churn for a telecommunication company.
So, We have trained the model, and now we want to calculate its accuracy using the test set. We pass the test set to our model, and we find the predicted labels. Now the question is,
<br>
“How accurate is this model?”
<br>
Basically, we compare the actual values in the test set with the values predicted by the model, to calculate the accuracy of the model.
<br>    

## There are different model evaluation metrics but we just talk about three of them:
 1.Jaccard index,
 2.F1-score,
 3.Log Loss