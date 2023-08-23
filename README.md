# Multi-Model-Fusion-for-3D-Object-Detection

This project is an extension of work done by Su Pang, Daniel Morris, Hayder Radha on 3D object detection for Multi model fusion of LiDAR and Camera sensory data.
Below is the paper reference:
```
@article{pang2020clocs,
  title={CLOCs: Camera-LiDAR Object Candidates Fusion for 3D Object Detection},
  author={Pang, Su and Morris, Daniel and Radha, Hayder},
  booktitle={2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year={2020}
  organization={IEEE}
}
```

Main README file to implement code is inside the folder.

## Abstract
3D object detection tasks are usually performed based on multiple sensory data, such as LiDAR, image, and RADAR data. Image data usually provide us with extensive details on semantic features of objects present in the image, while LiDAR focuses on 3D localization and provides information on structural details of objects. Many efforts have been made on multimodal fusion to perform 3D object recognition, and many works have been mainly presented on 3 concepts of fusion early, intermediate and late fusion. Early and intermediate fusion are usually architecturally complex and require pixel-level correspondence. Meanwhile, the late fusion approach is quite convenient and simpler as it uses pre-trained single modality detectors to detect candidates, and then uses these candidates through fusion and processing to generate final detection candidates. We use the Camera-LiDAR Object Candidates’ Fusion for 3D Object Detection (CLOCs) network and conduct a comprehensive study of the fusion architecture and detection framework. Our study is conducted using the KITTI training set and our test.

## Network Architecture

![Screenshot 2023-08-23 141554](https://github.com/ManthanKPatel/Multi-Model-Fusion-for-3D-Object-Detection/assets/90741568/c67a4647-d4ac-4e2e-9520-202ef8d34d6e)


![Screenshot 2023-08-23 141437](https://github.com/ManthanKPatel/Multi-Model-Fusion-for-3D-Object-Detection/assets/90741568/433f2224-39ed-4768-af61-0a78fd8e7c50)



## Results

![voxel](https://github.com/ManthanKPatel/Multi-Model-Fusion-for-3D-Object-Detection/assets/90741568/8e58aef2-8a93-40af-8c09-4fda15fc21b2)


![second](https://github.com/ManthanKPatel/Multi-Model-Fusion-for-3D-Object-Detection/assets/90741568/6cef7652-3b1f-4007-b395-e2d97601fa50)


![Screenshot 2023-08-23 141814](https://github.com/ManthanKPatel/Multi-Model-Fusion-for-3D-Object-Detection/assets/90741568/282cac51-b25d-48aa-ad94-07b728e5b358)



##### We have added our project report with our modifications and changes and results achived based on that.


