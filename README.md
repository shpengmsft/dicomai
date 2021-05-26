# DICOM Multi-Class classifier training and evaluation

1. Create a Azure MachineLearning (AML) workspace with required resource
    - Compute Instance
    - Compute Cluster (GPU compute)
    - File Dataset for DICOM images

3. Clone the project repository
4. Download config.json from AML workspace portal and save to notebooks folder
5. Upload and run following Notebook
    - fhl_dicom_image_converter.ipynb
    - fhl_dicom_multiclass_create_labeled_dataset.ipynb
    - fhl_dicom_multiclass_automl.ipynb
