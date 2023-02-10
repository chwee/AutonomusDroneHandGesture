# AutonomusDroneHandGesture

This is a sample program which allows users to control an Airsim drone using hand gestures.


This repository contains the following contents:

- Sample program
- Airsim gesture control interface
- Hand sign recognition model(TFLite)
- Finger gesture recognition model(TFLite)
- Learning data for hand sign recognition and notebook for learning
- Learning data for finger gesture recognition and notebook for learning

# Demo

Here's how to run the sample program

```
gesture_contoller.py
```

When your webcam is turned on, you can use gesture to control the Airsim Drone

# Directory


```
│  gesture_controller.py
│  airsim_controller.py
│  KeyController.py
│  keypoint_classification.ipynb
│  keypoint_classification_EN.ipynb
│  point_history_classification.ipynb
│  
├─model
│  ├─keypoint_classifier
│  │  │  keypoint.csv
│  │  │  keypoint_classifier.hdf5
│  │  │  keypoint_classifier.py
│  │  │  keypoint_classifier.tflite
│  │  └─ keypoint_classifier_label.csv
│  │          
│  └─point_history_classifier
│      │  point_history.csv
│      │  point_history_classifier.hdf5
│      │  point_history_classifier.py
│      │  point_history_classifier.tflite
│      └─ point_history_classifier_label.csv
│          
└─utils
│   └─cvfpscalc.py
│
└─airsim_functions
│   └─orbit.py
│
└─requirements.txt

```


