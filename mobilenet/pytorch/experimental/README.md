# Mobilenet V4 (Unofficial/Experimental)

Mobilenet V4 is my attempt at improving Mobilenet V3.

**Changes Made**

1. Introduced Fused MBConv (from EfficientNet v2) into MobileNet

| Model              | Params | MAC (M)   | PyTorch | Tensorflow | JAX/Flax |
|--------------------|--------|-----------|---------|------------|----------|
| MobileNet V4 Large | 5.48M  | 216.6     | Yes     | No         | No       |
| MobileNet V4 Small | 2.54M  | 56.5      | Yes     | No         | No       |

| Model |   Acc  | Framework |  Dataset   |
|:------|--------|----------:|------------|
| V4S   | 86.4%  | PyTorch   |  Birds 64  |
| V4L   | 89.2%  | PyTorch   |  Birds 64  |