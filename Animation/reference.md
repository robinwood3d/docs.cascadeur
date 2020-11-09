# 参考

开始制作动画之前，建议您研究一些参考资料。例如，你想要为某个动作制作动画时，可以先观看真人做该动作的视频。这有助于更好地了解整个运动及其元素。

一旦了解了运动的外观以及构成的姿势之后，就可以创建动画的草图了。这可以通过在动作的关键点定义几个关键姿势来完成。

## 如何设置动画参考

### 添加参考平面

1. 从**Object**菜单中选择**Add Plane**以将平面添加到场景。  
![](https://cascadeur.com/images/category/2020/08/20/b4823c33a01364ed2ccb3c9346b11065.png)

2. 切换到网格模式  
![](https://cascadeur.com/images/category/2020/08/20/977671479fb213f50194d958a268f62e.png)

3. 选择平面  
![](https://cascadeur.com/images/category/2020/08/20/04095ce82a78d0d26b597b4c6dc7fb39.gif)

4. 使用[**操纵器**](../Tools/AnimationTools/manipulators.md)调整平面的大小和位置。  
通常，我们希望将参考平面放置在角色后面。

### 添加视频

现在我们需要将视频添加到平面上。

Cascadeur当前不支持视频纹理，因此我们需要将视频另存为图像序列。这可以在任何视频编辑软件中完成。

最终的图像序列应如下所示：

![](https://cascadeur.com/images/category/2020/06/09/ad9c57c730d4ee541af0598f157f35b8.jpg)

将此序列添加到平面：

1. 选择参考平面

2. 单击绑定纹理按钮  
![](https://cascadeur.com/images/category/2020/06/09/18cf4857263b79dedcf0fc277cfaa573.png)

3. 选择图像序列的**每个**文件

4. 此时该图像序列会应用于参考平面。序列中的一个图像对应动画的一帧  
![](https://cascadeur.com/images/category/2020/06/09/e0dcdc8eced36270ac414bba62ed4300.gif)

### 准备动画参考

默认情况下，纹理在[**点控制器**](../Rig/RigStructure/point_controllers.md)模式下不可见。要解决此问题：

1. 切换到**点控制器**模式

2. 右键单击编辑模式选择面板以打开**Visible**菜单

3. 启用**Textures**

![](https://cascadeur.com/images/category/2020/08/20/c1d1da9ae276255249f6a3592f2deeef.gif)

您还可以设置动画参考的起始帧：

1. 切换到**网格模式**

2. 选择参考平面

3. 在[**大纲视图**](../Interface/outliner.md)中，设置起始帧  
![](https://cascadeur.com/images/category/2020/08/20/1436116712aad655cfba9f692809a7e0.png)

此时动画将在您设置的帧处开始播放。

## 参阅

[动画草图](../Animation/drafting_creating_poses.md)

[编辑模式](../GettingStarted/edit_modes.md)

[网格模式](../Rig/RigStructure/meshes.md)

[大纲视图](../Interface/outliner.md)