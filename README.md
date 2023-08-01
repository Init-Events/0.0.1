# Init Event 0.0.1

## Step 1 - Start Download Models from HugginFace

 - Visit OpenJourney's [Hugging Face](https://huggingface.co/prompthero/openjourney/tree/main)
 - Download the file `mdjrny-v4.safetensors`
 - Visit Stable Diffusion's [Huggin Face](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main)
 - Download the file `sd_xl_base_1.0.safetensors`
 - Visit Stable Diffusion Refiner's [Hugging Face](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/tree/main)
 - Download the file `sd_xl_refiner_1.0.safetensors`

## Step 1 - Install Python

  - **For Mac**: You should have `python3` installed, nothing else to do
    - To make sure its running corrently run `python3 --version` and `pip3 --version`
  - **For PC**: Visit the [Python Website](https://www.python.org/downloads/windows/)
  - **For Linux**: If you are running linux, you probably know better than us what you are doing. 


## Step 2 - Install Python Deps

  - Visit [PyTorch](https://pytorch.org/get-started/locally/) to get the right dependecies for your set up
  - Run the following command
  ```
    pip install diffusers transformers omegaconf accelerate safetensors invisible-watermark
  ```