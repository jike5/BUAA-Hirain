### 纪要

[toc]

### 9月计划

- [x] 完成论文工作

- [ ] 研究方向调研：（1）基于NeRF的工作的完成调研报告或PPT（2）或者其他有意思且可行的方向

  

---

#### 第二周总结

##### **Finish**

- [x] 初步调研了NeRF与自动驾驶方向结合点：

  （1）定位

  （2）感知（主要指Tesla最近在CVPR2022WorkShop的演讲）

  （3）Simulator

- [x] 继续完成ICRA论文相关实验

##### 20220907会议纪要：

* 关于NeRF与自动驾驶的讨论：

  基于NeRF的定位需要回答的问题：（1）为什么比其他方法好（2）好在哪里（3）有哪些不足（4）精度、速度具体量化指标

* 关于AVP-SALM：

  APV-SLAM在语义标签较少的区域表现不佳；结合ORB-SLAM2是否可以提高。需要完成AVP-SLAM的深入了解

* 补充：

  目前论文实验采用的图片大小为`480*960`的大小. Mega-nerf论文中采用的 `Mill`数据集图像为`4608*3456`，场景尺度`150,000 to 1,300,000 m^2`

------

#### 第三周总结

**Finish**

- [x] 云边协同项目进度汇报
- [x] ICRA论文投递
- [x] ICRA论文PPT准备

**20220919会议纪要**

[]

#### 第四周总结

- [x] 完成ICRA视频制作
- [x] 基于websocket修改EdgeSLAM

**20220923会议纪要**

* 使用不同数据集测试ORB-SLAM2的实际表现

#### 第五周总结

- [x] 云边协同开发：edgemesh环境配置；websocket开发；与tcp socket测试
- [x] 完成云边协同结项报告
- [ ] cpu，内存对比曲线(用于项目README)

讨论：

* AVP Dataset
* Benchmark
* Cloud-Edge Collaboration: Cloud  data receive, data compress, data sending, map updating

* NeRF-based SLAM(AIR)

**20220930纪要**

* 数据集：丁老师准备


#### 第六周总结


#### 第七周总结
- [x] 云边协同开发：完成ros-melodic,orbslam2-dev,edgeslam-run镜像编译
- [x] 完成orbslam2的cpu, rmse表现测试
- [x] 阅读AVP-SLAM-PLUS代码(代码很简单，很多AVP-SLAM论文里的并没有复现出来)
- [x] 阅读AVP-SLAM文献：比较有启发的有AVP-LOC
- [ ] edgeslam的cpu, rmse表现测试

Our dataset:
* 测试光照变化下重定位
* 不同位置开始
