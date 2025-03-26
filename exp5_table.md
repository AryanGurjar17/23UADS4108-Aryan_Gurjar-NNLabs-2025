| Layer            | Type            | Output Shape | Parameters |
|------------------|-----------------|--------------|------------|
| Conv2D (32, 3×3) | Convolution     | (28, 28, 32) | 320        |
| MaxPooling (2×2) | Pooling         | (14, 14, 32) | 0          |
| Conv2D (64, 3×3) | Convolution     | (14, 14, 64) | 18,496     |
| MaxPooling (2×2) | Pooling         | (7, 7, 64)   | 0          |
| Flatten()        | Fully Connected | 3136         | 0          |
| Dense (128)      | Fully Connected | 128          | 401,536    |
| Dense (10)       | Output          | 10           | 1,290      |
