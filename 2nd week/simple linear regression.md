### linear regression model:
<img src="pic/simple linear .JPG" width="500px"> 
We're going to predict the target value y. In our case using the independent variable engine size represented by x1. The fit line is shown traditionally as a polynomial. In a simple regression problem, a single x, the form of the model would be theta 0 plus theta 1 x1. In this equation, y hat is the dependent variable of the predicted value. And x1 is the independent variable.
<br>
Theta 0 and theta 1 are the parameters of the line that we must adjust. Theta 1 is known as the slope or gradient of the fitting line and theta 0 is known as the intercept.

<br><br>
<img src="pic/simple linear  1.JPG" width="500px"> 

<br><br>

### এখন আমাদের কাজ হল থেতা ১ এবং থেতা ২ কে খজা যা best fit line দিবে যার মাদ্ধমে আমরা error (MSE) কমাইতে পারব.. এটা হল mathmatical<br> or আরেক্তা কাজ করা যায় -> optimization approach.<br>
<br><br>

### mathmatical approch to :
<br>
<img src="pic/theta find.JPG" width="500px"> 
<br><br>

## NOW, predecting value
<img src="pic/predecting value.JPG" width="500px"> <br><br>

<br><br>

### train/ test split evaluation approach:
<br>
<img src="pic/train test evaluation.JPG" width="500px"> 
<img src="pic/error at of the model.JPG" width="500px"> 
<br><br>
<br>
Cross-validation is a resampling procedure used to evaluate machine learning models on a limited data sample. The procedure has a single parameter called k that refers to the number of groups that a given data sample is to be split into.<br>
<img src="pic/k fold cross validation.JPG" width="500px"> 
<br>

### after calculatin the acuracy for each fold <br> 
### avarage of all accuracy is the total accuracy <br> 


<br><br><br>

## Evaluation Metrics in Regression Models
A number of model evaluation metrics including <br>
1. (MAE)mean absolute error,<br>
2. (MSE)mean squared error,<br>
3. (RMSE)root mean squared error.<br>
<img src="pic/ Regression Models errors.JPG" width="500px"> 
<br>R squared is not an error per se but is a popular metric for the accuracy of your model. It represents how close the data values are to the fitted regression line. <br>

### The higher the R-squared, the better the model fits your data.<br>

### সুত্রঃ r^2 = 1- (sum_Of_all_Errors /some_of_squre_varient_of_mean<br>
## R-squared is a goodness-of-fit measure for linear regression models.