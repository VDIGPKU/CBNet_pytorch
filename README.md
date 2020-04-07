# CBNet: A Novel Composite Backbone Network Architecture for Object Detection

by Yudong Liu

## Introduction

We have released our code at https://github.com/PKUbahuangliuhe/CBNet implemented by caffe2. Since [Detectron](https://github.com/facebookresearch/Detectron) code will not be maintained, we release our implementation based on [mmdetection](https://github.com/open-mmlab/mmdetection)

Please follow [mmdetection](https://github.com/open-mmlab/mmdetection) on how to install the environment.

You need to convert the original backbone to cbnet version with python convert_db.py or python convert_tb.py.


## Citation

If you use our code/model/data, please cite our paper:
https://aaai.org/Papers/AAAI/2020GB/AAAI-LiuY.1833.pdf

Our code is free for research, but needs authorization for commerce.


### Detection results on COCO val2017

|  Baseline |   Backbone          | box AP |                 
| :-------------: | :-----: | :-----: |
|     FPN   |   ResNext-101-32-4d     |  40.1  |
|     FPN   |   Dual-ResNext-32-4d  | 41.5  |
|     FPN   |   Triple-ResNext-32-4d  | 42.0  |
|     FPN   |   Dual-ResNext-32-4d(CBNetv2)  | 43.2  |
|Cascade R-CNN(with DCN and multi-scale training)| Dual-Res2Net101(CBNetv2)|52.5 |
