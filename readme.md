# flux-model-colab

A Google Colab notebook for running local Stable Diffusion models with GPU acceleration.

## Overview

Load and run any Stable Diffusion-compatible model directly in Google Colab — no local GPU required. The notebook handles environment setup, model loading, and image generation in a few cells.

## Usage

1. Open `generate.ipynb` in Google Colab
2. Set runtime to **GPU** (`Runtime → Change runtime type → T4 GPU`)
3. Upload or mount your model to `/content/model`
4. Run all cells
5. Edit the `prompt` variable and get your result as `result.png`

## Requirements

- Google account with Colab access
- A Stable Diffusion model in diffusers format (placed at `/content/model`)
- Dependencies are installed automatically via `requirements.txt`

## License

MIT
