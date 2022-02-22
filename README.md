
# Attention based CNN for semantic segmentation of remote sensing images 

Semantic segmentation of high resolution aerial imagery is an important problem which aims to assign a categorical label to each pixel. In the recent years, fully convolution neural network has become one of the most widely used techniques for solving such task. This project aims to improve the semantic segmentation performance by utilizing attention module and incorporating it inside a semantic segmentation network. The proposed model uses attention module inside a residual UNet architecture. Our proposed model reaches 91.36 % overall accuracy for ISPRS Vaihingen dataset and 92.41 % overall accuracy for ISPRS Potsdam dataset. Our proposed model was compared with some other state of the art models and experimental results clearly show it outperforms all other state of the art models for our task.




# Dataset

Our model was trained on ISPRS Vaihingen and ISPRS Potsdam dataset. We used IRRG images and also NDSM images from the ISPRS websites and the composite IRRG-NDSM images reached the highest accuracy for our segmentation purpose. All the datasets can be downloaded from following website.

https://www.isprs.org/education/benchmarks/UrbanSemLab/default.aspx


# How to start 

Find the right version for your setup and install PyTorch.

Just run the RAUnet_ISPRS_Potsdam_4channel(Record benchmark result).ipynb file for Potsdam dataset and RAUnet_ISPRS_Vaihingen_4channel-GCP_final result.ipynb for Vaihingen dataset from jupyter notebook.



# License 

Code (scripts and Jupyter notebooks) are released under the GPLv3 license for non-commercial and research purposes only. For commercial purposes, please contact the authors.

