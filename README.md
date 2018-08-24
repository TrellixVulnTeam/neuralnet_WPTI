# Neuralnet

A high level framework for general purpose neural networks written in Theano.

## Requirements

[Theano](http://deeplearning.net/software/theano/)

[Scipy](https://www.scipy.org/install.html) 

[Numpy+mkl](http://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy)

[Matplotlib](https://matplotlib.org/)

[tqdm](https://github.com/tqdm/tqdm)

[visdom](https://github.com/facebookresearch/visdom)


## Installation
To install a stable version, use the following command

```
pip install neuralnet==0.1.0
```

The version in this repo tends to be newer since I am lazy to make a new version available on Pypi when the change is tiny. To install the version in this repo execute

```
pip install git+git://github.com/justanhduc/neuralnet.git@master (--ignore-installed) (--no-deps)
```

## Usages
To create a new model, simply make a new model class and inherit from Model in model.py. Please check out my [DenseNet](https://github.com/justanhduc/densenet) implementation for more details.
