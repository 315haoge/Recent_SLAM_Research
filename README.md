
# Recent_SLAM_Research_2020
【回馈社区】跟踪SLAM前沿动态[2019](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM_Research_2019.md), [2018版](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM_Research_2018.md) .去年大概收录了500篇关于SLAM的论文，因为本人在企业重点研究的是VSLAM以及多传感器融合，所以并没有把全部论文精读，难免有漏的或者差的。今年重点是求精以及做好分类，继续做好本圈儿的服务工作。

### ------------ ICRA 2020 
### ------------ ICRA 2020 终止线 ----------
### ------------ CVPR 2020 
### ------------ CVPR 2020 终止线 ----------
### ------------ ECCV 2020 
### ------------ ECCV 2020 终止线 ----------
### ------------ IROS 2020 
### ------------ IROS 2020 终止线 ----------
### ------------ ICCV 2020 
### ------------ ICCV 2020 终止线 ----------

### SLAM
#### 1. [ Semantic SLAM ] 2020-01-13-[Visual Semantic SLAM with Landmarks for Large-Scale Outdoor Environment](https://arxiv.org/pdf/2001.01028.pdf)  Only label the point clouds with semantic segmentation info, no improvement in accuarcy. [code](https://github.com/1989Ryan/Semantic_SLAM/)
#### 2. [ Calibration ] 2020-01-13-[A Generalized Framework for Autonomous Calibration of Wheeled Mobile Robots](https://arxiv.org/pdf/2001.01555.pdf) 
#### 3. [ VSLAM ] 2020-01-13-[Trained Trajectory based Automated Parking System using Visual SLAM](https://arxiv.org/pdf/2001.02161.pdf) 
#### 4. [ Deep SLAM ] 2020-01-13-[AD-VO: SCALE-RESILIENT VISUAL ODOMETRY USING ATTENTIVE DISPARITY MAP](https://arxiv.org/pdf/2001.02090.pdf)  Learned based frame to frame VO with the input as disparity map.
#### 5. [ Lidar Deep SLAM ] 2020-01-13-[CAE-LO: LiDAR Odometry Leveraging Fully Unsupervised Convolutional Auto-Encoder for Interest Point Detection and Feature Description](https://arxiv.org/pdf/2001.01354.pdf) Auto-Encoder based LiDAR Odometry (CAE-LO) that detects interest points from spherical ring data using 2D CAE and extracts features from multi-resolution voxel model using 3D CAE.  [code](https://github.com/SRainGit/CAE-LO) 
#### 6. [ VSLAM ] 2020-01-13-[Good Feature Matching: Towards Accurate, Robust VO/VSLAM with Low Latency](https://arxiv.org/pdf/2001.00714.pdf) Introduction of an efficient good feature selection algorithm using the Max-logDet metric, which is an order of magnitude faster than state-of-the-art feature selection approaches. [code](https://github.com/ivalab/GF_ORB_SLAM)  
#### 7. [ VSLAM ] 2020-01-13-[Direct Sparse Visual-Inertial Odometry with Stereo Cameras](https://candyguo.github.io/files/1.pdf) Quantitative evaluation demonstrates that the proposed Stereo VI-DSO is superior to Stereo DSO both in terms of tracking accuracy and robustness. But the result is worse than VINS.
#### 8. [ VSLAM ] 2020-01-14-[Accurate Line Reconstruction for Point and Line-Based Stereo Visual Odometry](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8936964) 
#### 9. [ VSLAM ] 2020-01-14-[A Stereo Visual-Inertial SLAM Approach for Indoor Mobile Robots in Unknown Environments Without Occlusions](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8937551) Use one-circle feature-matching method, which refers to a sequence of the circle matching for the time after space (STCM), and an STCM-based visual-inertial simultaneous localization and mapping (STCM-SLAM) technique.
#### 10. [ Lidar Seg ] 2020-01-14-[Multi-Scale Point-Wise Convolutional Neural Networks for 3D Object Segmentation From LiDAR Point Clouds in Large-Scale Environments](https://ieeexplore.ieee.org/abstract/document/8943956/authors#authors) 
#### 11. [ Review ] 2020-01-14-[Multi-Sensor Fusion in Automated Driving: A Survey](https://sci-hub.tw/10.1109/ACCESS.2019.2962554) 
#### 12. [ Lidar Deep SLAM ] 2020-01-14-[SLOAM: Semantic Lidar Odometry and Mapping for Forest Inventory](https://arxiv.org/pdf/1912.12726.pdf) 
#### 13. [ Deep SLAM ] 2020-01-22-[Learning Topometric Semantic Maps from Occupancy Grids](https://arxiv.org/pdf/2001.03676.pdf) 2D laser semantic map. 
#### 14. [ VSLAM ] 2020-01-22-[Temporal Delay Estimation of Sparse Direct Visual Inertial Odometry for Mobile Robots](https://sci-hub.tw/https://doi.org/10.1016/j.jfranklin.2019.11.075) Calibrate the time offset between IMU and Camera.
#### 15. [ IMU ] 2020-02-06-[A Lightweight and Accurate Localization Algorithm Using Multiple Inertial Measurement Units](https://sci-hub.tw/10.1109/LRA.2020.2969146) The overall performance of SLAM can be further improved by using multiple IMUs. 
#### 16. [ Lidar SLAM ] 2020-02-10-[Localization of Map Changes by Exploiting SLAM Residuals](https://link.springer.com/chapter/10.1007/978-3-030-40605-9_27) identify changes in maps constructed by SLAM.
#### 17. [ VSLAM ] 2020-02-10-[Bidirectional Trajectory Computation for Odometer-Aided Visual-Inertial SLAM](https://arxiv.org/pdf/2002.00195.pdf) not only solves the problem of the unobservability of accelerometer bias and extrinsic parameters before the first turning, but also results in more accurate trajectories in comparison with the state-of-the-art approaches.
#### 18. [ EKF ] 2020-02-10-[A Code for Unscented Kalman Filtering on Manifolds (UKF-M)](https://arxiv.org/pdf/2002.00878.pdf) a novel methodology for Unscented Kalman Filtering (UKF) on manifolds that extends our previous work about UKF on Lie groups.
#### 19. [ New sensor ] 2020-02-10-[Corners positioning for binocular ultra-wide angle long-wave infrared camera calibration](https://www.sciencedirect.com/science/article/abs/pii/S0030402619313397) calibrating binocular ultra-wide angle long-wave infrared camera.
#### 20. [ VSLAM ] 2020-02-12-[Kimera: an Open-Source Library for Real-Time Metric-Semantic Localization and Mapping](https://arxiv.org/pdf/1910.02490.pdf) VIO + Dense mapping + Semantic 
#### 21. [ Semantic ] 2020-02-12-[Edge Assisted Mobile Semantic Visual SLAM](http://tns.thss.tsinghua.edu.cn/~jingao/papers/infocom20_edgeSLAM.pdf) edgeSLAM leverages the state-of-the-art semantic segmentation algorithm to enhance localization and mapping accuracy, and speeds up the computation-intensive SLAM and semantic segmentation algorithms by computation offloading.
#### 22. [ lidar SLAM] 2020-02-12-[Online LiDAR-SLAM for Legged Robots with Robust Registration and Deep-Learned Loop Closure](https://arxiv.org/pdf/2001.10249.pdf)In this paper, we present a factor-graph LiDARSLAM system which incorporates a state-of-the-art deeply learned feature-based loop closure detector to enable a legged robot to localize and map in industrial environments. 
#### 23. [ Semantic ] 2020-02-14-[Tightly Coupled Semantic RGB-D Inertial Odometry for Accurate Long-Term Localization and Mapping](https://ieeexplore.ieee.org/abstract/document/8981658) utilize semantically enhanced feature matching and visual inertial bundle adjustment to improve the robustness of odometry especially in feature-sparse environments.
#### 24. [ VIO ] 2020-02-14-[Visual-Inertial Ego-Motion Estimation using Rolling-Shutter Camera in autonomous driving](https://pdfs.semanticscholar.org/3c90/940d1572789aa6459e443bede87fdfcb8b86.pdf) interpolate the IMU pose between consecutive poses and set up a novel feature measurement error model to cover the time delay issues. 
#### 25. [ VIO ] 2020-02-14-[EIP-VIO: Edge-Induced Points Based Monocular Visual-Inertial Odometry](https://ieeexplore.ieee.org/abstract/document/8982582) propose an improved and practical monocular visual-inertial odometry method based on selective edge points.
#### 26. [ Event camera ] 2020-02-14-[Sepia, Tarsier, and Chameleon: A Modular C++ Framework for Event-Based Computer Vision](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6960268/) A framework to process Event camera.  [code]( https://github.com/neuromorphic-paris/tutorials)
#### 27. [ Multimodal localization] 2020-02-14-[Multimodal localization: Stereo over LiDAR map](https://sci-hub.tw/https://doi.org/10.1002/rob.21936) Visual localization in lidar map. 

