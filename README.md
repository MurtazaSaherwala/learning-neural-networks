## learning-neural-networks
This is a repo for building my foundation on neural networks with Andrej Karparthy

![small-ai-generated-hyper-realistic-adorable-cute-baby-cat](https://github.com/user-attachments/assets/ace013ec-e533-4753-84e8-32b935209d0c)

# Micrograd
A tiny Autograd engine (with a bite! :)). Implements backpropagation (reverse-mode autodiff) over a dynamically built DAG and a small neural networks library on top of it with a PyTorch-like API. Both are tiny, with about 100 and 50 lines of code respectively. The DAG only operates over scalar values, so e.g. we chop up each neuron into all of its individual tiny adds and multiplies. However, this is enough to build up entire deep neural nets doing binary classification, as the demo notebook shows. Potentially useful for educational purposes.
