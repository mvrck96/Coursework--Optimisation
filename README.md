# BGD and Adadelta methods for function approximation problem

## Short info

Implemented methods:

- Batch Gradient Descent
- Adadelta

Approximation function: F(w, x): w_1 + w_2*x + w_3*x^2  

Loss function: __MSE__

Further details could be found in `paper.pdf`

## Requirements

- `numpy`
- `matplotlib`

## References
1. Matthew D. Zeiler, [ADADELTA: AN ADAPTIVE LEARNING RATE METHOD][1].
2. Sebastian Ruder, [An overview of gradient descent optimization algorithms][2].

[1]: https://arxiv.org/pdf/1212.5701.pdf	"ADADELTA: AN ADAPTIVE LEARNING RATE METHOD"
[2]: https://ruder.io/optimizing-gradient-descent/	"An overview of gradient descent optimization algorithms"
