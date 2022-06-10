# ece228-Object-detection-ensemble
A comprehensive study for object detection model ensemble
## Requirements
Our .ipynb were tested in the following environment.

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

  
### 1. Download the dataset  
Download the dataset from Penn-Fundan dataset website: https://www.cis.upenn.edu/~jshi/ped_html/ <br>
Then, execute the following command.
```
# unzip dataset
unzip PennFudanPed.zip
```
### 2. Training
Run the following file depending on your purpose.

> To run bagging:<br>
  baggingRun.ipynb<br>
  
> To run ensemble algorithm for different backbone and different architecture: <br>
  ensemble_algorithm.ipynb<br>
  
> To run Data augmentation:<br>
  augment_exp.ipynb<br>
> To run Test-time augmentation:<br>
  augment_exp.ipynb<br>

