# Deep-Learning-Project2
## 1 Date set
We use  image data of Natural Scenes around the world from Kaggle. This Data contains around 25k images of size 150x150 distributed under 6 categories: o represents buildings; 1 represents forest; 2 represents glacier; 3 represents mountain; 4 represents sea; 5 represents street. There are around 14k images in Train, 3k in Test and 7k in Prediction. This data was initially published on https://datahack.analyticsvidhya.com}{datahack.analyticsvidhya by Intel to host a Image classification Challenge.
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
## 3 
