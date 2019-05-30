# 基于端到端深度学习的自动驾驶系统
## 效果

<p align="center">
  <img src="image/1.png">
</p>

<p align="center">
  <img src="image/2.png">
</p>

<p align="center">
  <img src="image/3.png">
</p>

<p align="center">
  <img src="image/4.png">
</p>

<p align="center">
  <img src="https://github.com/lyzMaster/deepgta5/raw/master/models/image/drive.gif">
</p>


## 使用
`python drive.py`

打开[远程遥控器](https://www.pixeldesert.com/console/)，控制开始或结束

## 神经网络架构
<p align="center">
<img src="models/image/fx.jpg">
</p>
#### 总架构
<img src="models/image/full.png">

#### 主模型(NVDIA)
<img src="models/image/main_model.png">

#### 路径模型
<img src="models/image/ladar_model.png">


## 使用的工具
控制GTA5中的汽车运行：使用[DeepGTAV](https://github.com/aitorzip/DeepGTAV)控制车辆速度，以及转弯角度。

绘制卷积神经网络图像：[draw_convnet](https://github.com/gwding/draw_convnet)，keras的plot_model函数