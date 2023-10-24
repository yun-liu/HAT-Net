## [Vision Transformers with Hierarchical Attention](https://arxiv.org/abs/2106.03180)

First titled as "Transformer in Convolutional Neural Networks".


### Installation

This repository exactly follows the code and the training settings of [PVT](https://github.com/whai362/PVT).


### Image classification on the ImageNet-1K dataset

|     Methods     |   Size    | #Params | #FLOPs | Acc@1 |  Pretrained Models  |
|-----------------|:---------:|:-------:|:------:|:-----:|:-------------------:|
|  HAT-Net-Tiny   | 224 x 224 |  12.7M  |  2.0G  |  79.8 | [Google](https://drive.google.com/file/d/1iuhOCEMhEqJlCJKk--Qk1w6TcxP_Plgf/view?usp=sharing) / [Github](https://github.com/yun-liu/HAT-Net/releases/download/v2.0/HAT-Net_Tiny.pth) |
|  HAT-Net-Small  | 224 x 224 |  25.7M  |  4.3G  |  82.6 | [Google](https://drive.google.com/file/d/1lfVT_nCndVAPikAivigl72Ne5XKjfkCp/view?usp=sharing) / [Github](https://github.com/yun-liu/HAT-Net/releases/download/v2.0/HAT-Net_Small.pth) |
|  HAT-Net-Medium | 224 x 224 |  42.9M  |  8.3G  |  84.0 | [Google](https://drive.google.com/file/d/1fWITg1Cfm0qDaYw7xhfF8pXdbhK5ctHY/view?usp=sharing) / [Github](https://github.com/yun-liu/HAT-Net/releases/download/v2.0/HAT-Net_Medium.pth) |
|  HAT-Net-Large  | 224 x 224 |  63.1M  |  11.5G |  84.2 | [Google](https://drive.google.com/file/d/1MPNd86S_BvtPDrH_h39vjjvN12opsMki/view?usp=sharing) / [Github](https://github.com/yun-liu/HAT-Net/releases/download/v2.0/HAT-Net_Large.pth) |

### Citation

If you are using the code/models provided here in a publication, please consider citing:

    @article{liu2021vision,
      title={Vision Transformers with Hierarchical Attention},
      author={Liu, Yun and Wu, Yu-Huan and Sun, Guolei and Zhang, Le and Chhatkuli, Ajad and Van Gool, Luc},
      journal={arXiv preprint arXiv:2106.03180},
      year={2021}
    }
