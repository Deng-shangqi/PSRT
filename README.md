# PSRT
Code for the paper: "PSRT: Pyramid Shuffle-and-Reshuffle Transformer for Multispectral and Hyperspectral Image Fusion"
### Plateform
Python 3.8.5 + Pytorch 1.11.0
______

### Pretrained models
The pretrained checkpoints list in the .\pretrained model\
______

### Source training && testing codes
main_x4.py: The training function of our PSRT.

eval_x4.py: The testing function of our PSRT.

model_SR.py: The network of our PSRT.

______
### Data
The simulation of our data refers to [1] and [2].

Complete training and test data download link:
1. <https://pan.baidu.com/s/1SLR0QKVyMWOOuYIYgcNv_Q?pwd=7ja6>
______

### Bib reference
If you find this code helpful, please kindly cite:

@ARTICLE{dengtgrs2023,
author={Shang-Qi Deng, Liang-Jian Deng, Xiao Wu, Ran Ran, Danfeng Hong, Gemine Vivone },
journal={ IEEE Transactions on Geoscience and Remote Sensing },
title={ PSRT: Pyramid Shuffle-and-Reshuffle Transformer for Multispectral and Hyperspectral Image Fusion },
year={2023},
volume={14},
number={},
pages={},
doi={ 10.1109/TGRS.2023.3244750 }
   }


[1] Akhtar, Naveed, Faisal Shafait, and Ajmal Mian. "Sparse Spatio-spectral Representation for Hyperspectral Image Super-Resolution." ECCV, 2014. 63-78.
[2] N. Yokoya, C. Grohnfeldt, and J. Chanussot, "Hyperspectral and multispectral data fusion: a comparative review of the recent literature," IEEE Geoscience and Remote Sensing Magazine, vol.5, no. 2, pp. 29-56, June 2017.
