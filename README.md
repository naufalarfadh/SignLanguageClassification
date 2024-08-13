This project involves implementing a multi-class classification problem using the Sign Language MNIST dataset, which contains 28x28 pixel images of hands representing the 26 letters of the English alphabet. The goal is to train a Convolutional Neural Network (CNN) to accurately classify each image as the corresponding letter.

## Key Features
- **Data Pre-processing:** The dataset is provided in CSV format and processed into numpy arrays representing 28x28 pixel images, ready for CNN input.
- **Data Augmentation:** Images are augmented using `ImageDataGenerator` with transformations like rotation, shift, zoom, and flip to enhance model performance.
- **Model Architecture:** A CNN model is constructed with two Conv2D and MaxPooling2D layers, followed by Dense layers for classification.
- **Training and Validation:** The model is trained and validated to evaluate its performance on unseen data.
- **Visualization:** Training and validation accuracy and loss are visualized to assess the model's effectiveness.
