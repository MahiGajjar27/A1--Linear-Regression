# A1--Linear-Regression

Github: https://github.com/MahiGajjar27/A1--Linear-Regression.git
Medium: https://medium.com/@mgajjar/assignment-1-linear-regression-da25b24874a2

Problem Statement: Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet.

You would like to expand your business to cities that may give your restaurant higher profits.
The chain already has restaurants in various cities and you have data for profits and populations from the cities.
You also have data on cities that are candidates for a new restaurant.
For these cities, you have the city population.
Can you use the data to help you identify which cities may potentially give your business higher profits?

The linear regression program begins by importing essential libraries/packages such as numpy and matplotlib. It loads the dataset from a file using a user-defined function called `load_data()` from the `utils.py` module.

The dataset consists of two attributes: population of a city (x_train) and the profit of a restaurant in that city (y_train), both stored as numpy arrays.

The program educates itself about the dataset by visualizing it using matplotlib's `plt.scatter()` function, plotting population against profit with red 'x' markers.

The cost function computes the mean squared error (MSE) between predicted values and actual values, normalized by the number of training examples.

The gradients of the cost function with respect to parameters \(w\) and \(b\) are calculated using the partial derivatives of the cost function.

The `compute_gradient()` function computes these gradients and returns them.

Finally, the program initializes parameters \(w\) and \(b\), sets hyperparameters for gradient descent (learning rate, number of iterations), and trains the model using the `gradient_descent()` function. It then makes predictions based on input data and visualizes the linear fit alongside the original data points.
