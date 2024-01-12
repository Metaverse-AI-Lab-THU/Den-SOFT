<div align="center">
  <h1>HIDIVE-6D: High-Density Image Capturing for a 6DoF Immersive Visual Experience </h1>

  <p style="font-size:1.2em">
    <a href=""><strong>Xiaohang Yu</strong></a> ·
    <a href=""><strong>Zhengxian Yang</strong></a> ·
    <a href=""><strong>Shi Pan</strong></a> ·
    <a href=""><strong>Haoxiang Wang</strong></a> ·
    <a href=""><strong>Hongguang Xing</strong></a><br>
    <a href=""><strong>Yuqi Han</strong></a> ·
    <a href=""><strong>Jun Zhang</strong></a> ·
    <a href=""><strong>Lei Yang</strong></a> ·
    <a href=""><strong>Lu Fang</strong></a> ·
    <a href="https://ytrock.com"><strong>Tao Yu</strong></a>
  </p>
  <p align="center" style="font-size:16px">Under Submission</p>


  <p align="center" style="margin: 2em auto;">
    <a href='https://vr-nerf.github.io' style='padding-left: 0.5rem;'><img src='https://img.shields.io/badge/VR--NeRF-Project_page-orange?style=flat&logo=googlecardboard&logoColor=orange' alt='Project Page'></a>
    <a href='https://arxiv.org/abs/2311.02542'><img src='https://img.shields.io/badge/arXiv-Paper_PDF-red?style=flat&logo=arXiv&logoColor=green' alt='Paper PDF'></a>
    <!--<a href='https://dl.acm.org/doi/10.1145/3592106'><img src='https://img.shields.io/badge/Paper-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='DOI'></a>
    <a href='https://youtu.be/GdvxgsITZOw'><img src='https://img.shields.io/badge/YouTube-Video-red?style=flat&logo=YouTube&logoColor=red' alt='YouTube Video'></a>-->
  </p>
</div>

## Dataset Overview

Scene          |   cams   |   pos   |   img   |    volume   |  4K&nbsp;JPEGs 
:--------------| ---------| ---:    | ---:    | ------------|--------------------:
[RuziNiu Statue][apartment_index]  |   [41](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/apartment/images-jpeg-2k/collage.mp4)    |   38   | 1,558 | 20.27m&sup3; |[19&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/apartment/images-2k/index.html)
[LizhaoJi Building][kitchen_index] |   [41](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/kitchen/images-jpeg-2k/collage.mp4)      |   21   |   861 | 15.40m&sup3; |[9&nbsp;GB ](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/kitchen/images-2k/index.html)
[Architecture][office1a_index]     |   [40](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1a/images-jpeg-2k/collage.mp4)     |   32   | 1,295 | 34.22m&sup3; |[13&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1a/images-2k/index.html)
[Center Garden][office1b_index]    |   [40](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1b/images-jpeg-2k/collage.mp4)     |   53   | 2,109 | 140.74m&sup3; |[23&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1b/images-2k/index.html)
[Square1][office2_index]           |   [40](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office2/images-jpeg-2k/collage.mp4)      |   40   | 1,588 | 21.69m&sup3; |[15&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office2/images-2k/index.html)
[Square2][office_view1_index]      |   [40](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view1/images-jpeg-2k/collage.mp4) |   47   | 1,876 | 33.84m&sup3; |[18&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view1/images-2k/index.html) 
[Flagstaff][office_view2_index]    |   [40](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view2/images-jpeg-2k/collage.mp4) |   38   | 1,518 | 22.98m&sup3; |[15&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view2/images-2k/index.html) 
[Office1][riverview_index]         |   [40](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/riverview/images-jpeg-2k/collage.mp4)    |   43   | 1,710 | 53.55m&sup3; |[15&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/riverview/images-2k/index.html)
[Office2][seating_area_index]      |   [40](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/seating_area/images-jpeg-2k/collage.mp4) |   89   | 3,550 | 296.51m&sup3; |[30&nbsp;GB](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/seating_area/images-2k/index.html)
Total                              |                                                                                                                                 |     |       |    |157&nbsp;GB |  

\* `volume`column indicates the space size with at least one camera within a range of 1 m&sup3;
\* Above are all valid data which we have undistorted and tested on Metashape. If you want to acquire raw data, please contact us.

