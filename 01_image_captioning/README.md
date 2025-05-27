# 🧠 Project 01: Image Captioning App using Generative AI

This project is part of the [IBM Course: Building Generative AI-Powered Applications with Python].  
It demonstrates how to use a vision-language foundation model to automatically generate descriptive captions for images.

## 📌 Project Summary

The app allows users to upload an image, and it responds with a natural-language caption that describes the contents of the image.

It leverages the **BLIP (Bootstrapping Language-Image Pretraining)** model to generate human-like captions, and provides a simple web interface using **Gradio**.

## 🚀 Technologies Used

- Python
- Hugging Face Transformers
- BLIP model (`Salesforce/blip-image-captioning-base`)
- Gradio (for web UI)
- Pillow (for image handling)

## 🖼️ Demo Flow

1. User uploads or drags-and-drops an image.
2. The BLIP model processes the image and generates a caption.
3. The caption is displayed as output in the web interface.

## ▶️ How to Run

### 1. Install dependencies:

```bash
pip install -r requirements.txt

2. Run the app: python image_captioning_app.py
