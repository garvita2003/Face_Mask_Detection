# Face_Mask_Detection

Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.

The model is accurate, and since we used the CNN architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

The suggested model is created in three stages:
1. Data Pre-Processing
2. CNN Model Training
3. Applying the Face Mask Detector - to distinguish the appearance into “With Face Mask” and “Without Face Mask”

In order to curb the COVID-19 pandemic from spreading, this publication suggests a face mask 
identification system for still photos and live video that can detect whether a person is wearing a mask automatically. The suggested system can determine if a face mask is present or not using Keras, OpenCV, and CNN, and the model provides accurate and prompt results. An accuracy of about 97% is produced by the trained model.

Download the Dataset : [Dataset](https://drive.google.com/drive/folders/1TF-20w7rVJ-GPRFSvFNvNn5D_yx6o1wm?usp=sharing)

# Technology / Framework used:

1. Pythonn
2. Machine Learning
3. Deep Learning
4. OpenCV
5. Caffe-based face detector
6. Keras
7. TesorFlow
8. CNN - MobileNet
9. Streamlit
10. Usecase

# Instruction - Procedure / Flow of the Project to Execute the code:

1. Load the provided folder in the google drive 
2. Run the Model_Training.py file first
3. Then load the dataset as Facemask_Detection from the drive
4. Save the trained model in the new file having .h5 extension in the google drive itself (Cell 28 - Training)
5. Now Run the Model_Image_Testing.py file
6. In 4th cell of that file give the loaction of deploy.prototxt.txt and res10_300x300_ssd_iter_140000.caffemodel from your google drive path that you mounted at the start
7. Then Load the trained model that you saved as .h5 extension (Point 4) from your drive (Cell 8 - Testing)
8. Read any image from the dataset of images provided with and without mask in single or group images and test (Cell 18 - Testing) 

# Overview:

![Screenshot 2025-01-05 151055](https://github.com/user-attachments/assets/ad9d640a-4bea-4f89-a5d5-8101d9bc1ae8)
![Screenshot 2025-01-05 151113](https://github.com/user-attachments/assets/67db7c3a-c1f2-4d62-85dd-845f42be33bc)
![Screenshot 2025-01-05 151139](https://github.com/user-attachments/assets/7f7991b6-2b1f-41e0-9b90-853512a90ab3)
![Screenshot 2025-01-05 151147](https://github.com/user-attachments/assets/c5d3759d-c2d8-446d-9f14-49a310550b3e)
![Screenshot 2025-01-05 151154](https://github.com/user-attachments/assets/1ce510da-05f6-4036-a490-f9c16eecf45c)
![Screenshot 2025-01-05 151204](https://github.com/user-attachments/assets/b5ea8b43-4e5c-4a85-bf74-687382647031)
![Screenshot 2025-01-05 151227](https://github.com/user-attachments/assets/6ad6ae7e-da77-4bb2-8135-e23961b1d9d7)
![Screenshot 2025-01-05 151235](https://github.com/user-attachments/assets/a6a940e1-1127-49f2-82ec-fcf195aa8de0)
