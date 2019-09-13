# Face Averaging with dlib and OpenCV

This Python 2.x program averages faces of different people. You must have [dlib](http://dlib.net/) installed for this to work, and download the shape_predictor_68_face_landmarks.dat file. 

To run, first have your images (jpg) ready and run:
```
./face_landmark_detection.py shape_predictor_68_face_landmarks.dat ../path-to-your-jpgs

```

This should output a txt file with the facial coordinates. You can use the coordinates to create a "Face average" using the python file
```
python faceAverage.py
```

I also used [this starter code](https://www.learnopencv.com/average-face-opencv-c-python-tutorial/). There's also a tutorial there, so check it out.
