# Yolov3-windows的实现

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)


## 介绍

基于tensorflow及keras而改造的yolov3-windows实现



## 环境要求

```
TensorFlow1.4.0以上
Keras2.1
OpenCV3.3以上
h5py2.7
```

推荐使用Anaconda集成环境

```
pip install h5py
pip install opencv-python
```



## 下载yolov3.weight权重文件

- 由于tensorflow/Keras所支持的权重文件为h5格式，所以需将yolov3.weight进行转换
- 我已将其转换，可以从我的 [云盘](https://pan.baidu.com/s/1H8c5lIL1IMWwVdKjlDz4GQ)下载权重文件


###检测照片

```
python yolo.py
```

按要求输入Image FileName：

![IBHDTMW01Y}4W@4M69JNMEG](C:\Users\wp\Desktop\IBHDTMW01Y}4W@4M69JNMEG.png)


很快结果就出来了


![de3](C:\Users\wp\Desktop\de3.png)


效果很棒！！！


###检测视频

```
python yolo_video
```

先在yolov3.py中修改video_path


![NSC2_1ZAF2H9KN@61ZVW%{A](C:\Users\wp\Desktop\NSC2_1ZAF2H9KN@61ZVW%{A.png)


检测结果


![detect](C:\Users\wp\Desktop\detect.png)




##end--

