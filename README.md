<div align="center">
  <h1>Den-SOFT: Dense Space-Oriented Light Field Dataset for 6-DOF Immersive Experience </h1>

  <p style="font-size:1.2em">
    <a href=""><strong>Xiaohang Yu</strong></a> ·
    <a href=""><strong>Zhengxian Yang</strong></a> ·
    <a href=""><strong>Shi Pan</strong></a> ·
    <a href=""><strong>Haoxiang Wang</strong></a> ·
    <a href=""><strong>Hongguang Xing</strong></a><br>
    <a href=""><strong>Yuqi Han</strong></a> ·
    <a href=""><strong>Jun Zhang</strong></a> ·
    <a href=""><strong>Borong Lin</strong></a> ·
    <a href=""><strong>Lei Yang</strong></a> ·
    <a href=""><strong>Lu Fang</strong></a> ·
    <a href="https://ytrock.com"><strong>Tao Yu</strong></a>
  </p>
  <p align="center" style="font-size:16px">Under Submission</p>


  <p align="center" style="margin: 2em auto;">
    <a href='https://metaverse-ai-lab-thu.github.io/Den-SOFT/' style='padding-left: 0.5rem;'><img src='https://img.shields.io/badge/Den--SOFT-Project_page-orange?style=flat&logo=databricks&logoColor=orange/' alt='Project Page'></a>
    <a href='https://arxiv.org/abs/2311.02542'><img src='https://img.shields.io/badge/arXiv-Paper_PDF-red?style=flat&logo=arXiv&logoColor=green' alt='Paper PDF'></a>
    <!--<a href='https://dl.acm.org/doi/10.1145/3592106'><img src='https://img.shields.io/badge/Paper-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='DOI'></a>
    <a href='https://youtu.be/GdvxgsITZOw'><img src='https://img.shields.io/badge/YouTube-Video-red?style=flat&logo=YouTube&logoColor=red' alt='YouTube Video'></a>-->
  </p>
</div>

## Dataset Overview

Scene                               |           Camera          |            pos            |            img           |           volume          |       5K&nbsp;JPEGs 
:-----------------------------------| :------------------------:| :------------------------:| ------------------------:| -------------------------:|---------------------------:
[RuziNiu Statue][Ruziniu_index]     |            41             |            38             |          1,558           |          11.52 m&sup3;    |[19&nbsp;GB][Ruziniu_index] 
[LizhaoJi Building][Lizhaoji_index] |            41             |            21             |            861           |           6.83 m&sup3;    |[9&nbsp;GB ][Lizhaoji_index] 
[Architecture][Architecture_index]  |            40             |            32             |          1,295           |          12.57 m&sup3;    |[13&nbsp;GB][Architecture_index] 
[Center Garden][CenterGarden_index] |            40             |            53             |          2,109           |          23.95 m&sup3;    |[23&nbsp;GB][CenterGarden_index]
[Square1][Square1_index]            |            40             |            40             |          1,588           |           8.37 m&sup3;    |[15&nbsp;GB][Square1_index] 
[Square2][Square2_index]            |            40             |            47             |          1,876           |          11.59 m&sup3;    |[18&nbsp;GB][Square2_index] 
[Flagstaff][Flagstaff_index]        |            40             |            38             |          1,518           |           8.04 m&sup3;    |[15&nbsp;GB][Flagstaff_index]  
[Office1][Office1_index]            |            40             |            43             |          1,710           |          13.14 m&sup3;    |[15&nbsp;GB][Office1_index]
[Office2][Office2_index]            |            40             |            89             |          3,550           |           39.72 m&sup3;   |[30&nbsp;GB][Office2_index]
Total                               |                                                                                                                                 |     |       |    |157&nbsp;GB |  

\* `volume`column indicates the space size with at least 10 camera within a range of 1 m&sup3;  
\* Above are all valid data which we have undistorted and tested on Metashape. If you want to acquire raw data, please contact us.

