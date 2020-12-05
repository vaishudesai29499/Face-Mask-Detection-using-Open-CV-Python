Performing Face Mask Detection using Open-CV Python

Face Mask Detector Project using concept of OpenCV, Keras/TensorFlow, and Deep Learning etc.

In order to train a custom face mask detector, I break our project into two distinct phases, each with its own respective sub-steps:

1.Training: Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras/TensorFlow) on this dataset, and then serializing the face mask detector to disk 2.Deployment: Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as with_mask or without_mask
