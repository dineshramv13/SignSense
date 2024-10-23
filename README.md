# Sign Language Recognition App

This application enables real-time sign language recognition using a webcam feed. It allows users to collect images, train a model, and run inference to detect hand gestures that correspond to letters of the alphabet. The application uses **Streamlit** for the interface, **OpenCV** for video processing, and **MediaPipe** for hand tracking and gesture detection.

## Features

- **Collect Images**: Capture images of hand gestures corresponding to letters for training.
- **Train Model**: Train a Random Forest classifier using the collected images to recognize sign language gestures.
- **Run Inference**: Perform real-time gesture recognition using the trained model and display recognized words.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dineshramv13/SignSense

## Usage

### 1. Collect Images
- Go to the **Collect Images** section.
- Enter a letter (A-Z) and specify the number of images to collect.
- Use the webcam feed to capture hand gestures representing the entered letter.

### 2. Train Model
- Go to the **Train Model** section.
- Click on the **Train** button to train a Random Forest classifier using the collected images.
- The trained model and label mappings will be saved as `model.p`.

### 3. Run Inference
- Go to the **Run Inference** section.
- Use the webcam to perform real-time hand gesture recognition.
- Recognized letters will be displayed on the screen and concatenated to form words.

## Project Structure

- `data/`: Directory where collected hand gesture images are stored.
- `model.p`: Pickle file to store the trained model and label map.

## Technologies

- **OpenCV**: For webcam video feed and image processing.
- **MediaPipe**: For hand detection and gesture recognition.
- **Scikit-learn**: For training the Random Forest classifier.


SignSense supports individuals with speech disabilities, including those who are non-verbal or use sign language. Using advanced machine learning, it interprets sign gestures in real-time, fostering inclusive communication and empowerment for diverse communities, including the deaf, those with speech disorders, and the elderly.

Run the codes in the follwing procedure:
1. collect_imgs.py
2. create_dataset.py
3. train_classifier.py
4. inference_classifier.py
