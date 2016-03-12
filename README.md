<b>About agisoft PhotoScan</b></br>
Agisoft PhotoScan is a stand-alone software product that performs photogrammetric processing of digital images and generates 3D spatial data

to be used in GIS applications, cultural heritage documentation, and visual effects production as well as for indirect measurements of objects of various scales.

I have something work script run with PhotoScan Pro V1.2.3  under Linux Ubuntu v14.04~15.10

PhotoScan是一个使用单反相机或无人机拍摄的数字相片来产生3D模型数据的软件产品。
在这里存放测试使用的一些脚本，适合于PhotoScan Pro V.1.2.3，运行于Linux平台。


1.需要安装的软件包<br>
<ul>sudo apt-get install axel git clinfo</ul>

2.需要下载的软件包
2.1 Photoscan-pro 应用程序linux二进制包
<ul>axel http://download.agisoft.com/photoscan-pro_1_2_3_amd64.tar.gz</ul>
2.2 GPU并行计算及OpenCL支持
<ul>axel http://developer.download.nvidia.com/compute/cuda/7.5/Prod/local_installers/cuda-repo-ubuntu1504-7-5-local_7.5-18_amd64.deb</ul>
2.3 安装aliyun阿里云存储对象OSS的挂载程序源代码
<ul>git clone https://git.oschina.net/weiweibaba2007/cloudfs.git</ul>
