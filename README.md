#### Handwritten Digit Recognition Using CNN

Handwritten Digit Recognition is a crucial task in pattern recognition with various applications in document digitization and automated sorting. This project focuses on using Convolutional Neural Networks (CNNs) to automatically learn features from raw pixel data for accurate and robust handwritten digit recognition. The project aims to address the limitations of traditional methods and demonstrate the potential of CNNs to enhance accuracy and robustness in this task. The system combines machine learning techniques with a user-friendly interface to facilitate efficient and reliable handwriting recognition in real-world scenarios.Handwritten Recognition (HR) presents challenges due to individual writing styles. This project explores the limitations of existing systems using traditional algorithms and manual feature engineering. It proposes a solution leveraging Convolutional Neural Networks (CNNs) to learn features directly from raw pixel data. CNNs have revolutionized digit recognition by effectively learning patterns from large datasets.

### Problem Statement
The project's objective is to develop an accurate and robust handwritten digit recognition system that handles diverse handwriting styles and varying image conditions. The system aims to improve operational efficiency in industries relying on accurate handwritten digit recognition.

### Proposed System
The proposed system utilizes Convolutional Neural Networks (CNNs) for handwritten digit recognition. The system includes a deep CNN architecture designed for this task. The network consists of convolutional layers, pooling layers, and fully connected layers. It is trained on the MNIST dataset, containing labeled grayscale images of handwritten digits. The system is expected to achieve higher accuracy and robustness compared to traditional methods.

## Algorithm

### Purpose
To develop a system for accurate real-time handwritten digit recognition using CNNs.

### Inputs
- Handwritten digit images (MNIST dataset)
- Real-time handwritten digit images captured from a whiteboard using Pygame

### Outputs
- Recognized digit label
- Display of the recognized digit with a bounding box

### Algorithm Steps

#### Training Phase
1. Import necessary libraries and modules.
2. Load the MNIST dataset.
3. Preprocess the dataset by normalizing pixels and converting labels to one-hot vectors.
4. Define the CNN model architecture.
5. Compile the model with suitable optimizer and loss function.
6. Set up early stopping and model checkpoint callbacks.
7. Train the model on the preprocessed dataset.
8. Save the trained model for future use.

#### Real-time Digit Recognition
1. Initialize Pygame and display window.
2. Capture and process handwritten digits.
3. Continuously monitor for user events.
4. Record drawn points and update the digit area.
5. Extract the digit area after drawing completion.
6. Resize and preprocess the digit image.
7. Use the trained model to predict the digit label.
8. Display the recognized digit label and draw a bounding box.
9. Repeat steps 3-8 until program termination.

## System Requirements

### Hardware Requirements
- Processor: Intel Core i5 or equivalent.
- Memory (RAM): Minimum 8 GB.
- Storage: Adequate space to store code, datasets, and resources.

### Software Requirements
- Operating System: Windows, macOS, or Linux.
- Python: Python 3.x installed.
- Python Libraries: numpy >= 1.16.0, matplotlib >= 3.0.0, keras >= 2.4.0.

### Dataset
- MNIST Dataset: Contains 60,000 grayscale training images and 10,000 test images with corresponding labels.
