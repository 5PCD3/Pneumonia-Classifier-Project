# Pneumonia Classifier Project

## Overview

This project is an image classification tool that utilizes a pre-trained deep learning model to classify chest X-ray images into two categories: pneumonia or non-pneumonia. The user interface is built using Streamlit, providing a straightforward process for users to upload an image and receive a rapid classification result.

## Features

- **User-Friendly Interface:** The application offers a simple and intuitive interface for users to upload chest X-ray images.
- **Background Image:** The application dynamically sets the background to an image related to the project theme for an enhanced visual experience.
- **Classification Results:** After uploading an image, the application displays the uploaded image and provides the predicted class (pneumonia or non-pneumonia) along with a confidence score.

## How to Use

1. Ensure you have the required dependencies installed. You can install them using the following command:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the `main.py` file using the following command:

    ```bash
    streamlit run main.py
    ```

3. Open the provided Streamlit URL in your web browser.

4. Upload a chest X-ray image using the file uploader.

5. View the uploaded image and see the classification result along with the confidence score.

## Project Structure

- **main.py:** The main application file containing the Streamlit UI and the integration with the pre-trained classification model.
- **util.py:** A utility file with functions for setting the background image and classifying images using the pre-trained model.
- **model/:** Directory containing the pre-trained pneumonia classification model (`pneumonia_classifier.h5`) and the class labels (`labels.txt`).
- **bgs/:** Directory containing background images for the application.

## Requirements

- numpy
- streamlit
- Pillow
- keras
- tensorflow

## Acknowledgments

The classification model used in this project is based on deep learning techniques and was trained on a dataset of chest X-ray images. The project structure and code were inspired by best practices in machine learning application development.

Feel free to explore, modify, and contribute to this project!
