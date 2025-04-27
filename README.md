🖼️ Image Segmentation using Meta AI SAM Model

📝 Project Overview

This project explores the application of the Meta AI SAM (Segment Anything Model) for Image Segmentation tasks.

*What is Image Segmentation?*

Image Segmentation is a computer vision technique that divides an image into distinct regions or objects to simplify or change the image's representation, making it more meaningful and easier to analyze.
Instead of recognizing the entire image as a single unit (like in image classification), segmentation identifies and separates individual objects, boundaries, or regions within the image.

*There are two major types:*

1) Semantic Segmentation: Classifying each pixel into a category (e.g., sky, car, road).

2) Instance Segmentation: Identifying separate objects individually (e.g., two different people, two different cars).

✨ Use Cases of Image Segmentation:

-Medical imaging (detecting tumors)

-Autonomous driving (detecting roads, pedestrians)

-Satellite imagery analysis

-Photo editing (background removal, object cutout)

-Augmented Reality (AR) applications


*In this project:*

RESEARCH_PROJECT.ipynb: Demonstrates image segmentation using points and bounding boxes as prompts.

RP_phto_edit.ipynb: Creates segmentation masks and performs background removal.

Segmentation_Use_Case.ipynb: Extends segmentation results to a real-world problem-solving use case.

The project is designed in Google Colab, enabling users to easily explore and adapt it for their own research or applications.

🖼️ Important Note About Images

During execution, you will be required to upload your own images.

Alternatively, you can download sample images provided in the images/ folder of this repository.

Due to the nature of Google Colab (temporary storage), uploaded images will not persist after session ends.

👉 Please upload images into an images/ folder manually when running the notebooks.

📦 Technology Stack

-Python

-Google Colab

-PyTorch

-OpenCV

-NumPy

-Matplotlib

-torchvision

-Segment Anything Model (SAM) APIs


🔥 How to Run the Project

Clone or fork this repository:

!git clone https://github.com/GhogareS13/segmentation_model.git

        OR 

1) Open the .ipynb files in Google Colab using the provided badge or manually.

   - click on particular colab notebook

   - click "Open in Colab"


3) Upload necessary images (or use sample images from the images/ folder).

4) Run all code cells sequentially.

Follow instructions inside notebooks to see segmentation results and further outputs.

