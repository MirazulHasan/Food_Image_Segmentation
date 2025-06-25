## Food Image Binary Segmentation with UNET and MobileNet
This project implements a binary segmentation model to detect the presence of food in images. The model combines the strengths of UNET and MobileNet for efficient and accurate segmentation.

# Dataset
Images: 50 food-related images curated for this project.

Annotations: Binary masks were manually created using Photoshop to label areas containing food.

# Model Architecture
Backbone: MobileNet serves as the lightweight feature extractor, providing efficiency and flexibility.

Segmentation Head: UNET architecture is employed to output binary segmentation masks.

# Workflow
Data Preparation:

Images were manually masked to distinguish food regions (foreground) from non-food regions (background).

Preprocessing steps include resizing, normalization, and augmentation.

# Model Training:

The UNET-MobileNet architecture was trained to produce binary masks indicating the presence of food.

# Evaluation:

Performance metrics such as accuracy, IoU (Intersection over Union), and Dice Coefficient were used to validate the model.

# Features
Binary Segmentation: Detects whether food is present in an image with pixel-level accuracy.

Manual Annotations: High-quality ground truth masks created with Photoshop.

Lightweight Design: Utilizes MobileNet for efficient inference on resource-constrained devices.

# Applications
Useful for automated food identification systems.

Can serve as a foundation for further classification or calorie estimation systems.

Explore the repository to see the code, training details, and segmented results in action!

