# Brain-Tumor-Detection

This Project was accomplished using computer vision techniques

# Libraries

The code uses popular libraries lke Tensorflow, Keras, PIL, scikit-learn, matplotlib and Numpy. Data Preparation: Data Augmentation. Augmentation like rescale,shear_range,zoom_range,fill_mode,Width_shift_range,height_shift_range,validatio_split are defined to preprocess the Images.

Load Data: An Image dataset gotten from Kaggle is loaded from a given folder and label them according to their sub-directory name.

Data Splitting: The dataset is split into training, validation and test sets.
The datasets were loaded directly from their directories.

# Model Architecture:

The model(Brain_Tumor_Detection) consists of:

Two convolutional layers followed by a ReLU activationand max-pooling. Two fully connected layers to reduce the dimensions and output class scores. Training: Device: checks if a GPU is available and sets it as the device for computation.

Hyperparameters: definrs batch size, learning rate, and number of epochs.

Optimization and loss: Uses Adam optimizer and Cross-Entropy Loss.

Training Loop: Trains the model and validates it after each epoch. Implements early stopping based on validation loss.

# Metric Evalution:

Accuracy: Calculates the accuracy of the model on the test set.

Matplotlib visualization: uses matplotlib to visualize the accuracy of the training and validation set.

Model Saving: The model is saved for future Use.
