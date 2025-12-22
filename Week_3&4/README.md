**Welcome to Week 3**

***Problem Statement***

Students are required to develop a deep learning–based system that can automatically segment brain tumors from MRI scans. Using the BraTS dataset, which provides multi-modal MRI volumes and corresponding ground-truth segmentation masks, students must preprocess the data by loading MRI files, converting 3D volumes into 2D slices, normalizing and resizing the images, and preparing paired input–mask datasets.

Students must then implement a U-Net segmentation model using either TensorFlow/Keras or Pytorch, train the model on the prepared data, and evaluate its performance using metrics such as Dice Score and Intersection over Union (IoU). The final output should include the trained model, quantitative evaluation results, and visualizations comparing predicted segmentation masks with the ground-truth masks.

Link to the dataset: [BRaTS 2021 Dataset](https://www.kaggle.com/datasets/dschettler8845/brats-2021-task1)

The theory guide for the project can be found here: [Theory Guide](https://docs.google.com/document/d/1_FPFWqnD06kb9QH93hEePEFe_FTZRMp1MgsGIDm8nDc/edit?tab=t.0#heading=h.kxvpgxpt58uh)

