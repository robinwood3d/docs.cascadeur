# 复制工具

这套工具可用于在帧和场景之间复制对象的位置和对象的空间方向。

![](https://cascadeur.com/images/category/2020/03/11/3040e19a26071db5d7a3cc1bc6c9ed57.png)

## 控制器复制操作

使用此功能可以将所选控制器（或一组控制器）的位置和空间方向从一帧复制到另一帧。

**Copy (Ctrl + C)** -复制选择的帧中所选控制器的位置

**Paste (Ctrl + V)** -将所选控制器的位置粘贴到当前帧

**Paste into interval (Ctrl + Alt + V)** -将所选控制器的位置粘贴到选择的帧所属的区间（区间上的插值模式更改为[**固定插值**](../TimelineTools/interpolation.md/#固定插值)）

可以在[**Global**，**Local**或**Relative**](manipulators.md)模式下复制对象。可以在[**Settings**](../../Interface/settings.md/#Copier)选项卡的**Copier**面板上选择这些模式。

![](https://cascadeur.com/images/category/2020/03/11/64dff3e9c59e944bcc9501423a6ddd96.png)

- 在**全局**模式下，复制的对象将保留其在场景中的位置。
- 在**本地**模式使用相对于其父对象的位置。
- 在相**对**模式使用相对于轴心的对象位置，可以**右键单击**一个控制器来手动设置。此选项在[**本地坐标模式**](manipulators.md/#本地和全局模式)下最有用。

***注意：*** 如果场景包含相同的对象集，则也可以在场景之间复制对象。

## 区间复制操作

此功能按选定的区间复制选定对象的所有位置

- **Copy Interval (Ctrl + Shift + C)** -在所选区间上复制所选对象的位置
- **Paste Interval (Ctrl + Shift + V)** -将所选对象的位置与先前复制的对象粘贴在一起

## 时间轴区间复制操作

- **Copy timeline interval** -保存[时间轴](../../Interface/timeline.md)上一系列帧及其插值模式
- **Paste timeline interval** -将保存的区间粘贴到时间轴上的任何位置。如果保存的区间不适合时间轴的选定部分，则仅粘贴适合的帧

## Tracks Hierarchy

此选项使您可以从场景中复制动画轨道（**Copy Tracks Hierarchy**）并将其粘贴（**Paste Tracks Hierarchy**）到另一个场景

此功能要求两个场景都包含相同的对象集

## 使用示例

[附加物件]()

[转移动画]()

## 参阅

[时间轴](../../Interface/timeline.md)

[关键帧](../TimelineTools/keyframes.md)

[插值](../TimelineTools/interpolation.md)