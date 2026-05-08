# AI Image Captioning System

This project is a Deep Learning model designed to bridge the gap between **Computer Vision** and **Natural Language Processing**. It takes an image as input and generates a grammatically correct English sentence describing the scene.

## Features
- **Automatic Caption Generation:** Creates human-like descriptions for uploaded images.
- **Interactive UI:** Built with **Gradio** for a seamless, user-friendly web interface.
- **Deep Learning Architecture:** Uses an Encoder-Decoder framework.

##  Model Architecture
The system utilizes a hybrid architecture:
1. **Encoder (CNN):** A pre-trained **ResNet50** model (Transfer Learning) to extract high-level visual features from the images.
2. **Decoder (RNN):** A **Long Short-Term Memory (LSTM)** network to process the features and generate a sequence of words (the caption).

##  Tech Stack
- **Language:** Python
- **Deep Learning:** TensorFlow / Keras
- **Image Processing:** OpenCV / PIL
- **Interface:** Gradio
- **Environment:** Kaggle / Jupyter Notebooks

##  Dataset
The model was trained/fine-tuned on the **Flickr 8k Dataset**, which contains 8,000 images, each paired with five different descriptive captions.

##  How to use
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook or the Python script to launch the Gradio interface.
4. Upload an image and see the AI-generated caption in real-time!
