DeepFake video Detection using Neural Networks 
(ResNext and LSTM)

1. Introduction
This project aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achieved deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further the LSTM layer is trained using the features. For more details follow the documentation.

You can also follow on LinkedIn to get video for better intuition about the project.

LinkedIn: - www.linkedin.com/in/pranav-bire-982412258
Dataset used - Deepfake detection challenge dataset: 
https://www.kaggle.com/c/deepfake-detectionchallenge

2. Directory Structure
For ease of understanding the project is structured in below format

Deepfake-video-detection-using-Neural-Networks
    |
    |--- Model Creation
    |--- Documentation
    |--- sample
    |--- models

Model Creation
This directory consists of the step-by-step process of creating and training a deepfake video detection model using our approach.

Documentation
This directory consists of the documentation done during the project with detailed explanation of each and every step.

Sample
This directory consists of sample data that can be used to try your own model training and testing process and get a hands-on feel. It also consists of the face cropped preprocessed data of the sample dataset.

Models
This directory consists of all the models we trained and exported in a “.pt” format file to compare the accuracy on different epochs and number of frames used for identification.

3. System Architecture




4. Our Results
Sr no.	Model	No. of videos	Sequence length	Accuracy
1	model_80_frames	1600	80	94.48743
2	model_100_frames	1600	100	93.97781
3	model _40_frames	1600	40	89.34681
4	model _20_frames	1600	20	84.21461

5. Future scope of the Project
There is always a scope for enhancements in any developed system, especially when the project is built using the latest trending technology and has a good scope in future.
•	Our method has not considered the audio. That is why there is a scope for integration of audio deepfake detection method in the proposed model. 
•	Currently only Face Deep Fakes are being detected by the algorithm, but the algorithm can be enhanced in detecting full body deep fakes.
•	Deploying the applications in free cloud
•	Batch processing of entire video instead of processing first 'x' frames.

