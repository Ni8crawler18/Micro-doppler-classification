# Micro-Doppler based Target classification using SVM

## Overview

The project implements a Support Vector Machine (SVM) classifier to differentiate between drones and birds based on micro-Doppler spectrograms. The spectrograms, generated using MATLAB, are provided as input in PNG format. The workflow involves converting the spectrograms to grayscale, normalizing the grayscale images, and feeding them into a linear SVM classifier for classification.

## Features

-SVM Classification: Linear SVC classifier trained on grayscale spectrograms.
-Image Processing: Conversion to grayscale and normalization of input images.
-User Interface: A Tkinter-based GUI for easy interaction and real-time classification.
-GitHub Pages Deployment: The Tkinter UI is available via GitHub Pages.