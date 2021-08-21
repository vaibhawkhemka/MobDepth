# MobDepth
High Quality Monocular Depth Estimation for Real-Time Applications via Transfer Learning

## About
Depth Estimation is one of the attractive research areas in computer vision. The motivation of this project is to estimate depth without the use of LIDAR sensors or any other related costly setups. And it also makes the robot more robust and efficient to carry out any task using the crucial depth information

## Results
Fig (1): Depth Map for without skip Connections <br/>
![MobDepthWithoutSkip](https://user-images.githubusercontent.com/46538042/130331305-1a4fd8c7-bf54-429a-8df0-fa4064896b1d.png)

Fig (2): Depth Map for with skip Connections <br/>
![MobDepthWithSkip](https://user-images.githubusercontent.com/46538042/130331214-d9e06745-baf9-47cd-a49c-557c2d83c5d2.png)

## Requirements

## Pre-Trained Models
[MobNetWithoutSkip](https://drive.google.com/drive/folders/13Vkp1CQaYYjbxj6eBiQNCXE0y6hMljyJ?usp=sharing) <br />
[MobNetWithSkip](https://drive.google.com/drive/folders/1xaGtZObUFWwlfGUQArCLCD_cYUL_3uzk?usp=sharing)
## Testing
`python3 test.py --model "mobnetwithskip.hdf5" --input "test.png"`
## Data

## Training

## Fine-Tuning

## Evaluation

## Update
* Training on kitti Dataset
* Preparation of Data
* try Demo.py 
