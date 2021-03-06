# EfficientNet V2

The table lists below the supported EfficientNet V2 models

| Model             | Params | MAC (G)   | PyTorch | Tensorflow |
|-------------------|--------|-----------|---------|------------|
| EfficientNetV2-B0 | 7.14M  | 0.718     | Yes     | Yes        |
| EfficientNetV2-B1 | 8.14M  | 1.02      | Yes     | Yes        |
| EfficientNetV2-B2 | 10.10M | 1.17      | Yes     | Yes        |
| EfficientNetV2-S  | 21.46M | 2.85      | Yes     | Yes        |
| EfficientNetV2-M  | 54.14M | 5.36      | Yes     | Yes        |
| EfficientNetV2-L  | 118.52M| 12.23     | Yes     | Yes        |

## Results

| Model | Acc | Framework | Dataset     |
|:------|-----|:---------:|------------:|
| V2-B0 | 91% | PyTorch   | Animals 138 |

## Sources

- [EfficientNet V2 Paper](https://arxiv.org/pdf/2104.00298.pdf)
- My EfficientNet V1 Code and my MobileNet code.
- [Keras Implementation](https://github.com/keras-team/keras/blob/v2.8.0/keras/applications/efficientnet_v2.py)