# EfficientNet Implementation

An implementation of efficientnet

## Models

| Model           | Params | MAC (G) | PyTorch | Tensorflow | Image Size |
|-----------------|--------|---------|---------|------------|------------|
| EfficientNet-B0 | 5.29M  | 0.385   | Yes     | Yes        | 224        |
| EfficientNet-B1 | 7.79M  | 0.569   | Yes     | Yes        | 240        |
| EfficientNet-B2 | 9.11M  | 0.659   | Yes     | Yes        | 260        |
| EfficientNet-B3 | 12.23M | 0.962   | Yes     | Yes        | 300        |
| EfficientNet-B4 | 19.34M | 1.5     | Yes     | Yes        | 380        |
| EfficientNet-B5 | 30.39M | 2.36    | Yes     | Yes        | 456        |
| EfficientNet-B6 | 43.04M | 3.36    | Yes     | Yes        | 528        |
| EfficientNet-B7 | 66.35M | 5.17    | Yes     | Yes        | 600        |


## Results

| Model | Acc  | Framework |   Dataset   |
|:------|------|----------:|-------------|
| B0    | 84%  | PyTorch   | Animals 138 |
| B0    | 88%  | PyTorch   | Birds 64    |
| B1    | 85%  | PyTorch   | Animals 138 |

## Sources

- [EfficientNet Paper](https://arxiv.org/pdf/1905.11946.pdf)
- [Torchvision Implementation](https://pytorch.org/vision/main/_modules/torchvision/models/efficientnet.html)
- [Tensorflow Implementation](https://github.com/keras-team/keras/blob/v2.8.0/keras/applications/efficientnet.py)
- [EfficientNet Tutorial](http://python.plainenglish.io/implementing-efficientnet-in-pytorch-part-3-mbconv-squeeze-and-excitation-and-more-4ca9fd62d302)