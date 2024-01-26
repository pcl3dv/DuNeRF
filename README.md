<div align="center">

#  3D Reconstruction and New View Synthesis of Indoor Environments based on a Dual Neural Radiance Field
Zhenyu Bao<sup>1,2</sup> Guibiao Liao<sup>1,2</sup>, Zhongyuan Zhao<sup>1,2</sup>, Kanglin Liu<sup>2,* </sup>,  Qing Li<sup>2,*</sup> , Guoping Qiu<sup>3,4</sup>

<sup>1</sup>Peking University    <sup>2</sup>Pengcheng Laboratory    <sup>3</sup>University of Nottingham    <sup>4</sup>Shenzhen University

<sup>*</sup>corresponding author: max.liu.426@gmail.com, lqing900205@gmail.com

### [Paper]()

</div>

<img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/pipeline.png">

***Abstract**: Simultaneously achieving 3D reconstruction and new view synthesis for indoor environments has widespread applications but is technically very challenging. State-of-the-art methods based on implicit neural functions can achieve excellent 3D reconstruction results, but their performances on new view synthesis can be unsatisfactory. The exciting development of neural radiance field (NeRF) has revolutionized new view synthesis, however, NeRF-based models can fail to reconstruct clean geometric surfaces. %In this paper, 
We have developed a dual neural radiance field (Du-NeRF) to simultaneously achieve high-quality geometry reconstruction and view rendering. Du-NeRF contains two geometric fields, one derived from the SDF field to facilitate geometric reconstruction and the other derived from the density field to boost new view synthesis. One of the innovative features of Du-NeRF is that it decouples a view-independent component from the density field and uses it as a label to supervise the learning process of the SDF field. This reduces shape-radiance ambiguity and enables geometry and color to benefit from each other during the learning process. Extensive experiments demonstrate that Du-NeRF can significantly improve the performance of novel view synthesis and 3D reconstruction for indoor environments and it is particularly effective in constructing areas containing fine geometries that do not obey multi-view color consistency.    

Code is coming soon.

## Qualitative Result
<p float="left">
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig11.png" width="100" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig12.png" width="100" />
  <img src="https://github.com/pcl3dv/DuNeRF/blob/main/images/fig13.png" width="100" />

</p>