[apartment_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/apartment/index.html
[kitchen_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/kitchen/index.html
[office1a_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1a/index.html
[office1b_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1b/index.html
[office2_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office2/index.html
[office_view1_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view1/index.html
[office_view2_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view2/index.html
[riverview_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/riverview/index.html
[seating_area_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/seating_area/index.html
[table_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/table/index.html
[workshop_index]: https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/workshop/index.html

## Example Images

<table>
<thead>
  <tr>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/apartment/index.html">RuziNiu Statue</a></th>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/kitchen/index.html">LizhaoJi Building</a></th>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1a/index.html">Architecture</a></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/apartment/index.html"> <img src="static/images/media/RuziNiu Statue.jpg" alt="RuziNiu Statue" alt="RuziNiu Statue"> </a> </td>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/kitchen/index.html"> <img src="static/images/media/LizhaoJi Building.jpg" alt="LizhaoJi Building" alt="LizhaoJi Building"> </a> </td>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1a/index.html"> <img src="static/images/media/Architecture.jpg" alt="Architecture" alt="Architecture"> </a> </td>
  </tr>
</tbody>
</table>

<table>
<thead>
  <tr>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office1b/index.html">Center Garden</a></th>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office2/index.html">Square1</a></th>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view1/index.html">Square2</a></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office2/index.html"> <img src="static/images/media/Center Garden.jpg" alt="Center Garden" alt="Center Garden"> </a> </td>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view1/index.html"> <img src="static/images/media/Square1.jpg" alt="Square1" alt="Square1"> </a> </td>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view2/index.html"> <img src="static/images/media/Square2.jpg" alt="Square2" alt="Square2"> </a> </td>
  </tr>
</tbody>
</table>

<table>
<thead>
  <tr>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view2/index.html">Flagstaff</a></th>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view2/index.html">Office1</a></th>
    <th><a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/riverview/index.html">Office2</a></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/seating_area/index.html"> <img src="static/images/media/Flagstaff.jpg" alt="Flagstaff" alt="Flagstaff"> </a> </td>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/table/index.html"> <img src="static/images/media/Office1.jpg" alt="Office1" alt="Office1"> </a> </td>
    <td width="33%"> <a href="https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/office_view2/index.html"> <img src="static/images/media/Office2.jpg" alt="Office2" alt="Office2"> </a> </td>
  </tr>
</tbody>
</table>

## Capture Rig

All images in the dataset were taken with our self-designed multi-camera device named "Compound Eye"  (as specified in [the overview table](#dataset-overview)). Capture rig consists of  40-41 GoPro HERO10 cameras mounted on a remote-controlled car.

![Capture rig model](static/images/capture%20rig.jpg)

## Download instructions

The [HIDIVE-6D dataset](https://fb-baas-f32eacb9-8abb-11eb-b2b8-4857dd089e15.s3.amazonaws.com/EyefulTower/index.html) is hosted on Google Drive, and can be explored with any browser or downloaded with standard software, such as [wget](https://www.gnu.org/software/wget/) or [curl](https://curl.se/).


## Data Organization

Our scene capture data is organized following this structure:
```
1.41 cameras: RuziNiu Statue and LizhaoJi Building
│
├── images                # Scene images with 4K resolution
│   ├── 1(1)              # First camera (first pose)
│   ├── 1(2)              
│   ├── 1(...)            # More images
│   ├── 2(1)              # Second camera (first pose)
│   ├── [...]             # More images
│   ├── 41(38)            # Last camera (last pose)


2.40 cameras: All other scene datas
│
├── images                # Scene images with 4K resolution
│   ├── Square1-1         # Scene name - first pose
│   ├── [...]             # More images


3.Metashape Reference: camera poses and point cloud
│
├── Architecture          # Scene name
│   ├── camera.xml        # Camera poses
│   ├── point_cloud.ply   # Point cloud correspond to the scene

```


### JPEG images (`images/*.jpg`)

* We provide images at 4K resolution(Width:5568, Height:4176). If you want to use Metashape to get sparse point cloud reconstruction or camera poses, you can use the  `camera.xml`, `point_cloud.ply` as references. Some of the images were removed due to involving irrelevant elements in the scene or blurry images. It would be greatly appreciated if you have a better method that can use all images to estimate camera pose and reconstruct point clouds.

## Feasibility verification of our dataset

### 3D Reconstruction Demo with 3DGS

The following videos show the training result of our datasets using 3DGS.



https://github.com/Metaverse-AI-Lab-THU/HIDIVE-6D/assets/122356862/a56012be-126a-47d3-92eb-5fd638870610


[High resolution video](https://cloud.tsinghua.edu.cn/f/0ecde282f3fa4a0cb892/)


### Side by side comparison 

The following video shows the comparison between training results and Ground truth.



https://github.com/Metaverse-AI-Lab-THU/HIDIVE-6D/assets/122356862/93309ccf-47bb-49cf-8702-3a6afed190fc



[High resoulution video](https://cloud.tsinghua.edu.cn/f/22ddd702f6644f77bc69/)

### Caputure density visulization

In order to give you a more intuitive view of the sampling density when we collect scene data, we have visualized the viewpoint density within 1 m&sup3; using Metashape and mayavi. The sampling density from blue to red indicates sparse to dense.



https://github.com/Metaverse-AI-Lab-THU/HIDIVE-6D/assets/122356862/215dcb63-6bcf-4908-9f0d-1ac5da3e2e67




https://github.com/Metaverse-AI-Lab-THU/HIDIVE-6D/assets/122356862/1c8f9ce9-9967-462e-8ebc-ea3392b3dc51




## Citation
If you use any data from this dataset or any code released in this repository, please cite the HIDIVE-6D paper.

```bibtex
@InProceedings{HIDIVE-6D,
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
  title     = {{HIDIVE-6D}: High-Density Image Capturing for a 6DoF Immersive Visual Experience},
  year      = {2024},
  url       = {https://metaverse-ai-lab-thu.github.io/HIDIVE-6D/},
}
```

## License
Creative Commons Attribution-NonCommercial (CC BY-NC) 4.0,
as found in the [LICENSE file](LICENSE).

[[Terms of Use](https://opensource.fb.com/legal/terms/)]
[[Privacy Policy](https://opensource.fb.com/legal/privacy)]
