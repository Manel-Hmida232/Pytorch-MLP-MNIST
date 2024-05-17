This project involves using PyTorch, a popular machine learning library, to create a Multi-Layer Perceptron (MLP) model for the MNIST dataset.
 Here's a breakdown of the project :
 
1.Dataset Loading and Pre-processing:
    The project starts by loading the MNIST dataset, which consists of 60,000 training images and 10,000 test images of handwritten digits.
    The images are pre-processed by transforming them into PyTorch tensors and normalizing them to have a mean of 0.0 and a standard deviation of 1.0.
    
2.Model Configuration:
    The MLP model is built using PyTorch, including the necessary libraries like torch, torch.nn, and torch.optim.
    The device for training is configured to use the GPU if available; otherwise, it falls back to using the CPU.
   
3.Training Data:
    The training data is loaded from the MNIST dataset, and the number of data points is confirmed to be 60,000.
    The shape of the targets (labels) is shown as torch.Size([60000]), and the shape of the data is torch.Size([60000, 28, 28]).
    
4.Displaying Training Images:
    The project displays the first 9 training images along with their corresponding labels using matplotlib.
    Each image is shown using plt.imshow in grayscale, with the label as the title.
