1. The Addition problem: The addition problem is a toy benchmark used to evaluate the power of RNNs in learning
long-term dependencies (Hochreiter & Schmidhuber, 1997). The input to the RNN is a
two-dimensional sequence $X = \{x 0 (t), x 1 (t)\}|^T_{t=0}$ . At each time step the input consists of
a random signal x 0 ∈ [0, 1] and a mask signal x 1 (t). The mask signal has all zeros except
at two time steps when it has a value of 1. The RNN is to be trained to predict the sum of
x 0 at these two time steps.
