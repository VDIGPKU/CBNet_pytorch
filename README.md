# CBNet: A Novel Composite Backbone Network Architecture for Object Detection

by Yudong Liu

## Introduction

We have released our code at https://github.com/PKUbahuangliuhe/CBNet implemented by caffe2. Since [Detectron](https://github.com/facebookresearch/Detectron) code will not be maintained, we release our implementation based on [mmdetection](https://github.com/open-mmlab/mmdetection)

Please follow [mmdetection](https://github.com/open-mmlab/mmdetection) on how to install the environment.


## Citation

If you use our code/model/data, please cite our paper:
https://aaai.org/Papers/AAAI/2020GB/AAAI-LiuY.1833.pdf

Our code is free for research, but needs authorization for commerce.


### Faster R-CNN

|    Backbone     |  Style  | Lr schd | Mem (GB) | Train time (s/iter) | Inf time (fps) | box AP |                                                              Download                                                              |
| :-------------: | :-----: | :-----: | :------: | :-----------------: | :------------: | :----: | :--------------------------------------------------------------------------------------------------------------------------------: |
|     R-50-C4     |  caffe  |   1x    |    -     |          -          |      9.5       |  34.9  |      [model](https://s3.ap-northeast-2.amazonaws.com/open-mmlab/mmdetection/models/faster_rcnn_r50_caffe_c4_1x-75ecfdfa.pth)       |
|     R-50-C4     |  caffe  |   2x    |   4.0    |        0.39         |      9.3       |  36.5  |      [model](https://s3.ap-northeast-2.amazonaws.com/open-mmlab/mmdetection/models/faster_rcnn_r50_caffe_c4_2x-71c67f27.pth)       |
|     R-50-C4     | pytorch |   1x    |    -     |          -          |      9.3       |  33.9  |         [model](https://s3.ap-northeast-2.amazonaws.com/open-mmlab/mmdetection/models/faster_rcnn_r50_c4_1x-642cf91f.pth)          |
|     R-50-C4     | pytorch |   2x    |    -     |          -          |      9.4       |  35.9  |         [model](https://s3.ap-northeast-2.amazonaws.com/open-mmlab/mmdetection/models/faster_rcnn_r50_c4_2x-6e4fdf4f.pth)          |
