# Init Event 0.0.1

## Step 1 - Start Download Models from HugginFace

 - Visit OpenJourney's [Hugging Face](https://huggingface.co/prompthero/openjourney/tree/main)
 - Download the file `mdjrny-v4.safetensors`
 - Visit Stable Diffusion's [Hugging Face](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main)
 - Download the file `sd_xl_base_1.0.safetensors`
 - Visit Stable Diffusion Refiner's [Hugging Face](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/tree/main)
 - Download the file `sd_xl_refiner_1.0.safetensors`
 - Visit Stable Diffusion VAE or fp16VAE [Whole](https://huggingface.co/stabilityai/sdxl-vae) [fp16](https://huggingface.co/madebyollin/sdxl-vae-fp16-fix)
 - Download the file `sdxl_vae.safetensors`

## Step 2 - Install Python

  - **For Mac**: You should have `python3` installed
    - To make sure its running corrently run `python3 --version` and `pip3 --version`
    - If that does not work, make sure you have [homebrew](https://brew.sh/) installed
    - Then install python >= 3.9
  - **For PC**: Visit the [Python Website](https://www.python.org/downloads/windows/)
    - Download, and make sure both python and pip are on PATH
  - **For Linux**: If you are running linux, you probably know what you are doing. 


## Step 3 - Install Python Deps

  - Visit [PyTorch](https://pytorch.org/get-started/locally/) to get the right dependecies for your set up
  - Run the following command
  ```
    pip install diffusers transformers omegaconf accelerate safetensors invisible-watermark
  ```