# CIFAR-10 CNN 
A convolutional neural network trained on the Cifar-10 dataset

Data Augmentation:
    Random Horizontal Flip
    Random Rotation (maximum angle of 10 degrees)
    Random Affine Transformations (shear up to 10, scale between 0.8 and 1.2)
    Color Jitter (brightness, contrast, saturation adjustments within a range)

Network Architecture:
    4 Convolutional Layers
    4 Fully Connected Layers
    Max Pooling Layers
    Dropout Layers
    Batch Normalization Layers

Weight Initialization:
    Kaiming Uniform Initialization

Optimization Algorithm:
    Stochastic Gradient Descent (SGD)

Learning Rate Schedule:
    Starting Learning Rate: 0.01
    Learning Rate Decreases to 0.001 and 0.0001 at 25 and 80 epochs respectively

Training Parameters:
    Epochs: 100
    Batch Size: 32
    
 
Network Test Accuracy: 86.47%
