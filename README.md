# Drowsiness-Detection-Web-app
Prevents sleep deprivation road accidents, by alerting drowsy drivers.
In this project, we have trained a convolutional neural network, to determine whether the eyes are closed or not, further, eye-patches are extracted from the face image to make all predictions. The dataset used for the training process can be accessed from <a href="https://www.kaggle.com/kutaykutlu/drowsiness-detection" target="_blank">here.</a>
<br>This app can be tested live by cliking on the link below<br><a href="https://share.streamlit.io/mayureshagashe2105/hackulus21-drowsiness-detection-web-app/main/Eye_patch_Extractor_and_predictor.py" taget="_blank">Click Here</a>

## Understanding The Problem Statement
  According to the survey done by 'The Times of Inidia', nearly 40% of road accidents are caused by sleep deprivation. Fatigued drivers, long-duty driving are the major causes for the same. To solve this issue, this app primarily aims to predict whether or not the driver is sleeping, if found sleeping, it alerts the driver by making a high-frequency sound. This project is to avoid such sleep deprivation accidents!
  
  ## Implementation
1. A Deep Learning Model will be trained to detect whether the driver's eyelids are open or not. This will be achieved by training a Convolutional Neural Network using Tensorflow.<br>
2. A web-cam will take a picture of the driver's face at regular intervals of time and the patch of the driver's eye will be extracted from that picture. This task will be     <tab>achieved by using OpenCV.<br>
3. This patch will be further used for the prediction purpose with the model trained in step 1.<br>
4. Using this prediction, if the driver's eyes are closed a beep sound will be played, to alert the driver.<br>
