# ece228-Object-Detection-Ensemble
A comprehensive study for object detection model ensemble
## Requirements
Our .ipynb were tested in the following environment.

  numpy==1.21.1
  
  torch==1.9.0+cu111
  
  torchmetrics==0.8.2
  
  torchsummary==1.5.1
  
  torchvision==0.10.0+cu111
  
  Pillow==8.3.1
  
  pprintpp==0.4.0
  
  If you want to generate the figures we show in the report, please register an account here: <br>
  https://wandb.ai/site
  
  and get the requirement: <br>
  wandb==0.21.7
  
  Need to install pycocotools from coco website <br>
  https://cocodataset.org/#home
  
  or execute the command:
  ```pip install pycocotools```

  
### 1. Download the dataset  
Download the dataset from Penn-Fundan dataset website:  <br>
https://www.cis.upenn.edu/~jshi/ped_html/ <br><br>
Then, execute the following command.
```
# unzip dataset
unzip PennFudanPed.zip
```
### 2. Training
Run the following file depending on your purpose.

> To run bagging experiment:<br>
  ```baggingRun.ipynb```<br>
  
> To run ensemble algorithm for different backbone and different architecture: <br>
  ```ensemble_algorithm.ipynb```<br>
  
> To run Data augmentation:<br>
  ```augment_exp.ipynb```<br>

Experiment different transformation methods: comment out different lines in cell 2 of  ```augment_exp.ipynb```.
  
> To run Test-time augmentation:<br>
  ```augment_exp.ipynb```<br>

