图像增强软件
===========================

<div align="center">

[![BILIBILI](https://raw.githubusercontent.com/Fafa-DL/readme-data/main/Bilibili.png)](https://space.bilibili.com/46880349)
![](https://img.shields.io/badge/Image%20Augmentation-v3.1-brightgreen)
[![GitHub forks](https://img.shields.io/github/forks/Fafa-DL/Image-Augmentation)](https://github.com/Fafa-DL/Image-Augmentation)
[![GitHub stars](https://img.shields.io/github/stars/Fafa-DL/Image-Augmentation)](https://github.com/Fafa-DL/Image-Augmentation)

![main](https://raw.githubusercontent.com/Fafa-DL/readme-data/main/imgaug/main_3.0.png)

</div>

****
	
|B站主页|CSDN|视频教程|公众号获取下载|直接下载|技术探讨群|
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|[啥都会一点的研究生](https://space.bilibili.com/46880349)|[啥都生](https://blog.csdn.net/zzh516451964zzh)|[查看教程](https://www.bilibili.com/video/BV1Sv4y1S7yb)|啥都会一点的研究生->资源合集->课程资源->序号00|[v2.5](https://github.com/Fafa-DL/Image-Augmentation/releases/download/V2.5/ImgAug2.5.exe)<br/>[v3.4](https://github.com/Fafa-DL/Image-Augmentation/releases/download/V3.4/ImgAug3.4.exe)|[一群：78174903](https://jq.qq.com/?_wv=1027&k=lY5KVICA)<br/>[三群：584723646](https://jq.qq.com/?_wv=1027&k=bakez5Yz)|

****
## 我维护的其他项目

- [**开箱即用，涵盖主流模型的图像分类|主干网络学习/对比/魔改项目**](https://github.com/Fafa-DL/Awesome-Backbones)
[![GitHub stars](https://img.shields.io/github/stars/Fafa-DL/Awesome-Backbones)](https://github.com/Fafa-DL/Awesome-Backbones)
[![GitHub forks](https://img.shields.io/github/forks/Fafa-DL/Awesome-Backbones)](https://github.com/Fafa-DL/Awesome-Backbones)
- [**一键转换与编辑图像标注文件软件，极大提高效率**](https://github.com/Fafa-DL/LabelConvert)
[![GitHub stars](https://img.shields.io/github/stars/Fafa-DL/LabelConvert)](https://github.com/Fafa-DL/LabelConvert)
[![GitHub forks](https://img.shields.io/github/forks/Fafa-DL/LabelConvert)](https://github.com/Fafa-DL/LabelConvert)

## 更新日志

**`2023.12.02`**
- 修复Issue中Numpy不兼容相关的高频问题

**`2023.05.08`**
- 修复V3.3版本按新序号命名时输出多余`.`的问题
- 说明：遇到问题尽量把信息贴全方便复现溯源！

**`2022.12.03`, [V3.3](https://github.com/Fafa-DL/Image-Augmentation/releases/download/V3.3/ImgAug3.3.exe)发布** 
- 修复由**iaa.imgcorruptlike**引起的错误，支持`imgcorruptlike`增强功能
- 修复增强后的路径与原始增强路径一致引起的错误（但非常不建议这样做）
- 修复文件命名中符号兼容问题，`路径与文件名请避免使用中文！！！`

**`2022.11.27`, [V3.2](https://github.com/Fafa-DL/Image-Augmentation/releases/download/V3.2/ImgAug3.2.exe)发布** 
- 修复常规错误
- 日志文件与弹窗包含更多信息供debug
- **输出序号若为空，由原来从序号1开始命名更改为默认使用原文件名**

**`2022.11.06`，[V3.1](https://github.com/Fafa-DL/Image-Augmentation/releases/download/V3.1/ImgAug3.1.exe)发布** 
- 支持`ppm, bmp, pgm, tif, tiff`格式
- 更新Python及相应库至最新版本，处理速度更快

**`2022.10.29`** 
- 3.0版本更新，2.x系列版本详见[此处](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/readme/v2.md)
- 集成ImgAug库所有图像增强方式，用户可灵活设计专属增强方案（仅支持png、jpg、jpeg）
- 提升兼容性，修复因文件读取、增强结果越界、图像类型不符合等引起的闪退问题
- 新增日志模块，软件发生错误时可在`运行目录下的log/log.log`中查看原因，对症下药

## 增强方式

- [meta](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/meta.rst)
- [arithmetic](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/arithmetic.rst)
- [artistic](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/artistic.rst)
- [blend](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/blend.rst)
- [blur](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/blur.rst)
- [collections](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/collections.rst)
- [color](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/color.rst)
- [contrast](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/contrast.rst)
- [convolutional](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/convolutional.rst)
- [edges](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/edges.rst)
- [flip](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/flip.rst)
- [geometric](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/geometric.rst)
- [imgcorruptlike](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/imgcorruptlike.rst)
- [pillike](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/pillike.rst)
- [pooling](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/pooling.rst)
- [segmentation](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/segmentation.rst)
- [size](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/size.rst)
- [weather](https://github.com/Fafa-DL/Image-Augmentation/blob/master/doc/source/overview/weather.rst)

![demo](doc/images/examples_grid.jpg)

## 参考
```
https://github.com/aleju/imgaug
```
