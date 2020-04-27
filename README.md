# drowsiness-detection

The proposed model detects and sounds an alarm when the driver is on the verge of falling asleep. This is done by monitoring the person’s face with a  camera and when his/her eyes shut close for more than a few seconds, a blaring alarm is sounded, bringing the driver back to their consciousness. This project uses OpenCV for detecting the ROI from the driver's face, Keras backed with Tensorflow to build the classification model and Pygame for the alarm.

For a more technical look into the model, we use OpenCV for gathering the images from the webcam. A Region of Interest (ROI) is identified, which in our case is the eyes and it is fed into a deep learning model. Here, we use Convolutional Neural Networks (CNN) that consists of several layers which performs extremely well for image classification purposes.
