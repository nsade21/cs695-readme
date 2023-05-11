# README

This repository contains code used for an E-cigarette Detection Android Application 

## Repositories Utilized in this Project
Indicate all code repositories you have referenced

Example:

This project is based on the code provided by TensorFlow Authors in the follwing repository
<a href="https://colab.research.google.com/github/googlecodelabs/odml-pathways/blob/main/object-detection/codelab2/python/Train_a_salad_detector_with_TFLite_Model_Maker.ipynb#scrollTo=Hm_UULdW7A9T">Train a salad detector with TFLite Model Maker
</a>

This project is based on the code provided by TensorFlower Gardener in the follwing repository
<a href="https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android">TensorFlow Lite Object Detection Android Demo
</a>

This project is based on the code provided by  Yi Zhou in the follwing repository
<a href="https://github.com/googlesamples/mlkit/tree/master/android/automl">ML Kit AutoML Remote Model Quickstart Sample App
</a>


## Project Structure
```
Repo Root
+-- e-cig-data.csv                                          # Contains training and testing data for e-cigs
+-- e_cig_detector_tflite_model_maker.py                    # Code to build object detection models
+-- app-debug.apk                                           # apk download to run on andriod -- device computation
+-- vision-automl-remote-model-quickstart-proguard.apk      # apk download to run on andriod -- server computation
+-- android                                                 # Code to build an E-cig detection app with on device computation 
    +-- app                                                 # Content of application 
            +-- build.gradle
            +-- src
                    +-- main
                            +-- assets
                                    +-- efficientdet-lite0.tflite                               # Object detection model
                                    +-- efficientdet-lite1.tflite                               # Object detection model
                                    +-- efficientdet-lite2.tflite                               # Object detection model
                                    +-- mobilenetv1.tflite                                      # Object detection model
                            +-- java/org/tensorflow/lite/examples/objectdetection
                                    +-- MainActivity.kt                                         # Code for main app
                                    +-- ObjectDetectorHelper.kt                                 # Code for object detection
                                    +-- OverlayView.kt                                          # Code for annotations
                                    +-- fragments
                                            +-- CameraFragment.kt                               # Code for camera 
                                            +-- PermissionsFragment.kt                          # Code for permissions
                                    +-- res                                                     # Files used for UI
                                  
    +-- build.gradle
    
+-- automl                                                  # Code to build an E-cig detection app with on server computation 
    +-- app                                             # Content of application 
            +-- build.grade
            +-- src/main                                   
                    +-- java                                # Java code to run backend
                        +-- res
       +-- build.gradle 
              
            
            
    
```

## Quick Start
Write down how to write your code

* 1
* 2
* 3

## Note
Any addional inforamtion you want to provide
