# mnist-dl

The goal of the repository is to practice Deep-Learning with the new release of TensorFlow 2.0 with the MNIST dataset from Yann LeCun [website](http://yann.lecun.com/exdb/mnist/).

## Download the data

There is 4 datasets to download: images for train and test sets, and target for train and test sets.

```
curl 'http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz' > data/train-images-idx3-ubyte.gz
curl 'http://yann.lecun.com/exdb/mnist/train-labels-idx1-ubyte.gz' > data/train-labels-idx1-ubyte.gz
curl 'http://yann.lecun.com/exdb/mnist/t10k-images-idx3-ubyte.gz' > data/t10k-images-idx3-ubyte.gz
curl 'http://yann.lecun.com/exdb/mnist/t10k-labels-idx1-ubyte.gz' > data/t10k-labels-idx1-ubyte.gz
gzip -d train-images-idx3-ubyte.gz
gzip -d train-labels-idx1-ubyte.gz
gzip -d t10k-images-idx3-ubyte.gz
gzip -d t10k-labels-idx1-ubyte.gz
```
