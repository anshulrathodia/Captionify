# Image-Caption-Generator

## Overview

This project is an Image Caption Generator built using TensorFlow, leveraging VGG16 for image feature extraction and LSTM for generating precise captions. The model integrates CNN and LSTM through feature concatenation to predict subsequent words in captions, achieving a BLEU score of 0.535, indicating effective caption generation close to human reference captions. The application is deployed using Streamlit for an interactive web interface.

<img width="401" alt="250158178-ab509878-94ba-4318-a3e2-ca50baa47630" src="https://github.com/anshulrathodia/Image-Caption-Generator/assets/155772558/516af9bd-bcfb-4556-b4b3-b4d5c28411ce">

## Features

- **Image Feature Extraction**: Utilizes VGG16, a pre-trained Convolutional Neural Network (CNN), to extract high-level image features.
- **Caption Generation**: Uses a Long Short-Term Memory (LSTM) network to generate captions based on the extracted features.
- **Feature Concatenation**: Integrates CNN and LSTM through feature concatenation to enhance caption accuracy.
- **Performance**: Achieved a BLEU score of 0.535, showcasing the model's capability in generating human-like captions.
- **Deployment**: Deployed on Streamlit for easy access and user-friendly interaction.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/image-caption-generator.git
    cd image-caption-generator
    ```

2. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Download the pre-trained models**:
   - Ensure you have the VGG16 model and the trained LSTM model.
   - Place these models in the appropriate directory as specified in the code.

4. **Run the Streamlit application**:
    ```sh
    streamlit run app.py
    ```

## Usage

1. **Upload an Image**: Click the 'Browse files' button to upload an image.
2. **Generate Caption**: Click the 'Generate Caption' button to get the caption for the uploaded image.
3. **View Results**: The generated caption will be displayed below the image.

## Model Details

- **VGG16**: A convolutional neural network model used for extracting high-level features from images.
- **LSTM**: A type of recurrent neural network (RNN) capable of learning order dependence in sequence prediction problems.
- **Feature Concatenation**: Combines image features and textual features to predict the next word in the caption sequence.

## Evaluation

The model's performance is evaluated using the BLEU score, which measures the similarity between the generated captions and human reference captions. Our model achieved a BLEU score of 0.535, indicating a high level of accuracy and relevance in generated captions.

## Deployment

The application is deployed using Streamlit, providing an interactive web interface for users to upload images and generate captions.

