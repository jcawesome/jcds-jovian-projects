# Landscape Image Classification using Convolutional Neural Networks
## Introduction
In this notebook, I will try and use different techniques I have learned from the **Deep Learning with PyTorch: Zero to GANs** course.

I have chosen the `Intel Image Classification` dataset as part of a previous competition:

> https://www.kaggle.com/puneet6060/intel-image-classification

## Business Case
**Context:** The data contains images of different natural scenes around the world.
This data was initially published on https://datahack.analyticsvidhya.com by Intel to host a Image classification Challenge.

**Problem:** Multi Class Image Classification

The notebook is divided into different sections:
* Import Libraries
* Data Loading, Exploration and Manipulation
* Defining the Model
* Training the Model
* Model Verification
* Summary

## Summary
* The final model (Resnet9) wsa able to predict with an accuracy of more than 90%. I'm glad to have tried at least 2 models when building this final course project.

## Future Improvements
In order to improve this notebook (using the Intel image classification dataset), I have listed down a couple of suggestions for those who want to pick up where I left of (this includes my future self):
* Use Transfer Learning (i.e. Resnet34, VGG Imagenet)
* Use a different batch size and tweak some of the parameters (i.e. DataLoader parameters) to improve the speed of each run
* Try out other models (Ensemble Neural Networks)
* Figure out how to run multiple models and load them into the same GPU. Currently encountering this error after running one of the models. Current solution is to restart runtime
> RuntimeError: CUDA out of memory. Tried to allocate 2.00 GiB (GPU 0; 14.73 GiB total capacity; 9.82 GiB already allocated; 1.05 GiB free; 12.74 GiB reserved in total by PyTorch)


