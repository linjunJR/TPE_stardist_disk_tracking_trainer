# StarDist Training and Logistics

A collection of Jupyter notebooks for training and managing StarDist models for object detection and segmentation.

## Overview

This repository contains tools and workflows for:
- **Training** StarDist models on custom datasets
- **Disk detection** through automated model training pipelines
- **Manual refinement** of predictions via an interactive GUI
- **Mask generation** for training data preparation

## Notebooks

- **`TRAINING_stardist_disk_finder.ipynb`** - Main training pipeline for StarDist disk detection models
- **`manual_refine_GUI.ipynb`** - Interactive GUI for manually refining and correcting model predictions
- **`mask_generator.ipynb`** - Utility for generating training masks from annotated data

## Requirements

- Python 3.x
- StarDist
- TensorFlow/PyTorch
- Jupyter Notebook
- OpenCV, NumPy, and other standard scientific Python packages

## Usage

1. Prepare your dataset with annotated images
2. Use `mask_generator.ipynb` to create training masks
3. Run `TRAINING_stardist_disk_finder.ipynb` to train your model
4. Use `manual_refine_GUI.ipynb` to review and refine predictions

## License

See LICENSE file for details.
