# Generate-3D-Mesh-from-2D-Image-using-Depth_Estimation

Welcome! This project focuses on converting 2D images into 3D mesh using Depth estimation models.

## Overview
This repository contains the code and resources necessary for the project. Here's a brief overview of what you'll find:

## Environment Setup and Library Installation
Before diving into the project, ensure you have the required environment set up and libraries installed. This includes PyTorch, Pillow, and Transformers, Open3D.

## Image Processing and Model Setup
The first stage involves pre-processing the input image and setting up the AI model for further processing. This step prepares the image and model for subsequent analysis.

Reference to the Model: https://huggingface.co/vinvino02/glpn-nyu

## Loading and Resizing Images
In this section, we load and resize the image to fit the model's requirements. This ensures compatibility and optimal performance during the reconstruction process.


I used the following image:


![Volvo (1)](https://github.com/Roshan-RB/Generate-3D-Mesh-from-2D-Image-using-Depth_Estimation/assets/62153742/cc116dfe-e4b4-4571-aaf1-3881fc71a041)


## Depth Estimation
Using the prepared model, we predict depth information from the loaded image. This step forms the foundation for generating a 3D representation of the image.

![Figure_1](https://github.com/Roshan-RB/Generate-3D-Mesh-from-2D-Image-using-Depth_Estimation/assets/62153742/cb7d28c0-3cd7-4c98-9c86-74238f81a02c)



## Point Cloud Generation
Based on the depth estimation, we generate a point cloud representation of the image. Point clouds provide a spatially accurate depiction of the scene captured in the image.


![WhatsApp Image 2024-04-06 at 17 52 07_9297d116](https://github.com/Roshan-RB/Generate-3D-Mesh-from-2D-Image-using-Depth_Estimation/assets/62153742/e29fed80-7e6f-42d2-9c86-5d66226299fd)

![WhatsApp Image 2024-04-07 at 10 28 47_ff4ad0bc](https://github.com/Roshan-RB/Generate-3D-Mesh-from-2D-Image-using-Depth_Estimation/assets/62153742/f209586e-97c0-49fa-8a52-cd7c3bdfa10b)


## 3D Point Cloud Analysis and Post-Processing
After generating the point cloud, we analyze and post-process the data to refine the representation further. This step enhances the quality and accuracy of the reconstruction.

## 3D Modelling: Point Cloud to Mesh Conversion
The point cloud is converted into a mesh representation, which forms the basis for creating a solid 3D model. Meshes provide a more structured and visually appealing representation of the scene.



## Usage
To use this repository, follow these steps:

Clone the repository to your local machine.
Set up the environment by installing the required libraries.
Run the provided code files to execute each stage of the project.
## Resources
Tutorial Video: https://www.youtube.com/watch?v=5ypQIUbpA7c&t=1594s


This project was developed following the step-by-step instructions provided in the YouTube tutorial by Florent Poux

## Credits
Tutorial Creator: Florent Poux
