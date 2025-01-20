# Image Classification on CIFAR-10 Dataset

## **Overview**
This project demonstrates a simple image classification model using a **Convolutional Neural Network (CNN)**. The model is trained on the **CIFAR-10 dataset**, which contains 60,000 32x32 color images in 10 classes.

## **Dataset**
### CIFAR-10 Dataset
- **Classes**:
  1. Airplane
  2. Automobile
  3. Bird
  4. Cat
  5. Deer
  6. Dog
  7. Frog
  8. Horse
  9. Ship
  10. Truck
- **Training Data**: 50,000 images
- **Testing Data**: 10,000 images

## **Model**
The model is a simple **Convolutional Neural Network (CNN)** with:
- Two **convolutional layers** followed by max pooling and dropout.
- A fully connected dense layer with dropout for regularization.
- A softmax output layer for classifying the 10 classes.

### **Architecture**
1. **Convolutional Layers**:
   - Extract features from the images.
2. **Max Pooling**:
   - Reduce the spatial dimensions.
3. **Dropout**:
   - Prevent overfitting.
4. **Dense Layer**:
   - Fully connected layer for classification.

## **Steps**
1. **Data Preprocessing**:
   - Normalized pixel values to the range `[0, 1]`.
   - Split data into training and testing sets.

2. **Model Training**:
   - Optimizer: **Adam**
   - Loss: **Sparse Categorical Crossentropy**
   - Trained for **10 epochs** with a batch size of 64.

3. **Evaluation**:
   - Tested on the CIFAR-10 test dataset.

4. **Custom Image Testing**:
   - The trained model predicts the class of a custom image provided.

## **Results**
- **Test Accuracy**: 70.24% (varies based on training and dataset splits).

### Visualization of Training and Validation:
1. **Accuracy Plot**:
   Shows training and validation accuracy over epochs.
2. **Loss Plot**:
   Shows training and validation loss over epochs.

