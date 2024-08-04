<div align="center">

<h1> DuNeRF </h1>
<h2> 3D Reconstruction and New View Synthesis of Indoor Environments based on a Dual Neural Radiance Field </h2> 

<div>
    Zhenyu Bao<sup>1</sup>&emsp;
    Guibiao Liao<sup>1</sup>&emsp;
    Zhongyuan Zhao<sup>1</sup>&emsp;
    Kanglin Liu<sup>2, *</sup>&emsp;
    Qing Li<sup>2, *</sup>&emsp;
    Guoping Qiu<sup>3</sup>
</div>

<div>
    <sup>1</sup>Peking University&emsp;
    <sup>2</sup>Pengcheng Laboratory&emsp;
    <sup>3</sup>University of Nottingham
</div>

<div>
    ACMMM '24
</div>

### [Paper](https://doi.org/10.48550/arXiv.2401.14726) | Project | Video



<img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/pipeline.png">

***Abstract**: Simultaneously achieving 3D reconstruction and new view synthesis for indoor environments has widespread applications but is technically very challenging. State-of-the-art methods based on implicit neural functions can achieve excellent 3D reconstruction results, but their performances on new view synthesis can be unsatisfactory. The exciting development of neural radiance field (NeRF) has revolutionized new view synthesis, however, NeRF-based models can fail to reconstruct clean geometric surfaces. We have developed a dual neural radiance field (Du-NeRF) to simultaneously achieve high-quality geometry reconstruction and view rendering. Du-NeRF contains two geometric fields, one derived from the SDF field to facilitate geometric reconstruction and the other derived from the density field to boost new view synthesis. One of the innovative features of Du-NeRF is that it decouples a view-independent component from the density field and uses it as a label to supervise the learning process of the SDF field. This reduces shape-radiance ambiguity and enables geometry and color to benefit from each other during the learning process. Extensive experiments demonstrate that Du-NeRF can significantly improve the performance of novel view synthesis and 3D reconstruction for indoor environments and it is particularly effective in constructing areas containing fine geometries that do not obey multi-view color consistency.    

Code is coming soon.

## Qualitative Result
Ours results on Scannet.
<p align="middle">
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig01.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig02.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig03.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig04.png" width="24%" />
</p>

The decoupled colour in our Du-NeRF.
<p align="middle">
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig11.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig12.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig13.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig14.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig31.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig32.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig33.png" width="24%" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig34.png" width="24%" />
</p>

## Citation
Cite as below if you find this repository is helpful to your project:
```
@article{bao20243d,
  title={3D Reconstruction and New View Synthesis of Indoor Environments based on a Dual Neural Radiance Field},
  author={Bao, Zhenyu and Liao, Guibiao and Zhao, Zhongyuan and Liu, Kanglin and Li, Qing and Qiu, Guoping},
  journal={arXiv preprint arXiv:2401.14726},
  year={2024}
}
```
