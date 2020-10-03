# Remote Sensing Image Aircraft Samples Synthesis
This project is for the paper [Can Synthetic Data Improve Object Detection Results for Remote Sensing Images?](https://arxiv.org/abs/2006.05015).<br>

## Overview
<div  align="center">  
<img src="overview/synthetic generation.jpg" width = "600" height = "300" alt="图片名称" /><br>
Synthetic image generation by domain randomization. The 3D models are randomly placed on the background image (negative real image). By the use of various rendering factors, the system can generate a large volume of varied labeled data.
</div>

## Examples
Here is the example of our synthetic images. Statistics of synthetic datasets see paper.
<br>
<div  align="center">    
<img src="examples/1573045866704.jpg" width = "200" height = "200" alt="图片名称" /><img src="examples/1573045867614.jpg" width = "200" height = "200" alt="图片名称" /><img src="/examples/1573045868634.jpg" width = "200" height = "200" alt="图片名称" r />
</div>
<div  align="center">  
<img src="/examples/1573045869597.jpg" width = "200" height = "200" alt="图片名称"  /><img src="/examples/1573045870593.jpg" width = "200" height = "200" alt="图片名称" /><img src="examples/1573045872579.jpg" width = "200" height = "200" alt="图片名称"/>
</div><br>

## Download (will come soon)
Syn N 10k is for NWPU VHR-10, and Syn U 10k is for UCAS-AOD. Similar to PASCAL VOC style, every synthetic image (.jpg) has a corresponding annotation (.xml).<br>
Google Drive: [Synthetic_datasets](https://weix-liu.github.io/).<br>
Weixing Liu, Jun Liu, Bin Luo<br>
LIESMARS, Wuhan University<br>

## Citation
If you use this dataset for your research, please cite our [paper](https://arxiv.org/abs/2006.05015).<br>

## Acknowledgments
We collect 3D CAD data from [ShapeNet](https://www.shapenet.org/), background images from [NWPU VHR-10](https://ieeexplore.ieee.org/document/7560644) and [UCAS-AOD](https://ieeexplore.ieee.org/abstract/document/7351502).
