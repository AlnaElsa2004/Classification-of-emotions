# Emotion Classification Project

## Overview
This project focuses on classifying emotions from facial expressions using deep learning. The workflow includes:
1. Training a model on a facial expression dataset.
2. Testing the model on a single image to classify a single face's emotion.
3. Extending the model to images with multiple faces to detect and classify each face's emotion.
4. Analyzing video frames to dynamically classify emotions.

The project was implemented in Google Colab.

## Instructions

### Step 1: Train the Model
1. Open the `notebooks/Classification_of_emotions.ipynb` notebook in Google Colab.
2. Upload your dataset to the `data/` folder.
3. Train the model and save it in the `models/` folder.

### Step 2: Test on a Single Image
1. Place an image file (e.g., `single_face.jpg`) in the `images/` folder.
2. Load the trained model in the notebook.
3. Test the model and save the result  in the folder.

### Step 3: Test on an Image with Multiple Faces
1. Place an image file (e.g., `multi_faces.jpg`) in the `images/` folder.
2. Use a face detection library (e.g., OpenCV or MTCNN) to detect multiple faces.
3. Classify emotions for each detected face and save the result in the folder.

### Step 4: Test on a Video
1. Place a video file (e.g., `test_video.mp4`) in the `videos/` folder.
2. Extract video frames and classify emotions frame by frame.
3. Annotate the frames with detected emotions and save the output video in the folder.

---

## Requirements
Install the dependencies from `requirements.txt`:
```bash
pip install -r requirements.txt
```
Key dependencies:

- TensorFlow
- OpenCV
- Numpy
- Matplotlib
- Pandas

## Results
- Single Image Test: Successfully identified emotions from a single face.
- Multi-Face Image Test: Detected and classified emotions for multiple faces in a single image.
- Video Test: Processed video frames and dynamically classified emotions, producing an annotated video.

## License

 This project is licensed under the MIT License. See the `LICENSE` file for more information.

  
