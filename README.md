# Hand Gesture recognition with OpenCV and MediaPipe

This example showcases the utilization of landmarks identified by the MediaPipe library for training a gesture recognition model. Upon running the 
    `python train.py` script, 
,a webcam input is displayed, and users can generate training data by pressing a key between 0 and 9 while performing specific hand gestures. For instance, pressing key 0 captures training data for the 'Open hand' gesture. Users can create diversified datasets by moving their hand before releasing the key. The process is repeated for other gestures such as 'Thumb Up' (1), 'OK' (2), and 'Peace' (3). Following the data generation, the classify_gestures.ipynb Jupyter notebook is used to create and train a neural network, with the default setting being four classes. Users have the flexibility to modify the number of classes, ensuring that corresponding training data is provided. Once the training and classification steps are complete, the detect_gesture.py script can be employed to test the trained model, displaying predictions in the top left corner. Enjoy the training process and exploring gesture recognition capabilities.

# Recognition

Utility functions for landmark processing for csv storage and baseline for deep learning model taken from [Nikita Kiselov](https://github.com/kinivi) in [this repo](https://github.com/kinivi/hand-gesture-recognition-mediapipe) in turn translated from [this repo by Kazuhito Takahashi](https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe)
