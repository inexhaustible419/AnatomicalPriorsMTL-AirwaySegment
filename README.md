<div align="center">



https://github.com/user-attachments/assets/925a49b5-bc13-4c4d-a586-a649256337f3




</div>


# A Connectivity-Enhanced Multi-Task Learning based on Anatomical Priors for 3D Class-Balanced Pulmonary Airway Segmentation
[![Framework: Python](https://img.shields.io/badge/Framework-PyTorch-orange.svg)](https://pytorch.org/)
[![License](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)

A 3D airway segmentation multi task framework, aimed at enhancing the connectivity of existing backbone models through multi-task learning!


## Results Visualization

**Visualization of connectivity enhancement of Backbone network segmentation results by our framework.** Red: The red grid represents the connectivity enhancement results. Yellow: Local breaks in Backbone network segmentation results.
<div align="center">
<img src="https://github.com/user-attachments/assets/1df07ae3-eb49-49cb-92cf-df6b445603fc" width=60%>
</div>

**From a 2D perspective of CT, Visualization of connectivity enhancement of Backbone network segmentation results by our framework.** 
<div align="center">
<img src="https://github.com/user-attachments/assets/bfb459ed-44b0-49b1-9c7f-f42e5e758dec" width=85%>
</div>





## Method

<div align="center">
<img src="https://github.com/user-attachments/assets/a12fe472-ccaf-4f7a-8fa9-174f7222c494" width=70% alt="描述文字" />
</div>

The 3D Pulmonary Airway Segmentation Framework is composed of two main components: the class-balanced CT density distribution reconstruction (DDR-CB) at the input stage and the Anatomical Prior-Based Multi-Task Learning (AP-MTL) at the training stage.


<div align="center">
<img src="https://github.com/user-attachments/assets/1446ef87-d6e7-4368-8410-3331f44faef8" width=70%>
</div>

**Overview of Anatomical Prior-Based Multi-Task Learning.**  Follow the arrow to understand the entire process steps and the characteristics of the method.

## Requirements

```shell
edt==2.4.0
h5py==3.9.0
matplotlib==3.7.5
nibabel==5.2.1
numpy==1.20.0
opencv_python==4.9.0.80
pandas==1.4.4
Pillow==10.4.0
plotly==5.19.0
pydicom==2.4.4
scikit_image==0.19.3
scipy==1.14.0
SimpleITK==2.3.1
SimpleITK==2.4.0
torch==2.2.1
torchio==0.19.6
torchvision==0.17.1
tqdm==4.66.2
```

## DATA

* Download From:
  * [EXACT’09](http://image.diku.dk/exact/index.php?)
  * [LIDC-IDRI](https://www.cancerimagingarchive.net/collection/lidc-idri/)
  * [LABEL via ITK-SNAP](http://www.pami.sjtu.edu.cn/En/Home)

