# FYS-STK4155-Project-3
Open files in Jupyter notebook to view them. <br>
EigenvalueSolver.ipynb is a neural network using the tensorflow keras neural network functionality. It solves the nonlinear differential equation <br>

$$\frac{dx(t)}{dt} = -x(t) + f(x(t))$$,

where $f(x) = [x^TxA+(1-x^TAx)I]x$, which will yield an eigenvector. <br>
PDESolver.ipynb is a neural network that solves the diffusion equation, <br>

$$
\frac{\partial u(x,t)}{\partial t} = \frac{\partial^2 u(x,t)}{\partial t^2}
$$
