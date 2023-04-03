# 花卉识别-基于tensorflow2.3实现
**本期视频的代码存在较多bug，请参考新的视频和代码，对bug进行了修复，并对代码做了详解**

视频教程：[手把手教你用tensorflow2训练自己的数据集_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1rX4y1A7N8)

代码地址：[vegetables_tf2.3: 基于tensorflow2.3开发的物体分类系统 (gitee.com)](https://gitee.com/song-laogou/vegetables_tf2.3)



### 一起来玩

> qq群：821429104
>
> b站：dejahu
>
> 视频教程：[手把手教你用tensorflow2训练自己的数据集_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1rX4y1A7N8)
>
> 博客链接：[手把手教你用tensorflow2.3训练自己的分类数据集_dejahu的博客-CSDN博客](https://blog.csdn.net/ECHOSON/article/details/117964477)

## 文件目录
```bash
# 数据下载地址 https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz
# 参考代码 https://tensorflow.google.cn/tutorials/images/classification
flower_tensorflow2.0
├─ data_read.py # 数据读取
├─ data_split.py # 数据切分
├─ images  # 图片文件
│    ├─ 123.jpg
│    ├─ init.png
│    ├─ logo.png
│    ├─ target.png
│    ├─ 主页面.png
│    └─ 关于.png
├─ window.py # ui界面
├─ models # 模型
│    ├─ cnn_flower.h5
│    └─ mobilenet_flower.h5
├─ readme.md 
├─ requirements.txt # 安装需求
├─ test_model.py # 模型测试
└─ train_model.py # 模型训练
```

## 如何使用
首先你需要git项目到你的本地

确定你的电脑已经安装好了PyQt5、tensorflow2.0以及opencv-python等相关软件，你可以执行下列命令进行安装
```
cd flower_tensorflow2.3
conda create -n flower_demo 
pip install -r requirements.txt
```

如果你想要重新训练你的模型，请执行
```
python train_model.py
```
如果你想要测试模型的准确率，请执行
```
python test_model.py
```
如果你想看看图形化的界面，请执行
```
python window.py
```


## 执行效果
图形化界面
![image-20201212161743464](images/main.png)

## 捐助
如果您觉得我的项目帮助了您，您可以给我一点小小的鼓励，您的鼓励将会是我进一步创作的动力！😁😁😁

![alipayx](images/wx.jpg)



![wxpayx](images/ali.jpg)