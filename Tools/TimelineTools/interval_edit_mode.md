# 区间编辑模式

![](https://cascadeur.com/images/category/2020/02/21/9a82f921e4f6ffbc8bb7d40ee1c37ce0.png)

操纵器可用于在一帧或一个区间上进行更改。可以在工具栏上选择：

## 当前帧模式（默认）

这是默认模式。启用该选项后，您对场景对象所做的所有调整只会影响当前帧。

## 区间编辑模式

选择此模式时，对场景中某对象的调整会应用到所选区间中该对象的每个位置。例如在某一帧中移动一个对象，那么该对象在所选区间的其他帧中也会做出相应移动。

![](https://cascadeur.com/images/category/2019/08/15/5251fe16a511f49dcbbb7565839973c5.gif)

使用此模式时，视口窗口将标记为**红色**边框。

在此模式下编辑区间时，其插值类型将更改为[**固定**](interpolation.md/#固定插值)类型。发生这种情况是因为变换不仅应用于关键帧，而且还应用于每个帧。

如果要避免这种情况，请在[**Settings**](../../Interface/settings.md)选项卡中禁用**更改时固定插值**参数 。这样变换将仅应用于关键帧。

## 固定轴心区间编辑模式

在此模式下，操纵器也应用于选中区间的每一帧，但是是相对于某个轴心进行变换，例如当前帧所选对象的位置。在此模式下调整区间还会将其插值类型更改为[**固定**](interpolation.md/#固定插值)类型。

![](https://cascadeur.com/images/category/2019/08/15/5006f1ae9f839c8d463f47603a7a9dd9.gif)

## 设置

区间编辑模式的设置可以在**Settings**面板上的**Interval Edit Mode**选项卡上找到：

![](https://cascadeur.com/images/category/2020/09/29/5a8b4808d8f6d06d63ab5e3b31536789.png)

### Curve

此选项设置在编辑过程中如何影响轨迹。三种模式可用：

#### Step

![](https://cascadeur.com/images/category/2020/09/29/fdfce453832bfc5de844140ea076d62e.gif)

此为默认设置。如果选择此选项，则轨迹将作为单个实体移动，并且不会以任何方式变形。

#### Linear

![](https://cascadeur.com/images/category/2020/09/29/678bb3b6dce6374db571b7bc833f4ef1.gif)

如果选择此选项，则轨迹将以线性方式变形。

#### Bezier

![](https://cascadeur.com/images/category/2020/09/29/3b3468f543db85e84e16b4da66b5a60c.gif)

曲线如果使用此选项，则使用贝塞尔曲线样条线使轨迹变形。

这些设置也会影响旋转：

![](https://cascadeur.com/images/category/2020/09/29/d4cdede77e2c597a79bc580199cf4c81.gif)

*在区间编辑模式下 启用了**Linear**设置的旋转。*