[Ruziniu_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217095&parId=32A0E05ACDEA165D%217088&o=OneUp
[Lizhaoji_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217089&parId=32A0E05ACDEA165D%217088&o=OneUp
[Architecture_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217094&parId=32A0E05ACDEA165D%217088&o=OneUp
[CenterGarden_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217097&parId=32A0E05ACDEA165D%217088&o=OneUp
[Square1_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217090&parId=32A0E05ACDEA165D%217088&o=OneUp
[Square2_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217093&parId=32A0E05ACDEA165D%217088&o=OneUp
[Flagstaff_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217092&parId=32A0E05ACDEA165D%217088&o=OneUp
[Office1_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217091&parId=32A0E05ACDEA165D%217088&o=OneUp
[Office2_index]: https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217096&parId=32A0E05ACDEA165D%217088&o=OneUp


## Example Images

<table>
<thead>
  <tr>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217095&parId=32A0E05ACDEA165D%217088&o=OneUp">RuziNiu Statue</a></th>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217089&parId=32A0E05ACDEA165D%217088&o=OneUp">LizhaoJi Building</a></th>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217094&parId=32A0E05ACDEA165D%217088&o=OneUp">Architecture</a></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217095&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/RuziNiu Statue.jpg" alt="RuziNiu Statue" alt="RuziNiu Statue"> </a> </td>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217089&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/LizhaoJi Building.jpg" alt="LizhaoJi Building" alt="LizhaoJi Building"> </a> </td>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217094&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/Architecture.jpg" alt="Architecture" alt="Architecture"> </a> </td>
  </tr>
</tbody>
</table>

<table>
<thead>
  <tr>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217097&parId=32A0E05ACDEA165D%217088&o=OneUp">Center Garden</a></th>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217090&parId=32A0E05ACDEA165D%217088&o=OneUp">Square1</a></th>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217093&parId=32A0E05ACDEA165D%217088&o=OneUp">Square2</a></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217097&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/Center Garden.jpg" alt="Center Garden" alt="Center Garden"> </a> </td>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217090&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/Square1.jpg" alt="Square1" alt="Square1"> </a> </td>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217093&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/Square2.jpg" alt="Square2" alt="Square2"> </a> </td>
  </tr>
</tbody>
</table>

<table>
<thead>
  <tr>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217092&parId=32A0E05ACDEA165D%217088&o=OneUp">Flagstaff</a></th>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217091&parId=32A0E05ACDEA165D%217088&o=OneUp">Office1</a></th>
    <th><a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217096&parId=32A0E05ACDEA165D%217088&o=OneUp">Office2</a></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217092&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/Flagstaff.jpg" alt="Flagstaff" alt="Flagstaff"> </a> </td>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217091&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/Office1.jpg" alt="Office1" alt="Office1"> </a> </td>
    <td width="33%"> <a href="https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&cid=32A0E05ACDEA165D&id=32A0E05ACDEA165D%217096&parId=32A0E05ACDEA165D%217088&o=OneUp"> <img src="static/images/media/Office2.jpg" alt="Office2" alt="Office2"> </a> </td>
  </tr>
</tbody>
</table>

## Capture Rig

All images in the dataset were taken with our self-designed multi-camera device named "Compound Eye"  (as specified in [the overview table](#dataset-overview)). Capture rig consists of  40-41 GoPro HERO10 cameras mounted on a remote-controlled car.

![Capture rig model](static/images/capture%20rig.jpg)

## Download instructions

The [Den-SOFT dataset](https://onedrive.live.com/?authkey=%21AHkhjVX1B8Ktzuk&id=32A0E05ACDEA165D%217088&cid=32A0E05ACDEA165D) is hosted on one Drive, and can be explored with any browser.

## Data Organization

Our scene capture data is organized following this structure:
```
1.41 cameras: RuziNiu Statue and LizhaoJi Building
│
├── images                # Scene images with 5K resolution
│   ├── 1(1)              # First camera (first pose)
│   ├── 1(2)              
│   ├── 1(...)            # More images
│   ├── 2(1)              # Second camera (first pose)
│   ├── [...]             # More images
│   ├── 41(38)            # Last camera (last pose)


2.40 cameras: All other scene datas
│
├── images                # Scene images with 5K resolution
│   ├── Square1-1         # Scene name - first pose
│   ├── [...]             # More images


3.Metashape Reference: camera poses and point cloud
│
├── Architecture          # Scene name
│   ├── camera.xml        # Camera poses
│   ├── point_cloud.ply   # Point cloud correspond to the scene

```


### JPEG images (`images/*.jpg`)

* We provide images at 5K resolution(Width:5568, Height:4176). If you want to use Metashape to get sparse point cloud reconstruction or camera poses, you can use the  `camera.xml`, `point_cloud.ply` as references. Some of the images were removed due to involving irrelevant elements in the scene or blurry images. It would be greatly appreciated if you have a better method that can use all images to estimate camera pose and reconstruct point clouds.

## Feasibility verification of our dataset

### 3D Reconstruction Demo with 3DGS

The following videos show the training result of our datasets using 3DGS.



https://github.com/Metaverse-AI-Lab-THU/Den-SOFT/assets/122356862/a56012be-126a-47d3-92eb-5fd638870610


[High resolution video](https://cloud.tsinghua.edu.cn/f/0ecde282f3fa4a0cb892/)


### Side by side comparison 

The following video shows the comparison between training results and Ground truth.



https://github.com/Metaverse-AI-Lab-THU/Den-SOFT/assets/122356862/93309ccf-47bb-49cf-8702-3a6afed190fc



[High resoulution video](https://cloud.tsinghua.edu.cn/f/22ddd702f6644f77bc69/)

### Caputure density visulization

In order to give you a more intuitive view of the sampling density when we collect scene data, we have visualized the viewpoint density within 1 m&sup3; using Metashape and mayavi. The sampling density from blue to red indicates sparse to dense.



https://github.com/Metaverse-AI-Lab-THU/Den-SOFT/assets/122356862/215dcb63-6bcf-4908-9f0d-1ac5da3e2e67




https://github.com/Metaverse-AI-Lab-THU/Den-SOFT/assets/122356862/1c8f9ce9-9967-462e-8ebc-ea3392b3dc51




## Citation
If you use any data from this dataset or any code released in this repository, please cite the Den-SOFT paper.

```bibtex
@InProceedings{Den-SOFT,
  author    = {Xiaohang Yu and
               Zhengxian Yang and
               Shi Pan and
               Haoxiang Wang and
               Hongguang Xing and
               Yuqi Han and
               Jun Zhang and
               Lei Yang and
               Lu Fang and
               Tao Yu },
  title     = {{Den-SOFT}: Dense Space-Oriented Light Field Dataset for 6-DOF Immersive Experience},
  year      = {2024},
  url       = {https://metaverse-ai-lab-thu.github.io/Den-SOFT/},
}
```

## License
Creative Commons Attribution-NonCommercial (CC BY-NC) 4.0,
as found in the [LICENSE file](LICENSE).

[[Terms of Use](https://opensource.fb.com/legal/terms/)]
[[Privacy Policy](https://opensource.fb.com/legal/privacy)]
