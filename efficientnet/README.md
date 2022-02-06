# EfficientNet Implementation

An implementation of efficientnet

## Models

| Model           | Params | MAC (G) | PyTorch | Tensorflow |
|-----------------|--------|-----------|---------|------------|
| EfficientNet-B0 | 5.29M  | 0.385     | Yes     | Yes        |
| EfficientNet-B1 | 7.79M  | 0.569     | Yes     | Yes        |
| EfficientNet-B2 | 9.11M  | 0.659     | Yes     | Yes        |
| EfficientNet-B3 | 12.23M | 0.962     | Yes     | Yes        |
| EfficientNet-B4 | 19.34M | 1.5       | Yes     | Yes        |
| EfficientNet-B5 | 30.39M | 2.36      | Yes     | Yes        |
| EfficientNet-B6 | 43.04M | 3.36      | Yes     | Yes        |
| EfficientNet-B7 | 66.35M | 5.17      | Yes     | Yes        |


## Results

**Animals 138**

| Model | Acc  | Framework |
|:------|------|----------:|
| B0    | 84%  | PyTorch   |
| B1    | 85%  | PyTorch   |

## Sources

- [EfficientNet Paper](https://arxiv.org/pdf/1905.11946.pdf)
- [Torchvision Implementation](https://pytorch.org/vision/main/_modules/torchvision/models/efficientnet.html)
- [Tensorflow Implementation](https://github.com/keras-team/keras/blob/v2.8.0/keras/applications/efficientnet.py)
- [EfficientNet Tutorial](http://python.plainenglish.io/implementing-efficientnet-in-pytorch-part-3-mbconv-squeeze-and-excitation-and-more-4ca9fd62d302)