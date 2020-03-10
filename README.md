# Python-Time-Series-Analysis

A time series is a series of data points indexed in time order. The sequence of data points taken at successive equally spaced points in time. Examples of time series are daily closing value of the Dow Jones Industrial Average, 

Time series are very frequently in statistics, signal processing, pattern recognition, econometrics, mathematical finance, control engineering, astronomy, communications engineering, and largely in any domain of applied science and engineering which involves temporal measurements.

Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values



PyTorch is an open source deep learning platform, primarily developed by Facebook's artificial-intelligence research group, that provides a seamless path from research prototyping to production deployment.  

PyTorch provides two high-level features:
- Tensor computation (like NumPy) with strong GPU acceleration
- Deep neural networks built on a tape-based autodiff system

Tensors can simply be considered multidimensional arrays. Tensors in PyTorch are similar to NumPy arrays, with the addition being that Tensors can also be used on a GPU that supports CUDA.

<br>

> PyTorch Modules

- Autograd Module: PyTorch uses a technique called automatic differentiation. A recorder records what operations have performed, and then it replays it backward to compute the gradients. This technique is especially powerful when building neural networks in order to save time on one epoch by calculating differentiation of the parameters at the forward pass itself.
- Optim Module: torch.optim is a module that implements various optimization algorithms used for building neural networks. 
- nn Module: PyTorch autograd makes it easy to define computational graphs and take gradients, but raw autograd can be a bit too low-level for defining complex neural networks. This is where the nn module can help.


In this project we show how to use PyToch to address the most popular deep learning topics:

- Binary classification
- Multiclass classification
- Regression
- Auto-Encoder
- Denoizing Auto-Encoder
- RNN (LSTM)
- CNN
- GAN

Each topic will refers to Notebook example. The example assume that reader are familiar with the theory of the neural networks and Python.

More PyTorch tutorials are available [here](https://pytorch.org/tutorials/)

<br>

> Requirements

- Python 3
- PyTorch
- Pandas

<br>

> Project structure:

- examples: example Notebook 
- data: input data used to build example

### Enjoy!

<br>
