

# Stable Diffusion Image Generator

This project allows you to generate images from textual descriptions using the Stable Diffusion model. It utilizes Hugging Face's `diffusers` library to create high-quality images based on user input text. The model can run on both GPU (CUDA) and CPU environments, ensuring accessibility for different setups.

## Features

- **Text-to-Image Generation:** Enter a text prompt, and the model generates a corresponding image.
- **CUDA & CPU Support:** Automatically detects the system's hardware and runs the model accordingly.
- **Easy to Use:** Just input a description, and get your image!

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/PrajaktaDhule/stable-diffusion-image-generator.git
   cd stable-diffusion-image-generator
   
2.  Install the required dependencies:
      ```bash
    pip install -r requirements.txt

3.Ensure you have the diffusers library installed and access to a Hugging Face API key. You can sign up for an API key at Hugging Face.

## Usage

1. Run the script to generate images:
   ```bash
   python generate_image.py
## Example

```bash
Enter the description for the image: baby in the garden


## Acknowledgments

- This project utilizes the [Hugging Face Diffusers library](https://github.com/huggingface/diffusers) and the Stable Diffusion model.
- Special thanks to the Hugging Face community for providing these amazing resources.




![Alt Text](path/to/image)
