# Transfer Learning for Image Classification

A TensorFlow/Keras notebook exercise for classifying Homer and Bart images. Explores a pretrained image network, a custom classification head and fine-tuning.

## Open the notebook

[Open in Google Colab](https://colab.research.google.com/github/MohammedAli201/Transfer-learning/blob/main/Transfer_learning.ipynb)

## Data and environment

The notebook expects a `homer_bart_2` dataset with `training_set` and `test_set` directories. The image archive is not bundled here; the original cells use Google Drive and `/content/` paths. Supply a dataset you have permission to use and adjust those paths before running.

Dependencies used include TensorFlow/Keras, NumPy, OpenCV, seaborn and scikit-learn. The notebook reflects its original library APIs; it is not a pinned, reproducible benchmark environment.

## What to inspect

The notebook covers preprocessing, model training and classification evaluation. Saved outputs are historical notebook results, not a newly rerun benchmark. The more domain-specific computer-vision project is [salmon keypoint detection](https://github.com/MohammedAli201/YOLO-keypoint-detection-Salmon-fish).
