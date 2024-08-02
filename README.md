# Traffic-Accident-Video-Action-Classification

## Research on deep learning-based methods for determining negligence through traffic accident video analysis 

## Environments
- CUDA 11.6
- Pytorch
- MMEngine 0.10.4
- [MMAction2](https://mmaction2.readthedocs.io/en/latest/)

## Method
- Finetuned [TSN](https://yjxiong.me/others/tsn/) model in AI HUb dataset.
  - [pretrained model](https://download.openmmlab.com/mmaction/v1.0/recognition/tsn/tsn_imagenet-pretrained-r50_8xb32-1x1x3-100e_kinetics400-rgb/tsn_imagenet-pretrained-r50_8xb32-1x1x3-100e_kinetics400-rgb_20220906-cd10898e.pth)
  - [config file](https://github.com/open-mmlab/mmaction2/blob/main/configs/recognition/tsn/tsn_imagenet-pretrained-r50_8xb32-1x1x3-100e_kinetics400-rgb.py)

## Dataset
- [AI Hub traffic accident video dataset](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=597)
![image](https://github.com/user-attachments/assets/a1da6a50-a616-4dbc-b2e1-8f7b88109d51)

## Result 
- 4 places (parking lot, road and road others, roundabouts, t-intersection)
- 3 type classification (a object progress direction, b object progress direction, place feature)
- [Checkpoint & Logging File link](https://drive.google.com/drive/folders/1yU2Jr_1IXt5r4VChFsLlN3jazAZtTBKy?usp=drive_link)

## Todo
- [ ] add code
