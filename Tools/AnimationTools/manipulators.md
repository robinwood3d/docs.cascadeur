# 操纵器

>**本页内容**
>- [移动](#1.-移动)
>- [旋转](#2.-旋转)
>- [缩放](#3.-缩放)
>- [全局和局部模式](#局部和全局模式)
>- [尾部模式](#尾部模式)
>- [使用操纵器](#使用操纵器)
>- [区间编辑模式](#区间编辑模式)
 
**操纵器**是用于调整角色姿势的工具。可以在[**工具栏**](../../Interface/toolbar.md)上的专用面板上选择它们。

![](https://cascadeur.com/images/category/2020/02/21/a2ef26828c0d706d0700dabacc62531f.png)

*工具栏上用于选择**操纵器**的面板*

## 1. 移动

**快捷键：**![](https://cascadeur.com/images/category/2019/06/247d2219b636f4e6c20d9d8891af05dec3.png)

![](https://cascadeur.com/images/category/2019/07/23/7cf6bf2c78c49443ebe15ef3bd1177a0.gif)

*移动操纵器的使用示例， 用于在场景中移动对象*

用于沿坐标轴移动所选对象。要移动对象，请将鼠标指针放在某个轴上（此时该轴会显示为黄色），按住 ![](https://cascadeur.com/images/category/2019/06/04bba9a4c2865c96fa85a7af70a99a5aba.png) 并移动指针。

两个轴之间的正方形表示由这些轴形成的坐标平面。使用它可沿相应平面移动对象。

将鼠标放在工具中心的圆圈上，并按住 ![](https://cascadeur.com/images/category/2019/06/04bba9a4c2865c96fa85a7af70a99a5aba.png) 可在屏幕空间周围自由移动对象。

## 2. 旋转

**快捷键：**![](https://cascadeur.com/images/category/2019/06/04a2af2d1fca6c55cae10e3555ab8c94cd.png)

![](https://cascadeur.com/images/category/2019/07/23/037996e41bdf77c1b03b086f79fff19c.gif)

*旋转操纵器的使用示例，用于改变场景中对象的空间朝向*

该操纵器用于在坐标轴上旋转选定的对象。轴表示为圆圈。

要旋转对象，请将鼠标指针放在代表相应坐标轴的圆圈上，按住 ![](https://cascadeur.com/images/category/2019/06/04bba9a4c2865c96fa85a7af70a99a5aba.png) 并移动指针。

旋转所围绕的轴心可以手动设置。默认情况下，所选对象的中心用作轴心点（如果选择了多个对象，则将轴心分配给对象层级中最高的对象）。

## 3. 缩放

该工具更改所选对象的尺寸。

在缩放过程中，Cascadeur会尝试保留选定对象之间的距离，就像其他任何类型的编辑一样。

缩放所相对的轴心可以手动设置。

缩放操纵器通常用于编辑对象[轨迹](trajectories.md)

## 局部和全局模式

**快捷键**：~

![](https://cascadeur.com/images/category/2020/02/21/dc451853a4d8488c178e99b3c82ea04e.png)

![](https://cascadeur.com/images/category/2019/07/24/cae06f977b3fccb7bb00d1c7e0d9407b.png)

*在**本地**（左）和**全局**（右）模式下的**移动**操纵器*

上述每个操纵器都可以在**本地**或**全局**模式下运行。

在**全局**模式下，场景中每个对象都相对于世界坐标系进行移动，旋转或者缩放。

在**局部**模式中，对象的变换都应用于对象的本地坐标系，对象本地坐标系取决于对象的当前位置。

上述两种模式都会同时应用于所有的操纵器。

## 尾部模式

快捷键：Ctrl+Alt+Q

![](https://cascadeur.com/images/category/2020/02/21/23ea9bc6d021cdc674f70e8795b3d404.png)

![](https://cascadeur.com/images/category/2019/07/24/e01beafe5140e717670f91263a0c23d5.gif)

此选项为对象旋转添加“尾部”效果：旋转对象时，其所有子对象都随其旋转，就像尾巴一样。

尾部模式可以独立于其他操纵器设置为全局或局部。

要更改旋转的轴心点：

1. 选择要旋转的每个对象
2. 使用![](https://cascadeur.com/images/category/2019/11/06/fc464709c3873e750c7196304dff7f3c.png)单击某个控制器将旋转轴心点移动到该处

![](https://cascadeur.com/images/category/2019/05/08b4a8061132a5aecf6e513b1c4042743b.gif)

## 使用操纵器

- **选择**

使用![](https://cascadeur.com/images/category/2019/06/04bba9a4c2865c96fa85a7af70a99a5aba.png)，您可以选择操纵器的任何部分，比如轴，坐标平面或中心的圆，且一次只能选择一个。

- **使用**

选择操纵器后，在[视口](../../Interface/viewport.md)窗口中按住![](https://cascadeur.com/images/category/2019/06/04244e1c5cd5442c2c91b26efde9c8b884.png)并移动鼠标指针以移动选定的对象。如果选择了轴或坐标平面，则对象将沿其移动；否则，对象将沿其移动。如果选择了中心圆，则可以在屏幕空间中自由移动对象。

- **微调**

在对象上使用操纵器时按住![](https://cascadeur.com/images/category/2019/11/06/0ec16345c0425ae0c74017848ee42582.png)将使对象移动速度比正常速度慢十倍。这可用于以更高的精度操纵对象。

- **调整大小**

您还可以在[视口](../../Interface/viewport.md)窗口中调整操纵器的显示尺寸，只需要按住![](https://cascadeur.com/images/category/2019/06/048c2d5940e71fb29fa47b582d8433327e.png)并按住![](https://cascadeur.com/images/category/2019/06/04e50c952b8992be1e15f64bb7a23fe4e2.png)移动鼠标。

- **关闭**

要关闭操纵器，请选择[**选择**](selector_tool.md)模式或按**快捷键Q**

## 区间编辑模式

操纵器可用于在一帧或区间内进行编辑。在[区间编辑模式](../TimelineTools/interval_edit_mode.md)页面上查看相关信息。

## 参阅

[关键帧](../TimelineTools/keyframes.md)

[插值](../TimelineTools/interpolation.md)

[区间编辑模式](../TimelineTools/interval_edit_mode.md)
