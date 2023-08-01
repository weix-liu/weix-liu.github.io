# Remote Sensing Image Vehicle Samples Synthesis
Our synthetic vehicle dataset GTAV10k and codes [DSCR](https://github.com/weix-liu/DSCR.git) are available.<br>
This project is for the paper "Unsupervised Domain Adaptation for Remote Sensing Vehicle Detection using Domain-specific Channel Recalibration".

# Remote Sensing Image Aircraft Samples Synthesis
This project is for the paper [Synthetic Data Augmentation Using Multiscale Attention CycleGAN for Aircraft Detection in Remote Sensing Images](https://ieeexplore.ieee.org/document/9337932).<br>

## Overview
<div  align="center">  
<img src="overview/synthetic generation.jpg" width = "600" height = "300" alt="图片名称" /><br>
<font size="2">Synthetic image generation by domain randomization. The 3D models are randomly placed on the background image (negative real image). By the use of various rendering factors, the system can generate a large volume of varied labeled data.</font>
</div>

## Examples
Here are examples of our synthetic images. Statistics of synthetic datasets see paper.
<br>
<div  align="center">    
<img src="examples/1573045866704.jpg" width = "200" height = "200" alt="" /><img src="examples/1573045867614.jpg" width = "200" height = "200" alt="" /><img src="/examples/1573045868634.jpg" width = "200" height = "200" alt="" />
</div>
<div  align="center">  
<img src="/examples/1573045869597.jpg" width = "200" height = "200" alt=""  /><img src="/examples/1573045870593.jpg" width = "200" height = "200" alt="" /><img src="examples/1573045872579.jpg" width = "200" height = "200" alt=""/>
</div><br>

## Download
Syn N 10k is for NWPU VHR-10, and Syn U 10k is for UCAS-AOD. Similar to PASCAL VOC style, every synthetic image (.jpg) has a corresponding annotation (.xml).
<br>
<br>
Google Drive:<br>
[Synthetic_N10k](https://drive.google.com/drive/folders/1X7W7dc7dhqpHmcWItIx9StQ7f1oTOcrA?usp=sharing).<br>
[Synthetic_U10k](https://drive.google.com/drive/folders/1dgxlk5-NQpn4pUIcdVgORY-wQvmvtSz6?usp=sharing).<br>
Weixing Liu, Jun Liu, Bin Luo<br>
LIESMARS, Wuhan University<br>

## Citation
If you use this dataset for your research, please cite our [paper](https://ieeexplore.ieee.org/document/9337932).<br>

## Acknowledgments
We collect 3D CAD data from [ShapeNet](https://www.shapenet.org/), background images from [NWPU VHR-10](https://ieeexplore.ieee.org/document/7560644) and [UCAS-AOD](https://ieeexplore.ieee.org/abstract/document/7351502).
