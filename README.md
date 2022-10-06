# Diabetic Retinopathy Detection

## Dataset

The dataset used is accessed from [Kaggle](https://www.kaggle.com/c/diabetic-retinopathy-detection).

## Data Preprocessing

- Each image was resized to 512\*512.
- Each image local average color is subtracted and is clipped to remove the boundary condition.

## Results

|      Models       | Accuracy | Precision | Recall | F1 score | Cohen Kappa |
| :---------------: | :------: | :-------: | :----: | :------: | :---------: |
|    ResNet50V2     |  0.817   |   0.779   | 0.817  |  0.780   |    0.654    |
|    ResNet101V2    |  0.799   |   0.753   | 0.799  |  0.762   |    0.629    |
|    DenseNet169    |  0.705   |   0.556   | 0.705  |  0.621   |    0.026    |
|    DenseNet201    |  0.790   |   0.739   | 0.790  |  0.739   |    0.552    |
|  EfficientNetB3   |  0.729   |   0.610   | 0.729  |  0.640   |    0.109    |
|  EfficientNetB6   |  0.595   |   0.569   | 0.595  |  0.567   |   -0.047    |
| InceptionResNetV2 |  0.817   |   0.779   | 0.817  |  0.780   |    0.654    |
|    InceptionV3    |  0.834   |   0.807   | 0.834  |  0.811   |    0.756    |
