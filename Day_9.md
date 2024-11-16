# concept of gadient
 The gradient refers to the vector of partial derivatives of a function with respect to its input parameters. It represents the rate of change of the function as you make small changes to the input variables. Gradients are central to the optimization process used in many machine learning algorithms, particularly in gradient-based optimization methods like gradient descent.

 * The function we want to optimize is usually a loss function (or cost function). The goal is often to minimize this loss function, which quantifies the error of the model's predictions compared to the true values.

Loss Function: A function 
L(θ) where 
θ represents the parameters of the model (e.g., weights in a neural network, coefficients in linear regression), and the function returns a scalar value indicating how well the model fits the data. Common loss functions include:
Mean Squared Error (MSE): For regression problems.
Cross-Entropy Loss: For classification problems.
The gradient of the loss function with respect to the model parameters tells us how to adjust the parameters to minimize the loss.
