# Crop Row Detection

Computer-vision prototype for detecting crop rows in agricultural imagery using **Python and PyTorch**.

The project implements a semantic-segmentation style neural network with a pretrained **ResNet-18 encoder**, custom upsampling blocks and feature-pyramid components to identify row structures in field imagery.

## Why this project matters

Crop-row detection can support agricultural image analysis, field monitoring and downstream spatial or agronomic workflows by transforming raw imagery into structured visual information.

## Technical highlights

- Python
- PyTorch / Torchvision
- Deep learning for computer vision
- Pretrained ResNet-18 feature encoder
- Custom encoder-decoder / U-Net-style architecture
- Feature Pyramid Network components
- Image segmentation workflow

## Repository contents

- `model.py` — neural-network architecture
- `crop_row.ipynb` — experimentation / analysis notebook
- `model.pt` — trained model artifact
- `dataset/` — project dataset
- `test/` — example results

## Example detections

![Crop row detection example](test/test.png)

![Crop row detection example](test/test1.png)

![Crop row detection example](test/test2.png)

## Context

This repository reflects my broader work at the intersection of **AI, remote sensing, geospatial analytics and agriculture**.
