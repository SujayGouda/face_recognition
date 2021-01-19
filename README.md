# face_recognition

![alt text](https://image.freepik.com/free-vector/face-recognition-low-poly-wireframe-banner-template-futuristic-computer-technology-smart-identification-system-poster-polygonal-design-facial-scan-3d-mesh-art-with-connected-dots_201274-4.jpg)

## One-Shot Learning and Face Recognition (Implementation of FaceNet Inception model)

### Siamese Network for One-Shot Learning : 

![alt text](https://github.com/SujayGouda/face_recognition/blob/main/siamese.jpeg)

A Siamese network is an architecture with two parallel neural networks, each taking a different input, and whose outputs are combined to provide some prediction



### Triplet Loss function for Learning Face Embeddings:
The loss function penalizes the model such that the distance between the matching examples is reduced and the distance between the non-matching examples is increased.

### Weights:
Keras-OpenFace pretrained weights are used for minimizing triplet loss function

### Euclidean distance:
Calculates distance between the test image vector with all the images in the database. If distance is less than the threshold factor, then prediction is correct

### New-user:
Implemented a function to start web-cam and capture users faces, crop them for training

### Face recognition system:
Live-face-recognition system is implemented using webcam and OpenCV
