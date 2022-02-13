# EfficientNet Lite Implementation

The following is an implementation of EfficientNet Lite in PyTorch and Tensorflow.

EfficientNet lite is basically EfficientNet but with SEBlocks removed and it uses Relu6 instead of Swish/SILU. The depths of the first and last layers are not scaled. There are only 5 models, Lite0 - Lite4 which correspond to EfficientNet B0 - B4.

| Model              | Params | MAC (G) | Image Size | PyTorch | Tensorflow |
|--------------------|--------|---------|------------|---------|------------|
| EfficientNet-Lite0 | 4.65M  | 0.385   | 224        | Yes     | Yes        |
| EfficientNet-Lite1 | 5.42M  | 0.600   | 240        | Yes     | Yes        |
| EfficientNet-Lite2 | 6.01M  | 0.859   | 260        | Yes     | Yes        |
| EfficientNet-Lite3 | 8.20M  | 1.38    | 280        | Yes     | Yes        |
| EfficientNet-Lite4 | 13.01M | 2.55    | 300        | Yes     | Yes        |

## Sources

- My EfficientNet Code (found in `/efficientnet` folder)
- [Papers with Code](https://paperswithcode.com/model/tf-efficientnet-lite)
- [Tensorflow Official Implementation](https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet/lite)
- [timm Implementation](https://github.com/rwightman/pytorch-image-models/blob/master/timm/models/efficientnet.py)