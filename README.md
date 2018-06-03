# Perceptron
1. This is a practice of helping me to learn the background mathematics in Perceptron.
2. The coding part is based on [lazy Programmer](https://github.com/lazyprogrammer)
***
## We will first introduce some basics of Perceptron
1. Perceptron can only handle binary classification problems.
2. Instead of using targets as 0 and 1, it's more often to use -1 and 1.
***
## Perceptron Training
1. The function of perceptron is like linear regression: W.T*X + b
2. We will usually pick w randomly, following gaussian distribution(Just an option) and start training.
3. After the first time of training, we will set x, y = randomly select one misclassifed example.
4. Let w = w + Ωyx, where Ω = 1.0, 0.1, 0.01,...etc.
