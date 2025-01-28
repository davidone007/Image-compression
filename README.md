# Image Compression with SVD

## Team Members
- **Davide Flamini Cazaran** - A00381665 - davidecazaran@gmail.com
- **Miguel Angel Martínez Vidal** - A00396327 - miguelangelmartines148@gmail.com
- **Andrés Felipe Cabezas Guerrero** - A00394772 - pipecabezas00@gmail.com
- **Nicolás Cuéllar Molina** - A00394970 - nicolascuellar.molina@gmail.com
- **Nicol vanessa Corral Valdivieso** - A00398767 - Nicolvanessa2126@gmail.com

## Project Overview
This project applies **Singular Value Decomposition (SVD)** for **image compression**, aiming to reduce file size while preserving visual quality. SVD decomposes an image's intensity matrix into three fundamental matrices, storing only essential data and removing redundancies.

## Features
- Compress grayscale and color images using SVD.
- Optimize storage and transmission without sacrificing image quality.
- Evaluate compression using metrics like SSIM and MSE.

## Installation
The required libraries are already installed in the Jupyter notebook, which is located in this repository. Simply open the Jupyter notebook, and all dependencies should be available for use. 

The Python program for image compression is also contained within the Jupyter notebook, making it easy to run directly from there.

## Usage
To compress an image, run the corresponding cell in the Jupyter notebook with the image path provided as an input. For example:

```python
compress_image("path_to_image")
```

