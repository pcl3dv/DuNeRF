<div align="center">

<h1> DuNeRF (ACMMM '24)

<span style="font-size: 12px;"> 3D Reconstruction and New View Synthesis of Indoor Environments based on a Dual Neural Radiance Field </span>

</h1>
 

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
    <sup>* </sup>corresponding author
</div>

### [Paper](https://doi.org/10.48550/arXiv.2401.14726) | Project | Video

</div>

<br>

<img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/teaser.png">

## About DuNeRF

We have developed a dual neural radiance field (Du-NeRF) to simultaneously achieve high-quality geometry reconstruction and view rendering. Du-NeRF contains two geometric fields, one derived from the SDF field to facilitate geometric reconstruction and the other derived from the density field to boost new view synthesis. One of the innovative features of Du-NeRF is that it decouples a view-independent component from the density field and uses it as a label to supervise the learning process of the SDF field. This reduces shape-radiance ambiguity and enables geometry and color to benefit from each other during the learning process.

<br>

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
