# Face Averaging with dlib and OpenCV

This Python program averages faces of different people. You must have dlib installed for this to work, and download the shape_predictor_68_face_landmarks.dat. 

To run, first have your images (jpg) ready and run:
```
python facial_landmarks.py --shape-predictor shape_predictor_68_face_landmarks.dat --image yourimagename.jpg
```

This should output a txt file with the coordinates. You can use the coordinates to create a "Face average" using the python file
```
python faceAverage.py
```
