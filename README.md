# face_recognition

One-Shot Learning and Face Recognition (Implementation of FaceNet Inception model)

Siamese Network for One-Shot Learning : 

A Siamese network is an architecture with two parallel neural networks, each taking a different input, and whose outputs are combined to provide some prediction

![alt text](https://github.com/SujayGouda/face_recognition/blob/main/siamese.jpeg)


Triplet Loss function for Learning Face Embeddings:
The loss function penalizes the model such that the distance between the matching examples is reduced and the distance between the non-matching examples is increased.

Keras-OpenFace pretrained weights are used for minimizing triplet loss function

Live-face-recognition system is implemented using webcam and OpenCV
