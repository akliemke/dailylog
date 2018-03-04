# Week 1 - Notes


## Notation of the Course

> m   = Number of training examples

> x's = "input" variable | feature

> y's = "output" variable | "target" variable

> (x, y) = Single traing example

> ![formula](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/CodeCogsEqn2.gif) = iTh training example (index of the variable)

## Cost Function

*Hypothesis* is a linear function used to make predictions of the *target's* (Price of a house, for example). 
Theta 0 and Theta 1 is the parameters of the *model*.

> Theta 0 controls the horizontal inclination of the straight line 

> Theta 1 controls the inclination of the straight line

Having a dataset for training, what we want to do is to come up with values for the parameters theta 0 and theta 1, so that straight line of the function somehow fits the data well. Like this:
![Straight Line](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/straight_line_fit.PNG)
### Cost Function Intuition  

**Hypothesis** = ![Hypothesis](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/CodeCogsEqn.gif)

**Parameters** = ![Parameters](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/theta_0_theta_1.gif)

**Cost Function** = ![Cost Function](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/costa_function.gif)

**Goal** = Minimize ![Theta0_Theta1](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/theta_0_theta_1.gif) using  ![J_Function](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/J_function.gif)


## Linear Regression and Gradient Descent




### Math Functions generate in [CodeCogs Latex Editora](https://www.codecogs.com/latex/eqneditor.php)

> **Cost Function Syntax:** J(\theta_0, \theta_1) = \frac{1}{2m} \sum_{i=1}^m(h_\theta(x^{(i)})- y^{(i)})^2 

### Bibliography