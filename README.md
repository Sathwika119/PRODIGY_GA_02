# PRODIGY_GA_02
Stable Diffusion Image Generation 
#Dependencies:
Make sure to install the following Python packages before running the notebook:

pip install diffusers
pip install transformers
pip install torch
pip install accelerate
pip install safetensors
#Model Used
Stable Diffusion v1.4: CompVis/stable-diffusion-v1-4

Also demonstrated: runwayml/stable-diffusion-v1-5

These models are pre-trained and loaded via the Hugging Face diffusers pipeline.

#Features
Generate stunning AI art from text prompts.

Support for GPU acceleration using CUDA.

Image generation with prompts like:

"A magical forest with glowing mushrooms"

"A futuristic cityscape at sunset, digital art"

"Forest with road"
#How to Use
Clone the repo or open the Colab notebook.

Install all dependencies.

Authenticate with Hugging Face (optional but recommended for private models).

Run the cells to:

Load the model

Set the device (CPU/GPU)

Generate and save images based on your prompts

#Output
Images are saved as .png files:

output.png

generated_image.png

These can also be viewed inline in the Colab notebook.

#Notes
Using GPU is highly recommended for faster generation (torch.cuda.is_available() is used to detect CUDA).

You can swap models or customize prompts as needed.

Hugging Face token (HF_TOKEN) is required for access to some models.

#Example Prompt Output
Prompt: "A futuristic cityscape at sunset, digital art"
Output: generated_image.png

#License
This project is for educational purposes. Refer to the respective model licenses on Hugging Face for usage terms.
