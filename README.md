# Face Recognition
A face recognition model using the facebook embedder model with dlib. 
An lasagne MLP is used for distinguishing between faces in the database.

[![Play the gif](https://github.com/JamesUnicomb/face_recognition/blob/master/faces_encoded.gif)](https://www.youtube.com/watch?v=aa7Rk-uxxjI)
Video Link: https://www.youtube.com/watch?v=aa7Rk-uxxjI

## Face Messages
For each processed frame a message will be published with a ML predicted face and probability accociated with that matching.
```
Header header
string[] names
float64[] probability
float64[] distances
```
Probabilities and distances for each prediction are given for each face measurement for rejection of unknowns.

## Future Work
Work on a way of recognising unknown faces and rejecting faces not in the database.
