# Simple Neural Network
A neural network written in Python, consisting of a single neuron that uses gradient descent to learn.

https://medium.com/technology-invention-and-more/how-to-build-a-simple-neural-network-in-9-lines-of-python-code-cc8f23647ca1

### Requirements
- Python 3
- numpy

### How to run
Install numpy, then run either script:

```
pip install numpy
python3 main.py
python3 short_version.py
```

`main.py` is the commented, step-by-step version. It prints the random starting weights, the weights after training, and the prediction for the new input `[1, 0, 0]`.

`short_version.py` does the same training in 9 lines and prints only the prediction.

Both should predict a value close to 1 (about 0.99993).
