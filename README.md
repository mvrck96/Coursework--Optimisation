# BGD and Adadelta methods for function approximation problem

## Short info

Implemented methods:

- [Batch Gradient Descent][2]
- [Adadelta][1] 

Approximation function: $ F(\theta, x): \theta_1 + \theta_2x + \theta_3x^2$  

Loss function (MSE): $ Q(\theta) = \frac{1}{l} \sum_{i=1}^{l}\left [ f(\theta, x_i) - y_i\right]^2 = \frac{1}{l} \sum_{i=1}^{l} L(\theta, x_i, y_i) \rightarrow \min_{\theta \in R^n}$

Further details could be found in `paper.pdf`

## Requirements

- `numpy`
- `matplotlib`

## References

[1]: https://arxiv.org/pdf/1212.5701.pdf	"ADADELTA: AN ADAPTIVE LEARNING RATE METHOD"
[2]: https://ruder.io/optimizing-gradient-descent/	"An overview of gradient descent optimization algorithms"