%%writefile README.md
# Task-02: Image Generation with Pre-trained Models

## Objective
The objective of this task is to generate images from natural language text prompts using a pre-trained generative AI model. This task demonstrates how modern generative models can convert textual descriptions into realistic images without training a model from scratch.

## Tools Used
- Python
- Google Colab
- Stable Diffusion
- Hugging Face Diffusers
- PyTorch

 
## Implementation Steps
1. Environment Setup
Google Colab was used as the development environment.
GPU acceleration was enabled to improve performance.

2. Library Installation
Required libraries such as diffusers, transformers, torch, and accelerate were installed.

3. Model Loading
The pre-trained Stable Diffusion model was loaded using the StableDiffusionPipeline class from the Diffusers library and moved to the GPU for faster execution.

4. Text Prompt Input
A natural language prompt describing the desired image was provided to the model.

Example:
"A beautiful sunset over mountains, realistic style"

5. Image Generation
The model processed the text prompt and generated an image based on the given description.

6. Output Saving
The generated image was saved locally and downloaded for submission.

## Description
This project demonstrates text-to-image generation using Stable Diffusion without training a model from scratch.

