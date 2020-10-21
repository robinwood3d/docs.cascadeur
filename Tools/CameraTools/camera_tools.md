# 相机工具

相机定义了一个可以从中查看场景的视点。

![](https://cascadeur.com/images/category/2020/08/20/ded722773943f3a21a922db3b94ccfa7.png)

## 添加相机

要将摄像机添加到场景，请从**Object**菜单中选择**Add camera**：

![](https://cascadeur.com/images/category/2020/08/20/cba319c5f5bfd6a66ee4044235cce183.png)

默认情况下，摄像头不会显示在视口中。若要使摄像机可见，请在**Visible**菜单中勾选**Camera Object**：

![](https://cascadeur.com/images/category/2020/08/20/5a2de9ed6201927ed5e60756e3451552.png)

## 相机视角

要通过相机查看场景：

1. 选择相机
2. 单击**工具栏**上的**对齐到相机**按钮  
![](https://cascadeur.com/images/category/2020/08/20/a0c6c916eba4144d4af9e5f565a334da.png)

## 相机设定

在大纲视图窗口的**Camera**选项卡上，可以对选定相机进行设置调整：

![](https://cascadeur.com/images/category/2020/08/20/c1a7888f17394377433dcd5c13f76e24.png)

**Field of view (视野)**  
设置所选摄像机的视野

**Rotation offset (旋转偏移)**  
相机额外旋转。该参数包括三个欧拉角，可用于更改相机方向而无需更改其变换旋转。

**Aspect ratio height (长宽比高度)** 和 **Aspect ratio width (长宽比宽度)**  
这些参数定义相机拍摄的图像的长和宽的比例

## 相机控制

可以使用[**工具栏**](../../Interface/toolbar.md)上面板上专用的按钮设置相机行为 。

![](https://cascadeur.com/images/category/2019/06/14161ff5473b83bc71e85f467e6343ab55.jpg)

**跟踪对象**  
如果启用此按钮，则摄像机将跟随所选对象

**跟踪选定对象**
如果启用此按钮，则摄像机将跟随对象的选定部分（控制器或网格）

**对齐到相机**  
按此按钮可将视角对齐到当前选择的相机

**相机聚焦**  
此按钮将照相机聚焦在当前选择的对象上。快捷键为![](https://cascadeur.com/images/category/2019/06/042001c533574264e44ebf97f2de8026bf.png)

## 相机动画

可以像其他任何对象一样对摄像机进行动画处理：通过创建[**关键帧**](../TimelineTools/keyframes.md)并设置它们之间的[**插值区间**](../TimelineTools/interpolation.md)。

## 导出相机

跟其他对象一样，可以将相机导出为FBX和Collada格式。

在[导出](../../GettingStarted/export_fbxdae.md)页面上描述了导出场景相关信息。

但是：
到目前为止，Collada格式不支持相机动画。如果需要导出相机动画，请改用FBX。

## 参阅

[第一人称相机](first_person_camera.md)

[场景](../../GettingStarted/scenes.md)

[视口](../../Interface/viewport.md)