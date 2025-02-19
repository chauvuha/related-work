## Related Works

### Work 1: [Solving Differential Equations with Deep Learning: A Beginner’s Guide](https://arxiv.org/abs/2307.11237)
**Summary:** Solving differential equations with Deep Learning: a beginner’s guide 
Summary: This paper provides a strategy to use PINN (physics-informed neural networks) to solve ODEs of first order, second order, and non-linear second order. The paper also suggests how this might be applied in many simulations to advance physics. 
**Our Project's Difference:** Our project is different because we are actually going to implement this into code, and possibly compare a few different PINN networks and combine them.

### Work 2: [Solving Differential Equations Using Physics-Informed Deep Learning: A Hands-On Tutorial with Benchmark Tests](https://arxiv.org/abs/2302.12260)  
**Summary:** This paper revisits the concept of using deep learning to solve differential equations by embedding the equation knowledge into the loss function. This enables the model to learn the actual equations rather than merely fitting data points. It also provides a tutorial and benchmark tests for solving ODEs. The paper discusses the benefits and limitations of the PINN approach.  
**Our Project's Difference:** While this work focuses on a single neural network implementation, our project will compare several neural network architectures. Additionally, we aim to make the model more accessible by developing a web interface for public use.

### Work 3: [A Deep Learning Algorithm for Solving Partial Differential Equations](https://www.sciencedirect.com/science/article/pii/S0021999118305527)  
**Summary:** This research uses a different approach by training the neural network with random time and space points, as many partial differential equations (PDEs) lack analytical solutions. Thus, the model approximates results instead of solving them exactly.  
**Our Project's Difference:** Our project will focus on ODEs rather than PDEs. However, this work introduces an alternative training methodology that may yield valuable insights for our own research, potentially improving our approach to solving ODEs.

### Work 4: [Solve ODEs Using a Neural Network (MathWorks)](https://www.mathworks.com/help/deeplearning/ug/solve-odes-using-a-neural-network.html)  
**Summary:** MathWorks demonstrates solving an ordinary differential equation using a neural network instead of traditional numerical methods. The neural network provides differentiable approximate solutions in a closed analytic form. This work involves generating training data, defining a neural network, and training it with a custom loss function. It compares the neural network's predictions to the analytic solution.  
**Our Project's Difference:** Since our project also focuses on ODEs, this work serves as an important reference for understanding the training techniques and steps to solve ODEs with neural networks. We can potentially adapt their methods to improve accuracy and efficiency in our own project.

### Work 5: [Solving Differential Equations Using Deep Neural Networks](https://www.sciencedirect.com/science/article/abs/pii/S0925231220301909)  
**Summary:** this work focuses on solving partial differential equations through deep neural networks that optimize equations. This in turn produces an approximate solution to equations, rather than an exact solution, which is suitable for PDEs with irregular solutions.

**Our Project's Difference:**: On the other hand, our project focuses on providing exact solutions or the most simple version of the ordinary differential equations instead of PDEs. Additionally we won’t prioritize just irregular solutions, but rather encompass most if not all types of differential equations, providing a wider range of solutions/approximations that can be produced.

