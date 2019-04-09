# Mask_RCNN学习整理

#### Mask_RCNN学习系列博客
博客中介绍的代码主要是`./mrcnn`中的文件，它们是模型构建的主干，以及部分`./sample`中的文件，它们展示了如何训练并测试网络<br>
[『计算机视觉』Mask-RCNN_论文学习](https://www.cnblogs.com/hellcat/p/9749538.html)<br>
[『计算机视觉』Mask-RCNN_项目文档翻译](https://www.cnblogs.com/hellcat/p/9759328.html)<br>
[『计算机视觉』Mask-RCNN_推断网络其一：总览](https://www.cnblogs.com/hellcat/p/9789879.html)<br>
[『计算机视觉』Mask-RCNN_推断网络其二：基于ReNet101的FPN共享网络暨TensorFlow和Keras交互简介](https://www.cnblogs.com/hellcat/p/9802349.html)<br>
[『计算机视觉』Mask-RCNN_推断网络其三：RPN锚框处理和Proposal生成](https://www.cnblogs.com/hellcat/p/9811301.html)<br>
[『计算机视觉』Mask-RCNN_推断网络其四：FPN和ROIAlign的耦合](https://www.cnblogs.com/hellcat/p/9814975.html)<br>
[『计算机视觉』Mask-RCNN_推断网络其五：目标检测结果精炼](https://www.cnblogs.com/hellcat/p/9821011.html)<br>
[『计算机视觉』Mask-RCNN_推断网络其六：Mask生成](https://www.cnblogs.com/hellcat/p/9837595.html)<br>
[『计算机视觉』Mask-RCNN_推断网络终篇：使用detect方法进行推断](https://www.cnblogs.com/hellcat/p/9848096.html)<br>
[『计算机视觉』Mask-RCNN_锚框生成](https://www.cnblogs.com/hellcat/p/9854736.html)<br>
[『计算机视觉』Mask-RCNN_训练网络其一：数据集与Dataset类](https://www.cnblogs.com/hellcat/p/9881322.html)<br>
[『计算机视觉』Mask-RCNN_训练网络其二：train网络结构](https://www.cnblogs.com/hellcat/p/9907837.html)<br>
[『计算机视觉』Mask-RCNN_训练网络其三：训练Model](https://www.cnblogs.com/hellcat/p/9987442.html)<br>
将本工程改造为关键点检测项目：<br>
[Mask_RCNN_KeyPoints](https://github.com/Hellcatzm/Mask_RCNN_KeyPoints)<br>
记录博客：<br>
[『计算机视觉』Mask-RCNN_从服装关键点检测看KeyPoints分支](https://www.cnblogs.com/hellcat/p/10105465.html)<br>

#### 相关知识点学习
[『TensorFlow』分类问题与交叉熵](https://www.cnblogs.com/hellcat/p/8568005.html)<br>
[『计算机视觉』感受野和anchor](https://www.cnblogs.com/hellcat/p/9946340.html)<br>
[『计算机视觉』FPN特征金字塔网络](https://www.cnblogs.com/hellcat/p/9741213.html)<br>
[『计算机视觉』经典RCNN_其一：从RCNN到Faster-RCNN](https://www.cnblogs.com/hellcat/p/9629942.html)<br>
[『计算机视觉』经典RCNN_其二：Faster-RCNN](https://www.cnblogs.com/hellcat/p/9678467.html)<br>

#### 训练和测试
在上面博客中其实已经有介绍相关脚本的使用方式，这里还是更直接的给出代码链接:<br>
模拟训练模型脚本：      [./sample/shapes/train_shapes.ipynb](https://github.com/Hellcatzm/Mask_RCNN/blob/master/samples/shapes/train_shapes.ipynb)<br>
coco数据训练相关：      [./samples/coco](https://github.com/Hellcatzm/Mask_RCNN/tree/master/samples/coco)<br>
coco预训练模型测试脚本： [./sample/demo.ipynb](https://github.com/Hellcatzm/Mask_RCNN/blob/master/samples/demo.ipynb)<br>
