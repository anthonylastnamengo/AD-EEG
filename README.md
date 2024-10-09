# Early Dementia Detection using EEG Signals and Deep Learning

## Overview

This project aims to develop a non-invasive, affordable, and accurate method for detecting early-stage dementia and Alzheimer's disease in elderly patients. By using Fast Fourier-transformed (FFT) EEG signals combined with a deep learning classification network, we seek to identify subtle changes in brain activity that could be indicative of dementia, offering an alternative to invasive and costly MRI scans.

We aim to process MRI data from an EEG headset, namely the Neurosity Crown, and output a patient's risk factor from a classification deep learning network.

## Table of Contents

- [Overview](#overview)
- [Motivation](#motivation)
- [Features](#features)
- [Referenced Works](referenced-works)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Motivation

Dementia is the second leading cause of death in Australia, with Alzheimer's being the most common form of dementia. Early detection is crucial, yet the current diagnostic process often relies on costly and invasive scans that are not always accessible or accurate in detecting early-stage symptoms.

This project seeks to create a non-invasive solution using EEG signals to detect early symptoms of dementia, allowing for timely intervention and improving the quality of life for both patients and caregivers.

## Features

The repository aims to explore multiple avenues of classification models to determine which model is best suited for this task. 

### 1) Random Forest
- **FFT and Deep Learning**: Applies Fast Fourier Transform (FFT) on raw EEG signals and uses a neural network to classify dementia-related patterns.
- **Random Forest**: Using a group of decision trees in a Random Forest Classifier, the model will be able to distinguish and analyse patterns that can pinpoint dementia in patient EEG scans.

### 2) Transformer Model
- **Transformer Self-Attention**: Experimenting with applying the self-attention property towards time-series EEG data to extrapolate meaningful patterns and draw conclusions

## Referenced Works

The initial idea was inspired by another project of mine, using the GFNet architecture to detect Alzheimer's in MRI scans. I wanted to look for an alternative, more simple method, so I began researching about potentially using EEG signals instead, eventually finding this paper: 
https://www.frontiersin.org/journals/aging-neuroscience/articles/10.3389/fnagi.2023.1288295/full

The transformer architecture for EEG data was implemented with the following papers:
https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1148855/full
https://www.sciencedirect.com/science/article/pii/S1746809423007516

