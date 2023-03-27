# BEVpointcloud_process

ROS package for ground filter and cluster focus on the BEV pointcloud
该算法包含了点云下采样、点云变换、地面分割、聚类、跟踪
## 安装
 - 建立工作空间并拷贝这个库
   ```Shell
   mkdir -p BEV_pointcloud_cluster_tracker/src
   cd BEV_pointcloud_cluster_tracker/src
   git@github.com:huashu996/BEV_pointcloud_cluster_tracker.git
   cd ..
   catkin_make
   ```
## 运行
 - 启动
   ```Shell
   roslaunch lidar_obstacle_detector mai_city.launch
   ```
## 参数修改
	./cfg obstacle_detector.cfg
