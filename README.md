# APS360-Symbol-Identification
Group: 07 in LEC01 for APS 360

## Project Goal
Take images of mathematical notes (Greek symbols, math notation, numbers, words, arrows, etc.) and transcribe them automatically into LaTeX. 

## Overview
Using deep learning trained on an augmented version of the HASYv2 dataset, the team was able to create a model that can operate on 348 unique symbols with a final test accuracy of 92.85%. The final model was a version of ResNet implemented with 18 layers in Pytorch.

## Contents of Repository

### Main_Model_Iterations
This notebook contains the final ResNet model implementation, testing, and results. It also includes several model architectures and hyperparameter settings that were attempted and modified along the path to implementing this final ResNet-18 model.

### Model_Implementation
This notebook contains the code and results for our pure out-of-sample testing along with the code for the project's demo.

### R_CNN_Model_Implementation
This notebook contains the code for another path of inquiry in the project that implemented a region-based CNN (i.e. R-CNN).

### SVM_Baseline_Model
This notebook contains the implementation of the team's baseline model for this project, which was in the form of a Support Vector Machine.

### Transfer_Learning_Models 
This notebook contains the code for another path of inquiry for the project that implemented models via transfer learning.
