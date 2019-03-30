# FeatureMethod

这是一个使用OpenCV实现特征点法的视觉里程计的Demo。

相关教程见原作者@jingedawang的简书

+ [OpenCV提取ORB特征并匹配](http://www.jianshu.com/p/420f8211d1cb)
+ [2D-2D相机位姿估计](http://www.jianshu.com/p/fbf56587a268)
+ [三角测量](http://www.jianshu.com/p/96d3b832330e)
+ [3D-2D相机位姿估计](http://www.jianshu.com/p/f16e5b5cc47d)
+ [3D-3D相机位姿估计](http://www.jianshu.com/p/504f0e5d9c26)

## 安装依赖
编译前需要先安装以下依赖包

- Opencv 3
- suitesparse
- g2o

### 安装Opencv 3
网上有许多教程，请自行安装。

### 安装suitesparse
```
sudo apt-get install libsuitesparse-dev
```

### 安装g2o
```
cd /tmp
git clone https://github.com/RainerKuemmerle/g2o.git
cd g2o
mkdir -p build
cd build
cmake ..
make
sudo make install
```
