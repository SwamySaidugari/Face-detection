# Face-Detection-streamlit-application

A project on Face Detection in a local image from PC and webcam live feed using Haarcascde frontal face classifier. Used OpenCV library for the over operations on the image data and streamlit for building web application.

## Description:
A Face Detection Streamlit Application is a computer program that uses computer vision and machine learning techniques to detect human faces in real-time video streams.
The application can be built using various libraries and frameworks, such as OpenCV,Streamlit,PIL and others.

The user interacts with the application through a web-based graphical user interface created using the Streamlit library, which allows developers to build interactive data apps quickly. With this application, users can record a video using their device's camera, and then the application will automatically detect and highlight the faces in the media.

The face detection algorithm used in the application works by analyzing the pixel values of the image or video frames to identify regions that are likely to contain a face. Once those regions are identified, the algorithm runs additional analysis to determine if a face is present in the region and where its boundaries lie.

Facial recognition technology is becoming increasingly popular for applications such as security, marketing, and entertainment. This application provides a simple and convenient way for developers to experiment with facial detection algorithms and integrate them into their own projects.

## Demo video 

  

https://user-images.githubusercontent.com/126857270/235299937-fbc3c22d-3281-48d7-8d94-d1879b13e86a.mp4



## Tech Stack:
- Language: Python
- Libraries: OpenCV,Streamlit, PIL
- Back-End: Streamlit
- IDE:VS code

## How to run:
- First create a virtual environment by using this command:
- conda create -n myenv python=3.6
- Activate the environment using the below command:
- conda activate myenv
- Then install all the packages by using the following command
- pip install -r requirements.txt
- Now for the final step. Run the app
- streamlit run app.py
- We can run the application by local port

