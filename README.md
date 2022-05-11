# Deep-Learning-Project2
## 1 Date set
We use  image data of Natural Scenes around the world from Kaggle. This Data contains around 17k images of size 150x150 distributed under 6 categories: o represents buildings; 1 represents forest; 2 represents glacier; 3 represents mountain; 4 represents sea; 5 represents street. There are around 14k images in Train, 3k in Test. This data was initially published by Intel to host a Image classification Challenge. The dataset can be downoad from https://www.kaggle.com/datasets/puneet6060/intel-image-classification?resource=download.
Use !kaggle datasets download -d puneet6060/intel-image-classification to download this dataset.
Use loader.py to load training and test data.
## 2 Using non-pretrained models
### 2.1 ResNet50
The model definition is in resnet50.py, and the trained model parameters is in project2_Res50_final_smalldataset.pt
### 2.2 ViT
The model definition is in vit.py, and the trained model parameters is in project2_VitBase_final_smalldataset.pt
### 2.3 SPT+LSA+ViT
The model definition is in slvit.py, and the trained model parameters is in project2_SLVit_final_smalldataset.pt
### 2.4 SPT+LSA+ViT
The model definition is in traintest.py, and the trained model parameters is in project2_ResVit_final_smalldataset.pt
## 3 Using pretrained models
### 3.1 ImageNet-1K pretraining ResNet50
The model definition is in resnet50_image1k_pretraining.py, and the trained model parameters is in project2_pretrained_Res50_image1k_final_smalldataset.pt
### 3.2 ImageNet-1K pretraining ViT
The model definition is in vit_image1k_pretraining.py, and the trained model parameters is in project2_pretrained_ViT_image1k_final_smalldataset.pt
### 3.3 ImageNet-21K pretraining ResNet50
The model definition is in resnet50_image21k_pretraining.py (we use resnet50_miil_21k.pth to get ImageNet-21K pretraining ResNet50 model), and the trained model parameters is in project2_pretrained_Res50_image21k_final_smalldataset.pt
### 3.4 ImageNet-21K pretraining ViT
The model definition is in vit_image21k_pretraining.py, and the trained model parameters is in project2_pretrained_ViT_image21k_final_smalldataset.pt
## 4 pt files
pt files and the image data sets are in Google Drive https://drive.google.com/drive/folders/1NPhnDNp3wzMgKASbUZaT2VOsVFkbT3z0?usp=sharing because of their large size
