# Brain Tumor Segmentation

This is a simple web application that uses a pre-trained model to segment brain tumors from MRI images. The model is based on the U-Net architecture. This application is built using Streamlit and TensorFlow.

## Classification Data Acquisition

The data used for classification is the Brain MRI Images for Brain Tumor Detection dataset from Kaggle (Masoud Nickparvar’s Brain Tumor MRI). The dataset contains 7023 human brain MRI images divided into 4 classes:

- Glioma
- Meningioma
- Pituitary
- No Tumor

## Segmentation Data Acquisition

The data used for segmentation is the Segmented MRI Images from Nikhil Tomar’s Brain Tumor Segmentation Kaggle Dataset. The dataset contains 3064 human brain MRI images divided into 3 classes with masks of the tumor region:

- Glioma
- Meningioma
- Pituitary

## References

- [Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- [Segmented MRI Images](https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation)