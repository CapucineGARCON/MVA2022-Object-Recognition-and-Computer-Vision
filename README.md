# MVA2022-Object-Recognition-and-Computer-Vision
## Object Detection and Tracking with DiffusionDet

Codebase studying Diffusion models for object detection and multi-object tracking based on [Chen & al.](https://arxiv.org/abs/2211.09788), for a school project in the Object Recognition and Computer Vision Course (I. LAPTEV, J. PONCE, C. SCHMID, J. SIVIC) at Master 2 MVA in Ecole Normale Superieure Paris-Saclay. 

We studied DiffusionDet which is a diffusion model for object detection. Specifically, we reproduced the results of the author on MS-COCO dataset and compared DiffusionDet performances with Faster R-CNN. The main goal was to extend the use of Diffusion model to Multi-Object Tracking. We implemented a centroid-based tracker on top of the DiffusionDet model. 





https://user-images.githubusercontent.com/58911531/211219166-84071751-63b4-4e2b-901c-52cd6bfd2f86.mp4

This tracking video was obtained with the tracker we have built. 



### Authors

- Noémie BERGUES ([github](https://github.com/noemiebergues))

- Capucine GARÇON ([github](https://github.com/CapucineGARCON))

### Datasets

We have used the [MS-COCO dataset]() for our object detection experiments and the [MOT17 dataset]() for our Multi-Object Tracking experiments.


### Bibliography

#### Reference article

Chen & al., *DiffusionDet : Diffusion Model for Object Detection* ([arxiv](https://arxiv.org/abs/2211.09788))

```
@misc{https://doi.org/10.48550/arxiv.2211.09788,
  doi = {10.48550/ARXIV.2211.09788},
  
  url = {https://arxiv.org/abs/2211.09788},
  
  author = {Chen, Shoufa and Sun, Peize and Song, Yibing and Luo, Ping},
  
  keywords = {Computer Vision and Pattern Recognition (cs.CV), FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {DiffusionDet: Diffusion Model for Object Detection},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {Creative Commons Attribution 4.0 International}
}

```

