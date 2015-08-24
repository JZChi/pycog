# Excitatory-inhibitory recurrent neural networks for cognitive tasks

## Requirements

This code is written in Python and requires

* [Theano](http://deeplearning.net/software/theano/)

Optional but recommended if you plan to run many trials with the trained networks, outside of Theano, for analysis purposes:

* [Cython](http://cython.org/)

Also optional but recommended for analysis and visualization of the networks (including examples from the paper):

* matplotlib

## Installation

Go to the pycog directory and type

```bash
python setup.py develop
```

## Example

The networks used to generate the figures in the paper were trained using the specifications contained in /examples/models. It's instructive, however, to consider an example that strips away the embellishments such as different sets of trials for gradient and validation datasets.

* TODO

## Note

It is common to see the following warning when running Theano:

```bash
RuntimeWarning: numpy.ndarray size changed, may indicate binary incompatibility
  rval = __import__(module_name, {}, {}, [module_name])
```

This is almost always innocuous and can be safely ignored.

## License

MIT

## Citation

If you find our code helpful, consider giving us a shout-out in your publications:

* Song, H. F., Yang, G. Robert, and Wang, X.-J. "Training Excitatory-Inhibitory Recurrent Neural Networks: A Simple and Flexible Framework for Cognitive Tasks." 2015.
