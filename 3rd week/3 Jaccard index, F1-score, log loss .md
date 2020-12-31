 # 1.Jaccard index: (Jaccard index -- also known as the Jaccard similarity coefficient.)
 it's a statistic used in understanding the similarities between sample sets.
<br>
 <img src="pic/jaccard index.JPG" width="1000px"> 
<br><br>
<br><br>

# F1-score , confusion matrix:  ( best classifire)
<br>
## the F-score or F-measure is a measure of a test's accuracy<br><br>
It is calculated from the precision and recall of the test, where the precision is the number of correctly identified positive results divided by the number of all positive results, including those not identified correctly, and the recall is the number of correctly identified positive results divided by the number of all samples that should have been identified as positive.
<br><br>
<a href="https://www.youtube.com/watch?v=XwMlUv7OSJw">watch this video for confusion matrix</a>
<a href="https://www.youtube.com/watch?v=CYy0TZ6OIDw">watch this video2 for confusion matrix</a>
<br>

## 4 out coms of binary clssification:
<img src="pic/4 out comes of binary classification.JPG" width="1000px"> <br>
<br>

##  confiusion matrix equ:
<img src="pic/confiusion matrix equ.JPG" width="1000px"> 
<img src="pic/summary of confiusion matrix equ.JPG" width="1000px"> 
<br><br><br><br>

# log loss:
### Log Loss is the most important classification metric based on probabilities.

<img src="pic/log loss equ.JPG" width="1000px"> 
<br> <br>

### Example:
A model predicts probabilities of [0.8, 0.4, 0.1] for three houses. The first two houses were sold, and the last one was not sold. So the actual outcomes could be represented numeically as [1, 1, 0].
<br>
Let's step through these predictions one at a time to iteratively calculate the likelihood function.
<br>
The first house sold, and the model said that was 80% likely. So, the likelihood function after looking at one prediction is 0.8.
<br>
The second house sold, and the model said that was 40% likely. There is a rule of probability that the probability of multiple independent events is the product of their individual probabilities. So, we get the combined likelihood from the first two predictions by multiplying their associated probabilities. That is 0.8 * 0.4, which happens to be 0.32.
<br>
Now we get to our third prediction. That home did not sell. The model said it was 10% likely to sell. That means it was 90% likely to not sell. So, the observed outcome of not selling was 90% likely according to the model. So, we multiply the previous result of 0.32 by 0.9.
<br>
We could step through all of our predictions. Each time we'd find the probability associated with the outcome that actually occurred, and we'd multiply that by the previous result. That's the likelihood.<br>




