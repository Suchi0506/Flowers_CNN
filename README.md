# Flowers_CNN
Built a CNN-based flower classification model in TensorFlow with 94.17% accuracy, optimizing performance through added layers, dropout (0.3), Early Stopping, and hyperparameter tuning (batch size: 64, epochs: 20).

This file shows how to classify images of flowers using a tf.keras.Sequential model and load data using tf.keras.utils.image_dataset_from_directory. It demonstrates the following concepts:
1. Efficiently loading a dataset off disk.
2. Identifying overfitting and applying techniques to mitigate it, including data augmentation and dropout.

This tutorial follows a basic machine learning workflow:
1. Examine and understand data
2. Build an input pipeline
3. Build the model
4. Train the model
5. Test the model
6. Improve the model and repeat the process

This tutorial uses a dataset of about 3,700 photos of flowers. The dataset contains five sub-directories, one per class:

flower_photo/
  daisy/
  dandelion/
  roses/
  sunflowers/
  tulips/

Parameters used :
1. batch_size= 64
2. Added one more convolution layer before flattening
3. Implemented Early Stopping so that it will stop automatically if accuracy remain same for continuous 3 epochs.
4. Epochs= 20
5. Dropout= 0.3

Output= 94.17 percent confidence
