
# Gesture Recognition Case Study using Neural Networks

![hand_gesture](https://github.com/pragya2611/Neural_Network_Model_Building_for_Gesture_Recognition/assets/20012925/48a24836-85af-4fd8-af16-ddf0a84d4f8d)


## Problem Statement

As a data scientist at a home electronics company which manufactures state of the art smart televisions, you want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

* Thumbs up:  Increase the volume
* Thumbs down: Decrease the volume
* Left swipe: 'Jump' backwards 10 seconds
* Right swipe: 'Jump' forward 10 seconds 
* Stop: Pause the movie

Each video is a sequence of 30 frames (or images)

## Understanding the Dataset

The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 

## Objectives

Generator: The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

Model: Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

Write up: This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model.

## Conclusion

## Learnings



## Acknowledgements

Below are some of the references that helped me build these experiment with all sets of models

    1. https://towardsdatascience.com/step-by-step-implementation-3d-convolutional-neural-network-in-keras-12efbdd7b130

    2. https://www.sciencedirect.com/science/article/pii/S2351978920304571

    3. https://machinelearningmastery.com/rectified-linear-activation-function-for-deep-learning-neural-networks/

    4. https://www.javatpoint.com/recurrent-neural-network-in-tensorflow

    5. https://www.youtube.com/watch?v=bD05uGo_sVI- Generators Explained
