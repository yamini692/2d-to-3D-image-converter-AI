# AI-Powered Parallax Effect Generator (Simulated 3D Look)

This project uses an AI model (MiDaS) to create a **depth map** from a single image, and then applies a **parallax shift** to simulate a 3D-like effect.

## How It Works
1. Upload an image (JPEG or PNG format).
2. The MiDaS model predicts the depth map of the image.
3. The depth map guides pixel shifting to create a **parallax effect** (fake 3D look).
4. Outputs:
   - **Parallax Effect Image** (`parallax_effect.png`)
   - **Depth Map** (`depth_map.png`)

## Features
- **Automatic Depth Estimation** using MiDaS-small (fast version).
- **Parallax Creation** with customizable shift strength.
- **Easy Download** of generated results.
- **Visualization** of original image, depth map, and parallax image.

## Requirements
- Python
- PyTorch
- torchvision
- OpenCV (`opencv-python-headless`)
- PIL
- matplotlib
- google.colab

## Installation (already handled inside notebook)

pip install torch torchvision opencv-python-headless
