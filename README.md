# Brain Tumor MRI Detection Project

Welcome! We are Alex, Reese, and Kristina, college students studying abroad in Copenhagen, Denmark. This project involves a neural network we trained to predict whether a brain tumor is present in an MRI image. You can upload an MRI image to see the prediction in action.

---

## Project Structure

The repository contains the following files and folders:

- **`data/`**  
  The original dataset used for training and testing. This folder contains MRI images categorized by the presence or absence of tumors.

- **`data_aug/`**  
  A folder for storing augmented images during preprocessing. Make sure to use this folder when working with the data augmentation notebook (see the note below).

- **`mri_website/`**  
  The web application for uploading MRI images and viewing predictions.

- **`mri_project_TL_resNet.ipynb`**  
  A notebook demonstrating transfer learning using ResNet for tumor classification.

- **`mri_project_baseline_accuracy.ipynb`**  
  A notebook documenting the baseline accuracy achieved using a simple model.

- **`mri_project_data_aug.ipynb`**  
  A notebook that implements data augmentation techniques to improve the model’s robustness.

- **`mri_project_finalCNN.ipynb`**  
  The final Convolutional Neural Network (CNN) model that achieved optimal performance in detecting brain tumors.

- **`mri_project_simpleModel.ipynb`**  
  A notebook with a basic neural network implementation for comparison.

---

## Running the Project

### Environment Setup

Ensure you have the necessary Python libraries installed. These include but are not limited to:

- TensorFlow/Keras
- NumPy
- Matplotlib

You can install these dependencies using pip:

```bash
pip install tensorflow numpy matplotlib
