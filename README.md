
# Real-Time-Gesture-Detection-Using-Convolutional-Neural-Network




### What is Convolutional Neural Network?


A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other.

### What is gesture recognition?

- The ability of a computer to understand gestures and execute commands based on those gestures.
- Gesture recognition is useful in processing information that cannot be conveyed through speech or text.
- This could be used to control computer input and detect sign language and for active gameplay.
- The implementation of this system mainly consists of 3 phases: Learning, Detection, Recognition


#### 1) Learning: 
It involves two aspects such as:

- **Training dataset:** This is the dataset that consists of different types of hand gestures that are used to train the system based on which the system performs the actions.  
- **Feature Extraction:** It involves determining the centroid that divides the image into two halves at its geometric Centre

#### 2) Detection: 
- **Capture scene:** Captures the images through a web camera, which is used as an input to the system.  
- **Preprocessing:** Images that are captured through the webcam are compared with the dataset to recognize the valid hand movements that are needed to perform the required actions.
- **Hand Detection:** The requirements for hand detection involve the input image from the webcam. The image should be fetched with a speed of 20 frames per second. Distance should also be maintained between the hand and the camera. The approximate distance that should be between hand the camera is around 30 to 100 cm. The video input is stored frame by frame into a matrix after preprocessing. 

#### 3) Recognition: 
It involves two aspects such as:
- **Gesture Recognition:** The number of fingers present in the hand gesture is determined by making use of defect points present in the gesture. The resultant gesture obtained is fed through a 3-Dimensional Convolutional Neural Network consecutively to recognize the current gesture.
- **Performing action:** The recognized gesture is used as an input to perform the actions required by the user.


## Implementation approach:

1) Make Detections
2) Capture Landmarks & Export to CSV
3) Train Custom Model Using Scikit Learn
- Read in Collected Data and Process
- Train Machine Learning Classification Model
- Evaluate and Serialize Model

4) Make Detections with Model





