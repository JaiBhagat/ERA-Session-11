# ERA-Session-11
# Assignment Objective

In this assignment, you are tasked with constructing a training architecture as described.

## Requirements:

1. Build a training structure for ResNet18 on the CIFAR10 dataset, ensuring the training is performed for 20 epochs.
2. Do **NOT** manually copy and paste the code. Instead, sync your Google Colab notebook with your GitHub repository to pull the required code.
3. Ensure that your Google Colab notebook is minimalistic in nature. Avoid defining any class or function directly in the notebook. Instead, all functionalities should be imported from your other files.
4. The Colab notebook should fulfill the following criteria:
    - Conduct training of ResNet18 over 20 epochs on the CIFAR10 dataset.
    - Visualize the loss curves for both test and training datasets.
    - Display a gallery containing 10 misclassified images.
    - Illustrate the [GradCAM](link-to-gradcam) output on these 10 misclassified images. However, ensure the channel applied for GradCAM is not less than 5px. 
5. Ensure that the following transforms are applied during training:
    - `RandomCrop(32, padding=4)`
    - `CutOut(16x16)`

Upon completion:
- Push the code to your GitHub repository.
- Share the link to your code.
- This README should contain a link to the main repository, facilitating a better understanding of your file structure.

**Note**: When utilizing GradCAM for the misclassified images, ensure you make use of the library discussed in class. 

