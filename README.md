Download Link: https://assignmentchef.com/product/solved-cpe695-homework1-applied-machine-learning
<br>



<strong>Please answer the following questions related to Machine Learning concepts: </strong>

<ol>

 <li>[<em>18 points</em>] Explain the following concepts:

  <ul>

   <li>supervised learning,</li>

   <li>unsupervised learning,</li>

   <li>online learning,</li>

   <li>batch learning, 5) model-based learning,  6) instance-based learning.</li>

  </ul></li>

</ol>




<ol start="2">

 <li>[<em>6 points</em>] What is <em>overfitting</em> of training data? What is <em>regularization</em>?</li>

 <li>[<em>6</em> <em>points</em>] Prove Bayes’ Theorem.</li>

</ol>




<strong>Programming Problem: </strong>




<ol start="4">

 <li>[40 <em>points</em>] In this problem, we write a program to find the coefficients for a linear regression model. You need to use Python to implement the following methods of finding the coefficients:

  <ul>

   <li>Normal equation, and</li>

   <li>Gradient descent (batch or stochastic mode)

    <ol>

     <li>Print the cost function vs. iterations</li>

     <li>Discuss how you choose the right alpha (learning rate). For example, you can plot cost function vs. learning rate to determine the best learning rate.</li>

    </ol></li>

  </ul></li>

</ol>

A simulated dataset will be provided, you job is to find the coefficients that can accurately estimate the true coefficients. Your solution should be 2 for intercept and 3, 4, 5 for the three coefficients.




Please do NOT use the fit() function of the Scikit-Learn library in your program. (You need to implement the Gradient Descent algorithm in your code.)




Simulated data is given as follows in Python:

import numpy as np x1 = 2 * np.random.rand(100, 1) x2 = 2 * np.random.rand(100, 1) x3 = 2 * np.random.rand(100, 1) y = 3 * x1 + 4 * x2 + 5 * x3 + np.random.randn(100, 1) + 2