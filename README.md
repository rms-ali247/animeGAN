# AnimeGAN

**AnimeGAN** is a Generative Adversarial Network (GAN) project designed to generate realistic anime-style faces. This project is part of an assignment titled **"This Anime Face Does Not Exist" GAN** and includes a trained generator model, sample generated images, and the code used for training and inference.

## Live Demo

Check out a live demo of the model on [Hugging Face Spaces](https://huggingface.co/spaces/raosaeedali/animeGAN).

## Project Structure

animeGAN/ ├── generated images/ # Directory containing generated anime face images ├── model.keras # Pretrained GAN model ├── project.ipynb # Jupyter Notebook for training and inference └── README.md # This file


## How It Works

- **Generator Model:** The core of the GAN that creates new anime faces from random noise.
- **Inference Notebook:** The Jupyter Notebook (`project.ipynb`) contains code for loading the pretrained model, generating random noise, and producing anime faces.
- **Training Details:**  
  The model was trained on an **NVIDIA RTX A4000 GPU**, which significantly improved training times and performance.

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- (Optional) OpenCV (for additional image processing tasks)

## Setup & Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/animeGAN.git
   cd animeGAN
   
2. **Activate the Virtual Environment:**
   ```bash
   env\Scripts\activate


Usage
Generating Anime Faces:
Open the project.ipynb notebook and run the cells to load the pretrained generator model and generate new anime faces.

Viewing Generated Images:
The generated images will be saved in the generated images/ folder.

Acknowledgments
The code and explanations in this repository have been refined with the assistance of AI-powered platforms such as ChatGPT, DeepSeek, and Gemini.
