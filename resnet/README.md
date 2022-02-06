# ResNet Implementation

This folder contains a implementation of ResNet in Tensorflow and PyTorch. Each model is set to 1000 classes default, and both Tensorflow and PyTorch implementations can be customized

| Model              | Params | FLOPS (G) | PyTorch | Tensorflow | JAX/Flax |
|--------------------|--------|-----------|---------|------------|----------|
| ResNet 18          | 11.69M | 1.81      | Yes     | Yes        | No       |
| ResNet 34          | 21.8M  | 3.55      | Yes     | Yes        | No       |
| ResNet 50          | 25.56M | 4.09      | Yes     | Yes        | No       |
| ResNet 101         | 44.55M | 7.80      | Yes     | Yes        | No       |

## Sources

- [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385.pdf)
- https://github.com/keras-team/keras/blob/master/keras/applications/resnet.py