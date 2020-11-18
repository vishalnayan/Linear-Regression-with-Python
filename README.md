### Linear Regression

Linear Regression is an important topic in Machine learning, although its very prominent concept of statictics, and is widely used for many practical reasons in Data science and ML. 
Some imporant point regardin linear regression are; 

- Linear approach to modelling the relationship between a scalar response or dependent variable (denoted by y), and one or more explantory variables (independent variable) denoted by X.
- Model is based on the equation of a ***straight line***, y=a+bx, where a is the y-intercept (the value of y when x=0) and b is the slope (the degree to which y increases as x increases one unit).
- The word ***‘regression’*** was used to Sir Francis Galton to describe the relationship between heights of parents and their children. Tall parents tend to have tall children, but shorter than themselves while short parents tend to have short children, but taller than themselves. He called this ‘regression towards mediocrity’. This is known as the ***‘regression effect’***.
- The strange thing is that we can exchange the words ‘parents’ and ‘children’ so, for example, tall children tend to have shorter parents and tall parents tend to have shorter children.
- The case of one explanatory variable is known as **Simple linear regression**.
- For more than one explanatory variable, the process is called **Multiple linear regression**.
- In linear regression, the relationhips are modelled using linear predictor function, whose unknown models parameter are estimated based on the data. Such models are called **Linear model**
- It's wideldy used in many practical applications is because models which depend linearly on their unknown parameters are easier to fit than models which are non-linearly related to their parameters.


### Practical Scenarios
- If the goal is error reduction, forecasting, prediction, linear regression can be used to fit a predictive model to an observed dataset of values of the response and explantory variable.
- If the goal is to explain variation in the response variable that can be attributed to variation in the explanatory variables.

### Gradient Descent Algorithm
- Gradient descent algorithm is an optimization algorithm used to find the values of parameters(coefficient) of a function (f) that minimizes the cost function(cost).
- Used to finding a local minimum of a differentiable function.
- To find a local minimum of a function using gradient descent, we take steps proportional to the negative of the gradient (or approximate gradient) of the function at the current point. But if we instead take steps proportional to the positive of the gradient, we approach a local maximum of that function; the procedure is then known as gradient ascent. 
- GD algorithm is best used in the scenarios when the parameters cannot be calculated analytically(i.e. using linear algebra), and must be searched by a optimization algorithm.
- Common examples of algorithms with coefficients that can be optimized using gradient descent are Linear Regression and Logistic Regression.
- Every ML algorithm has an optimization algorithm at its core, and Gradient descent algorithem is a simple algorithm which you can use it with any ML algo.
- GD algorithm can be used with algorithms like linear regression.
- GD algorithm scales to a very large datasets.

### Step to calculate Gradient Descent 
- Get the initial values for the coefficient or coefficients for the function. This could be 0 or some random value,i.e. coefficient = 0.0
- Calculate the cost of coefficients by plugging them into the function and calculating the cost,i.e. cost = f(coefficient)
- Derivative of the cost is calculated. The derivative is a concept from calculus and refers to the slope of the function at a given point. We need to know the slope so that we know the direction (sign) to move the coefficient values in order to get a lower cost on the next iteration,i.e. delta = derivative(cost)
- Now since we know from the derivative which direction is the downhill,i.e. low cost, we can update the coefficient values. A learning rate parameter (alpha) must be specified that controls how much the coefficients can change on each update,i.e. coefficient = coefficient – (alpha * delta)
- This process is repeated until the cost of coefficients is 0 or near 0 value.





### Project
- Create a linear regression model, and fit it to given data using Gradient descent algorithm.


### References
https://en.wikipedia.org/wiki/Gradient_descent

https://en.wikipedia.org/wiki/Linear_regression

https://machinelearningmastery.com/gradient-descent-for-machine-learning/



