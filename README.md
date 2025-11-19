<h2 align="center">
<img src="assets/images/logo.png" width="35%" align="center"> 
<br/>
<small>A Multimodal Generative Framework for Sewing Pattern Design and Generic Garment Modeling</small>
</h2>
<p align="center"><a href="https://arxiv.org/abs/2504.01483"><img src='https://img.shields.io/badge/arXiv-Paper-red?logo=arxiv&logoColor=white' alt='arXiv'></a>
<a href='https://style3d.github.io/garmagenet'><img src='https://img.shields.io/badge/Project_Page-Website-green?logo=googlechrome&logoColor=white' alt='Project Page'></a>
<a href='https://huggingface.co/datasets/Style3D/GarmageSet'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Dataset-blue'></a>
</p>
<p align="center"><img src="assets/images/teaser.png" width="100%"></p>


> We introduce **GarmageNet**, a unified generative framework that automates the creation of 2D sewing patterns, the construction of sewing relationships, and the synthesis of 3D garment initializations compatible with physics-based simulation. Central to our approach is **Garmage**, a novel garment representation that encodes each panel as a structured geometry image, effectively bridging the semantic and geometric gap between 2D structural patterns and 3D garment geometries. Followed by **GarmageNet**, a latent diffusion transformer to synthesize panel-wise geometry images and **GarmageJigsaw**, a neural module for predicting point-to-point sewing connections along panel contours. 


## Updates

**[November 18, 2025]** First release of [GarmageSet](https://huggingface.co/datasets/Style3D/GarmageSet) dataset 🥳

## Citation

If you find this work useful, please cite:

```bibtex
@article{li2025garmagenet,
  title     = {{GarmageNet}: A Multimodal Generative Framework for Sewing Pattern Design and Generic Garment Modeling},
  author    = {Li, Siran and Liu, Ruiyang and Liu, Chen and Wang, Zhendong and 
               He, Gaofeng and Li, Yong-Lu and Jin, Xiaogang and Wang, Huamin},    
  address   = {New York, NY, USA},
  articleno = {216},
  doi       = {10.1145/3763271},
  issue_date= {December 2025},
  journal   = {ACM Trans. Graph. (SIGGRAPH Asia)},
  keywords  = {garment modeling, garment dataset, diffusion Generation},
  month     = {December},
  number    = {6},
  numpages  = {23},
  publisher = {Association for Computing Machinery},
  url       = {https://doi.org/10.1145/3763271},
  volume    = {44},
  year      = {2025}
}
```

