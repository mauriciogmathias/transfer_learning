Cats vs. Dogs Classification - README
=====================================

Project Overview
----------------
This project is a binary classification task to distinguish between images of cats and dogs using a pre-trained MobileNetV2 model. The workflow includes:
1. Data Loading: Load and split the dataset into training, validation, and test sets.
2. Data Augmentation: Apply transformations like flipping and rotation to the training data.
3. Transfer Learning: Use MobileNetV2 as the base model, fine-tuned for our custom dataset.
4. Model Training: Train the model and monitor its performance on the validation set.
5. Evaluation: Plot the accuracy and loss metrics to visualize the training process.

Structure
---------
Here’s how the project is structured:
- `cats_and_dogs_filtered/`: Contains the dataset with separate directories for training and validation images.
  - `train/`: Contains subdirectories for cat and dog images used in training.
  - `validation/`: Contains subdirectories for cat and dog images used in validation.
- `scripts/`**: Holds the Python script for training the model.
