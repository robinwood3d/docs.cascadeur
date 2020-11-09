# 插值

本节介绍在关键姿势之间创建平滑的过渡。要了解有关创建关键姿势的信息，请参阅[上一节](drafting_creating_poses.md)。

此阶段使用的工具是：

- [插值](../Tools/TimelineTools/interpolation.md)
- [动画轨道](../Tools/TimelineTools/animation_tracks.md)
- [轨迹](../Tools/TimelineTools/trajectories.md)
- [IK和FK](../Tools/TimelineTools/interpolation.md/#IK与FK插值)

## 添加插值

插值用于在关键姿势之间创建平滑过渡。

![](https://cascadeur.com/images/category/2020/10/08/b8b82158f02ad63c7ef7edb715d58321.gif)  
*动画仅用关键帧表示（左）与添加贝塞尔曲线插值的相同动画（右）*

要创建插值区间：

1. 选择一系列帧
2. 选择插值类型

![](https://cascadeur.com/images/category/2020/10/08/d3b8e23001dc32961da0baf36dac47f6.gif)

### 插值类型

Cascadeur支持各种类型的插值。每种类型最适合特定任务。选择正确的插值类型对于创建令人信服的动画至关重要。

#### [贝塞尔插值](../Tools/TimelineTools/interpolation.md/#贝塞尔插值)

![](https://cascadeur.com/images/category/2020/10/08/d4d2ecf7ee05f38077791302c9b43f53.gif)

对象沿着由其在关键帧中的位置定义的曲线移动，在轨迹的开头加速，并在轨迹的末尾减速。

当在多个区间中选择这种类型的插值时，先前区间中的角色移动会影响后续区间，从而产生与惯性移动相似的效果。这可以使运动看起来更逼真，但是如果不需要此效果，请改用贝塞尔粘性插值类型。

这种类型的插值最适合有机的弓形运动。如果不确定要选择哪种类型，请使用此类型。

#### [贝塞尔粘性插值](../Tools/TimelineTools/interpolation.md/#贝塞尔粘性插值)

![](https://cascadeur.com/images/category/2020/10/08/c772a983211485bd2af57893cac2f7fe.gif)

此类型的工作方式与贝塞尔插值相同，但先前的移动对后续移动的影响较小。

#### [线性插值](../Tools/TimelineTools/interpolation.md/#线性插值)

![](https://cascadeur.com/images/category/2020/10/08/a1d2cdcf2b98df47b01ebb325e987ac7.gif)

对象以恒定的速度在指定的关键帧之间移动。

#### [步插值](../Tools/TimelineTools/interpolation.md/#步插值（默认）)

![](https://cascadeur.com/images/category/2020/10/08/ff99525c30267624ef8ad8b4428cc3ad.gif)

不计算中间值，动画对象仅更改其在关键帧中的位置和姿势。
这是默认选项。

在完整的动画中很少会遇到步插值，但是在某些情况下也可以使用步插值：例如，当您需要一个对象来立即改变位置时。

#### [固定插值](../Tools/TimelineTools/interpolation.md/#固定插值)

![](https://cascadeur.com/images/category/2020/10/08/c07c2c28045c47f8fc8e80f087800fb5.gif)

选择此类型后，您可以选择在插值区间的每一帧而不是仅关键帧上编辑角色姿势。这样，您可以在关键帧之间调整姿势，而无需创建其他关键帧。

添加插值区间的目的是了解每个动作所花费的时间。仅仅观察关键姿势很难理解这一点。

## 时间间隔和空间间距

插值与时间间隔和空间间距的概念密不可分。

时间间隔代表一个动作需要多长时间。

<table border="0" cellpadding="1" cellspacing="1" style="width:800px">
	<tbody>
		<tr>
			<td><img alt="" src="https://cascadeur.com/images/category/2020/10/08/f4e1af25519b0a89a05ab1a5033c0083.gif" style="height:271px; width:400px"></td>
			<td><img alt="" src="https://cascadeur.com/images/category/2020/10/08/3fedac7fada893fadf705856e94806f0.gif" style="height:271px; width:400px"></td>
		</tr>
	</tbody>
</table>
	
*具有相同关键帧集但时序不同的两个动画。注意改变时间如何改变动画的整体感觉*

为动画选择正确的时间间隔对于创建逼真的动作非常重要。

时间间隔可以通过以下方式调整：

- 在[**时间轴**](../Interface/timeline.md)上移动[**关键帧**](../Tools/TimelineTools/keyframes.md)
- 分别通过按\+和\-来**添加**或**删除**帧
- 使用[轨道拉伸模式](../Tools/TimelineTools/track_stretching_mode.md)
    - 当您需要更改整个序列的长度时，请使用此模式

空间间距是指动画对象的位置在帧之间如何变化。

![](https://cascadeur.com/images/category/2020/10/08/0a851c25c4130e902de70c8c88a8c4d6.gif)

通过控制空间间距，您可以更改动画的感觉。您可以根据动画的需要来产生恒定的速度，加速或减速，停止或开始运动的感觉。

## 轨迹

![](https://cascadeur.com/images/category/2020/10/08/44889b2715ab71b2dded4323e20f7f05.png)

一段轨迹显示了所选对象在所选区间内的运动路径。

轨迹对于理解动画的空间间距很有用。如果需要，它们也可以用于更改间距。

要启用轨迹：

1. 选择要为其启用轨迹的控制器

2. 在[**时间轴**](../Interface/timeline.md)上选择一个区间

3. 此时[**视口**](../Interface/viewport.md)窗口将在此区间内显示这些控制器的轨迹

4. 单击**Set Trajectory Interval**。这样，无论选择的帧如何，您选择的轨迹都将可见

Cascadeur可以用不同的方式渲染轨迹。在[这里](../Tools/AnimationTools/trajectories.md/#轨迹渲染模式)了解他们。

### 编辑轨迹

1. 启用轨迹编辑模式  
![](https://cascadeur.com/images/category/2020/10/08/b225aead44437497544b776e7eeaafe7.png)

2. 在轨迹上选择一个关键帧  
![](https://cascadeur.com/images/category/2020/10/08/87cc0aae6be86db6a40b8d97e0e76865.gif)

3. 使用[操纵器](../Tools/AnimationTools/manipulators.md)编辑其位置  
![](https://cascadeur.com/images/category/2020/10/08/fb3926667e59cee5ce4ba576bedeaf66.gif)

轨迹也可以缩放：

1. 选择几个关键帧（整个轨迹或轨迹的一部分）

2. 应用[缩放](../Tools/AnimationTools/manipulators.md/#3.-缩放)操纵器

![](https://cascadeur.com/images/category/2020/10/08/397d59cb435ce4c55f82044d6a60a38d.gif)

## 双关键帧

在相邻帧上创建一对关键帧可极大地改变轨迹。

![](https://cascadeur.com/images/category/2020/10/08/8bd4620708b31af5e5b58b6f3871c2d0.gif)  
*注意轨迹如何变化。*

到目前为止，切线**无法在视口中可视化**。

切线的特性取决于相邻区间上使用的插值类型：

- 贝塞尔粘性插值可基于两个相邻帧计算切线
- 普通贝塞尔插值计算切线，以便在整个区间上保持平滑。

## IK和FK

Cascadeur支持正向和反向运动学。

<table border="0" cellpadding="1" cellspacing="1" style="width:800px">
	<tbody>
		<tr>
			<td><img alt="" src="https://cascadeur.com/images/category/2020/10/08/70bba4c330ecfb8e4191bf8dd83a80a2.png" style="height:305px; width:439px"></td>
			<td><img alt="" src="https://cascadeur.com/images/category/2020/10/08/7905996a64b4622521a23903b34df259.png" style="height:305px; width:449px"></td>
		</tr>
	</tbody>
</table>

反向（左）和正向（右）运动的相同运动

反向和正向运动学模式之间的交替可用于解决某些种类的动画问题：

![](https://cascadeur.com/images/category/2020/10/08/d0d7eea1e5de8379792a0f4fc9a3c3ce.gif)

## [动画轨道](../Tools/AnimationTools/animation_tracks.md)

有时，您可能需要对角色的不同部分使用不同的关键帧和/或插值类型。

这可以通过创建多个动画轨迹并将角色的各个部分分配给它们来完成。

1. 在身体部位中选择要移至新轨道的控制器

2. 单击[**时间轴**](../Interface/timeline.md)上的**添加轨道**按钮

![](https://cascadeur.com/images/category/2020/10/08/d0a28b73106b9adfa33c3f03ee88ba50.gif)

应该注意的是，错误地处理动画轨道可能会导致插值无法按预期工作。特别是当某些轨道使用正向运动学时。

因此，应谨慎使用轨道。仅在必要时创建其他轨道。