# Deepfake detection using Deep Learning (ResNext and LSTM)

## 1. Introduction
This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achived deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further the LSTM layer is trained using the features. 

## 2. Directory Structure
For ease of understanding the project is structured in below format
```
Deepfake_detection_using_deep_learning
    |
    |--- Django Application
    |--- Model Creation
```
1. Django Application 
   - This directory consists of the django made application of our work. Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.
2. Model Creation
   - This directory consists of the step by step process of creating and training a deepfake detection model using our approach.

   


## 3. Our Results

| Model Name | No of videos | No of Frames | Accuracy |
|------------|--------------|--------------|----------|
|model_84_acc_10_frames_final_data.pt |6000 |10 |84.21461|
|model_87_acc_20_frames_final_data.pt | 6000 |20 |87.79160|
|model_89_acc_40_frames_final_data.pt | 6000| 40 |89.34681|
|model_90_acc_60_frames_final_data.pt | 6000| 60 |90.59097 |
|model_91_acc_80_frames_final_data.pt | 6000 | 80 | 91.49818 |
|model_93_acc_100_frames_final_data.pt| 6000 | 100 | 93.58794|

## Download Models
https://drive.google.com/drive/folders/1UX8jXUXyEjhLLZ38tcgOwGsZ6XFSLDJ-?usp=sharing
