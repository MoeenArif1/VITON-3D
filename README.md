# Virtual Try on System with Realistic 3D Avatar

Welcome to the repository for my Final Year Project! This project focuses on studying existing Virtual Try-On (VTON) and 3D generation models and leveraging them to develop a 3D VTON system. Specifically, this implementation utilizes Pasta GAN++ and Magic123 models for achieving realistic virtual try-on experiences.

## Project Documentation

- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/PDF_file_icon.svg/15px-PDF_file_icon.svg.png">  [Final Year Project Paper](https://github.com/MoeenArif1/VITON-3D/blob/main/fyp-%20paper.pdf) - This document provides a detailed description, methodology, and analysis of the project, including insights into the VTON approach and the models used.

## Notebooks

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MoeenArif1/VITON-3D/blob/main/VTON_3D.ipynb)

Click the badge above to open the project notebook in Google Colab. This notebook guides through the implementation of the 3D VTON system using default datasets.

## Getting Started

To begin experimenting with the project, follow these steps in the provided Colab notebook:

1. **Copy Networks Data:**
   
    - Copy data from the link into the VITON-3D Folder.
      [![Google Drive 🔗](https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Google_Drive_logo.png/15px-Google_Drive_logo.png)
](https://drive.google.com/drive/folders/10P9sW_bVoIEL9qZKjWIhf4ja0BsEXtKA)

3. **Default Dataset Execution:**
   - Open the Colab notebook by clicking on the badge above.
   - Follow the instructions within the notebook to execute the system with the default dataset.

4. **Using Your Own Data:**
   - Prepare your images by resizing them to 320x512 pixels and saving them as PNG files with a white background.
   - Place your custom images in the directory `DATA/custom_input/image`.
   - Update the `test_pairs` configuration in the `custom_input` folder to match your custom dataset.

   Example structure after setup:
   
   DATA/custom_input/image/your_image1.png
   DATA/custom_input/image/your_image2.png
   DATA/custom_input/test_pairs



## Project Outputs

### 2D Output
![2D Output](https://github.com/MoeenArif1/VITON-3D/blob/main/DATA/output/stored___input.png)

The above image demonstrates a sample 2D output from the system. This output showcases the virtual try-on of clothing items based on the provided input image.



