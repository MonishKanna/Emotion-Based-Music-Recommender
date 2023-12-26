# Emotion-Based Music Recommender

## Overview
The "Emotion-Based Music Recommender" project involves building and training convolutional neural network (CNN) and fine-tuned ResNet50V2 models for facial emotion recognition. The goal is to recommend music playlists based on detected emotional states from facial expressions. The project includes data visualization, preprocessing, model building, training, evaluation, and practical applications for music recommendations.

## Project Structure

1. **Visualizing Classes**
   - Display class distribution in training and test datasets.
   - Show sample images from each class.

2. **Data Preprocessing**
   - Resize images to 48x48 pixels.
   - Apply data augmentation to the training set.
   - Create data generators for training and testing.

3. **Building CNN Model**
   - Define a CNN model for facial emotion recognition.
   - Compile the model using Adam optimizer and categorical crossentropy loss.

4. **Specifying Callbacks**
   - Implement ModelCheckpoint, EarlyStopping, and ReduceLROnPlateau.

5. **Training CNN Model**
   - Train the CNN model on preprocessed data.
   - Evaluate the model on the test dataset.

6. **Evaluating CNN Model**
   - Display test loss and accuracy.
   - Plot training and validation curves.
   - Visualize the confusion matrix.

7. **ResNet50V2 Model**
   - Load ResNet50V2 model with pre-trained weights.
   - Fine-tune the model for emotion classification.

8. **Fine-Tuning ResNet50V2**
   - Train the fine-tuned ResNet50V2 model.
   - Evaluate the model on the test dataset.

9. **Evaluating ResNet50V2**
   - Display test loss and accuracy.
   - Plot training and validation curves.
   - Visualize the confusion matrix.

10. **Visualizing Predictions**
    - Display sample predictions using CNN and ResNet50V2 models.
    - Show music recommendations based on predicted emotions.

11. **Music Player**
    - Explore a dataset of songs with mood labels.
    - Display mood distribution and song popularity statistics.
    - Recommend songs based on predicted emotions.

12. **Predicting New Images**
    - Download Haarcascade frontalface detection for face detection.
    - Load, preprocess, and predict emotions on new images.
    - Provide music recommendations based on predicted emotions.

## Usage
1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/emotion-based-music-recommender.git
   cd emotion-based-music-recommender
