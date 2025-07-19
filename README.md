# Text-to-Image Using Stable Diffusion

This project is a simple web application that generates images from text prompts using the Stable Diffusion model. The interface is built with Gradio, allowing users to enter a prompt and receive a generated image in real time.

## Features

- Generate images from any text prompt using Stable Diffusion.
- User-friendly web interface with custom styling.
- Easily restart and generate new images with different prompts.

## Requirements

- Python 3.7+
- torch
- torchvision
- torchaudio
- diffusers
- gradio
- pillow

All dependencies can be installed using the following commands (also included in the notebook):

```python
!pip install torch torchvision torchaudio
!pip install diffusers
!pip install gradio
!pip install pillow
```

## Usage

1. Open the `texttoImage.ipynb` notebook.
2. Run all cells to install dependencies, load the model, and launch the Gradio interface.
3. Click **Start** in the web interface, enter your text prompt, and click **Generate Image** to see the result.
4. Use **Return & Enter New Prompt** to generate more images.

## Model

- Uses the [CompVis/stable-diffusion-v1-4](https://huggingface.co/CompVis/stable-diffusion-v1-4) model from Hugging Face.

## License

This project is for educational purposes. Please check the licenses of the models and libraries used.

---

**Author:** Vanapriya Alaparthy