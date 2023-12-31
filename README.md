# Visualizing Gradient-Descent-Method in 2D and 3D with Matplotlib and Numpy
A short description and python implementation of Gradient descent, an optimization algorithm which is used to train machine learning models and neural networks.

To install all the necessary libraries:
````
pip install -r requirements.txt
````
**Gradient Descent optimization**

Gradient descent is a practical, efficient algorithm for adjusting the parameters of a model with the goal of minimizing the cost.
The method is widely used not only in deep learning, but in machine learning in general.


For a better understanding, let's look at the figure below.

![Screenshot](Visualisation_Gradient_Descent.PNG)


**How does the algorithm Gradient descent work?**

1. A random starting point x<sub>0</sub> is picked.
2. While the gradient hasn’t converged, compute the negative gradient at x<sub>0</sub>.
3. Update the point x<sub>0</sub>.
   On each iteration you run an update rule.

   Mathematically:

   $x_{ t+1 } = x_{ t } - \alpha \nabla f(x_{ t })$;

   where $x_{ t+1 }$ is the position of the next iteration,
   
   $x_{ t }$ is the position of previous step,

   $\alpha$ is the learning rate.
   
5. Repeat the process till you find the minimum.

To visulaize and get a better imagination, run the files Gradient Descent 2D or 3D and enjoy it.

For questions and suggestions:


[Talha Filikci](mailto:talhafilikci@gmail.com?subject=[Github])
