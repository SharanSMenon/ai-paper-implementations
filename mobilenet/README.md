# Mobilenet Implementation

The table below lists the supported models and their implementation status.

| Model              | Params | FLOPS (M) | PyTorch | Tensorflow | JAX/Flax |
|--------------------|--------|-----------|---------|------------|----------|
| MobileNet V1       |        |           | No      | No         | No       |
| MobileNet V2       | 3.50M  | 300.81    | Yes     | Yes        | No       |
| MobileNet V3 Large | 5.48M  | 216.6     | Yes     | No         | No       |
| MobileNet V3 Small | 2.54M  | 56.5      | Yes     | No         | No       |

## Results

| Model | Acc  | Framework |
|:------|------|----------:|
| NA    | NA%  | None      |

## Sources

- [MobileNet V1 Paper](https://arxiv.org/pdf/1704.04861.pdf)
- [MobileNet V2 Paper](https://arxiv.org/pdf/1801.04381.pdf)
- [Mobilenet V3 Paper](https://arxiv.org/pdf/1905.02244.pdf)
- [Torchvision Mobilenet](https://pytorch.org/vision/0.9/_modules/torchvision/models/mobilenetv3.html#mobilenet_v3_large)
- [Keras Mobilenet V2](https://github.com/keras-team/keras/blob/v2.8.0/keras/applications/mobilenet_v2.py)
- [Inverted Residual Explanation](https://ttumiel.github.io/blog/mobilenet-to-efficientnet/)
