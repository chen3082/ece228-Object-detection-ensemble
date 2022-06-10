# ece228-Object-detection-ensemble
A comprehensive study for object detection model ensemble
### requirement
  numpy==1.21.1
  
  torch==1.9.0+cu111
  
  torchmetrics==0.8.2
  
  torchsummary==1.5.1
  
  torchvision==0.10.0+cu111
  
  Pillow==8.3.1
  
  wandb==0.21.7
  
  pprintpp==0.4.0
  
  Need to install pycocotools from coco website
  https://cocodataset.org/#home
  
  And downlaod the dataset from Penn-Fundan dataset website
  https://www.cis.upenn.edu/~jshi/ped_html/
  
### 1. Download the dataset  
The dataset is available here: https://www.cis.upenn.edu/~jshi/ped_html/
Then, execute the following commands.
```
# unzip dataset
unzip PennFudanPed.zip
```
### 2. Training
Run the following file depending on your purpose.
### To run bagging:
  baggingRun.ipynb
### To run ensemble algorithm for different backbone and different architecture:
  ensemble_algorithm.ipynb
### To run Data augmentation:
  augment_exp.ipynb
### To run Test time augmentation:
  augment_exp.ipynb
