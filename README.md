# face-recognition
Project on OpenCV
Face detection and Recognition using OpenCV-python

A console based application

OpenCV based face recognition system that can detect and recognize multiple faces in an image.

There are 2 parts in a face recognition system.

1. Face Detection - To detect faces in images.

2. Face Recognition - To recognize face of persons in the images.

**FACE RECOGNITION**
We are using LBPH (Local Binary Patterns Histograms ) classifier to recognize the faces from the images. It compares neighboring pixels of a pixel and creates a histogram out of it for comparing faces. We could also use algorithms such as, EigenFaces Face Recognizer and FisherFaces Face Recognizer.

**REQUIREMENTS**

Python3

OpenCV2

PIL

Cascade Classifier

gspread

JSON


**How to run??**
1.Run create.py file to create a dataset by providing name and id, it will capture 20 images and store in dataset and convert into array, store in trainner.yml file.

2.Run detector.py to detect the face. If any face stored in dataset, the name of the person will be displayed.

3.The detected person's data will be added to the google form.
