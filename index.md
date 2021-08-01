
# A Flexible Framework for Virtual Omnidirectional Vision to Improve Operator Situation Awareness
Authors: Martin Oehler and Oskar von Stryk <br/>
Affiliation: Technical University of Darmstadt

## Abstract
During teleoperation of a mobile robot, providing good operator situation awareness is a major concern as a single mistake can lead to mission failure. Camera streams are widely used for teleoperation but offer limited field-of-view. 
In this paper, we present a flexible framework for virtual projections to increase situation awareness based on a novel method to fuse multiple cameras mounted anywhere on the robot. Moreover, we propose a complementary approach to improve scene understanding by fusing camera images and geometric 3D Lidar data to obtain a colorized point cloud. 
The implementation on a compact omnidirectional camera reduces system complexity considerably and solves multiple use-cases on a much smaller footprint compared to traditional approaches such as actuated pan-tilt units. 
Finally, we demonstrate the generality of the approach by application to the multi-camera system of the Boston Dynamics Spot.

## Source Code
The source code is hosted as open source on Github:
* [tu-darmstadt-ros-pkg/image_projection](https://github.com/tu-darmstadt-ros-pkg/image_projection)
* [tu-darmstadt-ros-pkg/color_cloud_from_image](https://github.com/tu-darmstadt-ros-pkg/color_cloud_from_image)

License: [MIT](https://choosealicense.com/licenses/mit/)

## Citation
Please cite our paper if you use this software as part of your scientific publication:

```
[BIBTEX HERE]
```
