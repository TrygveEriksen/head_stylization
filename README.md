# Digital humans project - TEAM 3

## Quick Start

1. Clone the repository:

   ```bash
   git clone https://github.com/TrygveEriksen/head_stylization
   cd head_stylization
   ```

2. Initialize and update submodules:

   ```bash
   git submodule update --init --recursive
   ```

3. Follow the quick start guides in each submodule for environment setup and usage:

   - `PanoHead/README.md`
   - `3d_head_stylization/README.md`

   Each submodule contains its own conda environment instructions and usage examples.

## Pretrained Models

Download the stylized generator checkpoints from the links below:

Panohead stylized generator checkpoints: [Panohead Link](https://drive.google.com/drive/folders/1m517-F1NCTGA159dePs5R5qj02svtX1_)


Diffusion model for 3d_head_stylization: [Diffusion Link](https://huggingface.co/SG161222/Realistic_Vision_V5.1_noVAE)

Oil painting, pixar and cyberpunk stylized generator checkpoints: [Pretrained Link](https://drive.google.com/drive/folders/1rBiPeaMAQGfZ_o6OkdxJVbiLvj-geV4t)


Place the downloaded checkpoints somewhere in the `3d_head_stylization/` directory and give the correct paths as arguments when running the scripts.

## Dataset preparation

See `PanoHead/3DDFA_V2_cropping/cropping_guide.md` for instructions on how to prepare the dataset for Task 1 - 4.

## Running tasks
For each of the tasks, follow the instructions in the respective submodule's README to set up the environment and run the code. Task 1 - 3 are in `PanoHead/`, while Task 4 is in `3d_head_stylization/`.
