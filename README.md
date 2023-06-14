# model-ml

Data can be seen here: https://drive.google.com/drive/folders/1lVAt10pd0C0qSmptwv82nKwLuivb1t-n

which obtained from Kaggle:

1. https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification (6 anorganic types)
2. https://www.kaggle.com/datasets/techsash/waste-classification-data (organic dataset, taking from test set only)

For model, we used transfer learning with MobileNetV2 and adding few more layers. We obtain total 90% accuracy from test set.

After we saved the model to .h5 format, we convert it to .tflite format.
