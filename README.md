# Brain Tumor Segmentation

This repository contains a project focused on the segmentation of brain tumors from MRI images using a U-Net deep learning architecture. The U-Net model is specifically designed for biomedical image segmentation tasks and has been fine-tuned to accurately detect and segment tumors in brain scans.

![image](https://github.com/user-attachments/assets/899433fb-7e62-428b-8938-bdf5c47fcdac)


## Overview

Brain tumor segmentation is a critical task in medical image analysis, aiming to distinguish tumor tissue from normal brain structures in MRI scans. Accurate segmentation assists in diagnosis, treatment planning, and monitoring disease progression.

## Repository Contents

- **Unet/**: Directory containing the implementation of the U-Net model.
- **MV_Project_Code1.ipynb**: Jupyter Notebook detailing the initial experiments and model training processes.
- **MV_Project_Code2.ipynb**: Jupyter Notebook with subsequent experiments and refinements.
- **Unet_MV_mini-project.ipynb**: Jupyter Notebook summarizing the mini-project's objectives, methods, and results.
- **unet_mv_mini_project.py**: Python script for training and evaluating the U-Net model.

## Getting Started

To utilize the code in this repository, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Vanshdalal314/Brain-Tumor-Segmentation.git
   ```

2. **Install the required dependencies**:

   Ensure you have Python installed, then install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the dataset**:

   - Obtain a dataset of brain MRI images with corresponding segmentation masks.
   - Organize the data into appropriate directories for training and testing.

4. **Train the model**:

   Execute the training script or run the Jupyter Notebook to train the U-Net model on your dataset.

5. **Evaluate the model**:

   After training, assess the model's performance using evaluation metrics such as Dice coefficient and Hausdorff distance.

## References

- **U-Net: Convolutional Networks for Biomedical Image Segmentation**: The foundational paper introducing the U-Net architecture.
- **Brain Tumor Segmentation**: Overview of brain tumor segmentation tasks and datasets. 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the contributors and the open-source community for their invaluable resources and support. 
