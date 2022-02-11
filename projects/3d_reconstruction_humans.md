---
layout: projects
title: "Projects"
---
 <center> 
 <h1>
 3D Reconstruction of Humans
 </h1>
 </center>

 ---

 We are interested in computer vision and machine learning with a focus on 3D scene understanding, reconstruction etc. In particular, we deal with problems where human body is reconstructed from 2D images and analysed in 3D, registration of point clouds of indoor scenes captured from commodity sensors as well as large outdoor scenes captured from LIDAR scanners.



## 3D Reconstruction of Humans from Monocular/Multi-view Images

Recent advancements in deep learning have enabled 3D human body reconstruction from a monocular image, which has broad applications in multiple domains. Given a single RGB image we want to generate a complete 3D reconstruction of a clothed human. This is a very illposed problem due to depth ambiguity. 


<div class="imgbox">
    <img class="center-fit" src="/assets/img/human_reconstruction.gif" alt="Group Picture" style="width:70%;"/>
</div>
<br>

---

## 3DHumans
We have collected [3DHumans](http://cvit.iiit.ac.in/research/projects/cvit-projects/sharp-3dhumans-a-rich-3d-dataset-of-scanned-humans), a dataset of around 250 scans containing people in diverse body shapes in various garments styles and sizes. We cover a wide variety of clothing styles ranging from loose robed clothing like saree (a typical South-Asian dress) to relatively tight-fitting shirt and trousers. The dataset consists of around 150 male and 50 unique female subjects. Total male scans are about 180 and female scans are around 70. In terms of regional diversity, for the first time, we capture body shape, appearance and clothing styles for the South- Asian population. We will release this data in the public domain for academic purpose.

<div class="imgbox">
    <img class="center-fit" src="/assets/img/dataset.gif" alt="Group Picture" style="width:70%;"/>
</div>

---
## Volumetric Capture 

##### Static Capture
We collect high-quality 3D static scans of human with a wide variety of clothing styles and varied poses using a commercial structured- light sensor (accurate up to 0.5mm). We are able to retain high-frequency geometrical and textural details.


<div class="imgbox">
    <img class="center-fit" src="/assets/img/dataset_static.jpeg" alt="Group Picture" style="width:70%;"/>
</div>
<br>

##### Temporal Capture
Due to the lack of 4D data of humans, we have our own capture pipeline to collect temporally coherent data. This data is collected through precisely calibrated multiple Microsoft Azure Kinects.
<div class="imgbox">
    <img class="center-fit" src="/assets/img/volumetric_capture.gif" alt="Group Picture" style="width:70%;"/>
</div>




