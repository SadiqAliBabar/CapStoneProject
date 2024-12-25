# Human Action Recognition (HAR) Project

This project focuses on recognizing human actions in videos using a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks.

## Features
- **Video Processing**: Converts input videos into frames for analysis.
- **Action Recognition**: Predicts actions in the video frames using a trained model.
- **Output Generation**: Saves the predicted results into a processed video.

## Project Structure

HAR-Project/

├── models/  
├── output_videos/  
├── assets/  
├── README.md  
├── requirements.txt  
├── notebook.ipynb  

## Installation

Clone this repository:


### Install the required dependencies:


Data is here: [Google Drive Link](https://drive.google.com/drive/folders/1hqjOC6M3OmpwmAuBFAD99LR73ofpyXD5?usp=sharing)

### Usage
- **Run the Notebook**: Open the `notebook.ipynb` in a Jupyter environment.
- **Input Video**: Place your video in the appropriate directory.
- **Execute the Prediction**: Follow the steps in the notebook to generate predictions.
- **Output**: The processed video with action predictions will be saved in the `output_videos/` folder.

## Showing Some magic of my project
My project achieved about 81% accuracy :) not bad for a beginner.

![Screenshot](assets\ss2.png)

![Screenshot](assets\ss1.png)



## Model Details
- **Model Type**: CNN + LSTM
- **Training Method**: Sequential model trained on the UCF50 dataset.
- **Accuracy**: 81% on test data.
  
## Prediction 

## Video Preview

Here is a preview of one of the output videos generated from the model:

### Prediction 1

<video width="600" controls autoplay loop>
  <source src="OutputVideoFolder\Screen Recording 2024-12-24 182445.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### Prediction 2

<video width="600" controls autoplay loop>
  <source src="OutputVideoFolder\Screen Recording 2024-12-24 182544.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

