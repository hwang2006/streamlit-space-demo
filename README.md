---
sdk: streamlit
sdk_version: 1.41.1 # The latest supported version
---

# Hot Dog Classifier Demo

This repository contains a demo application for classifying images as "hot dog" or "not hot dog" using the Hugging Face Gradio SDK. The application is deployed to Hugging Face Spaces using GitHub Actions.

## Overview

The Hot Dog Classifier Demo uses a pre-trained image classification model from the Hugging Face Transformers library. The application allows users to upload an image and receive a classification result indicating whether the image is of a hot dog or not.

## Features

- Upload an image for classification.
- Receive a prediction with probabilities for "hot dog" and "not hot dog".
- Deployed to Hugging Face Spaces using GitHub Actions for continuous integration and deployment.
