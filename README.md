Download Link: https://assignmentchef.com/product/solved-eecs658-assignment-2
<br>
Deliverables:

<ol>

 <li>Copy of Rubric2.docx with your name and ID filled out (do not submit a PDF)</li>

 <li>Python source code for CompareMLModels</li>

 <li>Screen print showing the successful execution of CompareMLModels 4. Answers to the following questions:

  <ol>

   <li>Based on accuracy which model is the best one?</li>

   <li>For each of the 6 other models, explain why you think it does not perform as well as the best one.</li>

  </ol></li>

</ol>




Assignment:

<ul>

 <li>For this assignment, we are going to compare how well different ML classifiers classify the iris dataset.</li>

 <li>Write a Python program called CompareMLModels that does the following:</li>

</ul>

o Uses 2-fold cross-validation to produce a test set of 150 samples of the iris data set with the following ML models:

<ul>

 <li>Linear regression (LinearRegression)</li>

 <li>Polynomial of degree 2 regression (LinearRegression)</li>

 <li>Polynomial of degree 3 regression (LinearRegression)</li>

 <li>Naïve Baysian (GaussianNB)</li>

 <li>kNN (KNeighborsClassifier)</li>

 <li>LDA (LinearDiscriminantAnalysis)</li>

 <li>QDA (QuadraticDiscriminantAnalysis)</li>

 <li>Remember 2-fold cross-validation involves:</li>

</ul>

<ul>

 <li>Dividing the data set into 2 folds</li>

 <li>Training the model with fold 1 Testing the model with fold 2</li>

 <li>Training the model with fold 2</li>

 <li>Testing the model with fold 1</li>

 <li>Concatenating the test results from the 2 folds to get a test set of 150 samples.</li>

 <li>For each of the 7 models the program should display (with a label before each model’s display indicating which model the results are for):

  <ul>

   <li>Confusion matrix</li>

   <li>Accuracy metric o If the values in your confusion matrices do not add up to 150, then you did something wrong.</li>

  </ul></li>

 <li>Remember: You need to convert the class from strings to integers for training the regression models. Use preprocessing.LabelEncoder() method</li>

</ul>

or do it in the code brute force. Also, remember, the results of regression need to be converted back to integers before creating the confusion matrix. There are some slides on how to do that, if you don’t remember. You also need to convert the output of the regression from float to integer.




Remember:

<ul>

 <li>Your Programming Assignments are individual-effort.</li>

 <li>You can brainstorm with other students and help them work through problems in their programs, but everyone should have their own unique assignment programs.</li>

</ul>