# 轨迹

>**本页内容**
>- [轨迹渲染模式](#轨迹渲染模式)
>- [轨迹固定模式](#轨迹固定模式)
>- [轨迹编辑模式](#轨迹编辑模式)
>- [锁定轨迹区间](#锁定轨迹区间)

![](https://cascadeur.com/images/category/2019/05/15893a95aa125f56e25953de252ec3e3e4.gif)

轨迹表现为一条线，它显示了选中对象在所选区间内的运动路径。

要显示轨迹，请在[视口](../../Interface/viewport.md)中选择一个对象，然后在[时间轴](../../Interface/timeline.md)上选择一个区间。

## 轨迹渲染模式

可以在顶部的UI面板上找到用于切换轨迹渲染模式的工具

![](https://cascadeur.com/images/category/2020/03/11/411430e6462858f2bcb43bca7b19f93f.png)

### 1. 显示选定的父轨迹

![](https://cascadeur.com/images/category/2019/07/24/1c553190079671c07b5f9a96fa01a12c.jpg)

如果选择一组对象，则仅渲染层级中最高的对象的轨迹

### 2. 显示所有选定的轨迹

![](https://cascadeur.com/images/category/2019/07/24/49b490ad3e760ce01f860fda8f2d12eb.jpg)

如果要显示每个选定点控制器或对象的轨迹，请选择此选项

### 3. 显示选中的连线轨迹

![](https://cascadeur.com/images/category/2019/07/24/3268a9e97e4e384a22971b48fdb14ab5.jpg)

如果启用此选项，轨迹将显示选中的点控制器的连线的位置

### 4. 显示选定的对象和连线轨迹

![](https://cascadeur.com/images/category/2019/07/24/400652212c333c412e9e8ed28125a95e.jpg)

该模式下将显示选中的点控制器以及其连线的位置

点控制器显示为绿色点。当前帧的点控制器用黄圈来标记。

### 5. 仅显示关键帧

![](https://cascadeur.com/images/category/2019/07/24/3cb67cda47df5193b8a2b26983a197df.jpg)

此模式下，仅显示点控制器的在关键帧上的轨迹

## 轨迹固定模式

此选项用于*固定*轨迹。与常规轨迹不同，即使取消选择相应的对象，固定轨迹在视口中仍然可见，仅当禁用**轨迹固定模式**按钮时才会消失。

![](https://cascadeur.com/images/category/2020/03/11/6adad6d4cd17a2cbd0936fce1f9c5a8a.png)

此功能包括多种模式：

### 1. 固定所有轨迹

此按钮固定每个选定控制器的轨迹

### 2. 固定连线轨迹

此按钮固定所选控制器的连线的位置（类似于“**显示所选连线轨迹**”选项）

### 3. 固定连线与控制器轨迹

此按钮固定控制器和控制器连线的位置


## 轨迹编辑模式

![](https://cascadeur.com/images/category/2020/03/11/2ca9d63ea4d7d5f02abe033fc785eb2b.png)

要编辑轨迹，您需要启用“**轨迹编辑模式**”按钮。之后您可以通过应用标准操纵器来移动，旋转和以其他方式调整轨迹上的任何点。

**注意：** 如果您在插值间隔中编辑一帧或多帧的轨迹，则此间隔的插值模式将切换为[固定](../TimelineTools/interpolation.md/#固定插值)

## 锁定区间轨迹

![](https://cascadeur.com/images/category/2020/03/11/293ee3707dc8c13adfdcc1d60144f1e9.png)

按下此按钮，当您选择另一个区间时轨迹不会消失


## 参阅

[关键帧](../TimelineTools/keyframes.md)

[插值](../TimelineTools/interpolation.md)