### 3D Reconstruction
#### 1. [Automatically explore] 2020-01-14-[Plan3D: Viewpoint and Trajectory Optimization for Aerial Multi-View Stereo Reconstruction](https://sci-hub.tw/https://doi.org/10.1145/3233794)
#### 2. [ laser reconstruction] 2020-02-14-[Real-Time 3D Reconstruction of Thin Surface Based on Laser Line Scanner](https://www.researchgate.net/publication/338707435_Real-Time_3D_Reconstruction_of_Thin_Surface_Based_on_Laser_Line_Scanner) 

### Path Planning
#### 1. [UAV] 2020-01-14-[Robust Real-time UAV Replanning Using Guided Gradient-based Optimization and Topological Paths](https://arxiv.org/pdf/1912.12644.pdf)Replanning method based on GTO.[code](https://github.com/HKUST-Aerial-Robotics/Fast-Planner)
#### 2. [Auto exploration] 2020-01-14-[3D Exploration and Navigation with Optimal-RRT Planners for Ground Robots in Indoor Incidents](https://www.researchgate.net/publication/338367746_3D_Exploration_and_Navigation_with_Optimal-RRT_Planners_for_Ground_Robots_in_Indoor_Incidents)

### Others.

## SLAM 能力图 

<img src="https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM%E8%83%BD%E5%8A%9B%E5%9B%BE.png" width ="300" height="550" />





























