# CorrNet
This project provides the code and results for 'Lightweight Salient Object Detection in Optical Remote Sensing Images via Feature Correlation', IEEE TGRS, vol. 60, pp. 1-12, 2022. [IEEE link](https://ieeexplore.ieee.org/document/9690514) and [arxiv link](https://arxiv.org/abs/2201.08049) [Homepage](https://mathlee.github.io/)

# Network Architecture
   <div align=center>
   <img src="https://github.com/MathLee/CorrNet/blob/main/image/CorrNet.png">
   </div>
   
# Accuracy v.s. Parameters
   <div align=center>
   <img src=https://github.com/MathLee/CorrNet/blob/main/image/accuracyVSparams.png width=52% />
   </div> 
   
   
# Requirements
   python 2.7 + pytorch 0.4.0 or
   
   python 3.7 + pytorch 1.9.0


# Saliency maps
   We provide saliency maps and [measure results (.mat)](https://pan.baidu.com/s/19dG5CghVZ31NSw49bd63Dw) (code: m1dm) of [all compared methods](https://pan.baidu.com/s/1JoLznx_AvAHvCA7BU9hqfQ) (code: kftm) and [our CorrNet](https://pan.baidu.com/s/1rLaFSywXmZ7LuI_1o1poBg) (code: fbee) (or under './saliencymap/') on ORSSD and EORSSD datasets.
   
   In addition, we also provide saliency maps of our CorrNet on the recently published [ORSI-4199](https://github.com/wchao1213/ORSI-SOD) dataset under './saliencymap/'.
   
   ![Image](https://github.com/MathLee/CorrNet/blob/main/image/table.png)
   
# Training

Modify paths of [VGG backbone](https://pan.baidu.com/s/1YQxKZ-y2C4EsqrgKNI7qrw) (code: ego5) in /model/vgg.py and datasets, then run train_CorrNet.py.


# Pre-trained model and testing
Download the following pre-trained model, and modify paths of pre-trained model and datasets, then run test_CorrNet.py.

We also uploaded these pre-trained models in /models.

[ORSSD](https://pan.baidu.com/s/1rmBvxXjDh8KRL98CoFUl0g) (code: vqi7)

[EORSSD](https://pan.baidu.com/s/1FVF9x8f-PvVVgeDSAvJcbA) (code: q5mr)

[ORSI-4199](https://pan.baidu.com/s/1VcG-OX1Hi8T1_XOnZwgKBA) (code: va3b)

   
# Evaluation Tool
   You can use the [evaluation tool (MATLAB version)](https://github.com/MathLee/MatlabEvaluationTools) to evaluate the above saliency maps.


# [ORSI-SOD_Summary](https://github.com/MathLee/ORSI-SOD_Summary)
   
# Citation
        @ARTICLE{Li_2022_CorrNet,
                author = {Gongyang Li and Zhi Liu and Zhen Bai and Weisi Lin and Haibin Ling},
                title = {Lightweight Salient Object Detection in Optical Remote Sensing Images via Feature Correlation},
                journal = {IEEE Transactions on Geoscience and Remote Sensing},
                volume = {60},
                pages = {1-12},
                year = {2022},
                }
                
                
If you encounter any problems with the code, want to report bugs, etc.

Please contact me at lllmiemie@163.com or ligongyang@shu.edu.cn.
