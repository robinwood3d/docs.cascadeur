# 过滤器

>**本页内容**
>- [过滤器类型](#过滤器类型)
>   - [引向前一帧位置](#引向前一帧位置)
>   - [引向惯性位置](#引向惯性位置)
>   - [引向中间位置](#引向中间位置)
>   - [引向反向惯性位置](#引向反向惯性位置)
>   - [引向下一帧位置](#引向下一帧位置)
>   - [引向插值位置](#引向插值位置)
>   - [引向本地插值位置](#引向本地插值位置)
>   - [角动量](#角动量)
>- [使用过滤器](#使用过滤器)

过滤器是根据对象在相邻帧中的位置来调整其位置的工具。通过应用过滤器，您可以为动画添加惯性，平滑对象的轨迹或修复动画错误。

过滤器可用于快速调整角色姿势和动画序列。

截至目前，只能使用快捷键使用过滤器功能。

## 过滤器类型

### 引向前一帧位置

快捷键：![](https://cascadeur.com/images/category/2019/06/0402a8b90ef0976f0f0a8fd908c8671923.png)

此过滤器将所选对象移动到靠近前一帧的位置。

### 引向惯性位置

快捷键：![](https://cascadeur.com/images/category/2019/06/0456d66fd38988e4d0103d535fad575b12.png)

该过滤器将所选对象移动到更靠近其惯性位置的位置，这些位置是根据先前帧中的位置计算得出的。

### 引向中间位置

快捷键：![](https://cascadeur.com/images/category/2019/06/041db59736c474c6ec19a51390983a9395.png) 

该过滤器将选定的对象移动到更靠近上一帧和后续帧的平均位置。

### 引向反向惯性位置

快捷键：![](https://cascadeur.com/images/category/2019/06/04ddf780df862a3ff1a3030d90309642a2.png)

该过滤器将所选对象移动到更靠近其惯性位置的位置，这些位置是根据后续帧中的位置计算得出的。

### 引向下一帧位置

快捷键：![](https://cascadeur.com/images/category/2019/06/042e5a82c1929dccd711d1924ff9c86984.png)

将所选对象移近下一帧中的位置。

### 引向插值位置

快捷键：![](https://cascadeur.com/images/category/2019/06/045dddd57c2cce49fdef8174ed6cec953f.png)

将选定的对象移近最近帧中的平均位置。

### 引向本地插值位置

快捷键：![](https://cascadeur.com/images/category/2019/06/0458c84ec753dc1612fe73e64452f2671d.png)

将选定的对象移近以本地坐标计算的最近帧中的平均位置。

### 角动量

快捷键：![](https://cascadeur.com/images/category/2019/06/04d216debf080acd3ff68147c2eec24215.png)

该滤镜会更改当前帧中角色的角动量，使其更接近平均动量。

## 使用过滤器

要显着改变对象的位置，您必须多次应用滤镜或放大其效果（请参见下文）。

|快捷键|将过滤器应用于当前帧|
-|-
快捷键+![](https://cascadeur.com/images/category/2019/06/0457a7f2bf991b968f92f90481bfaa8112.png)|将过滤器应用于时间轴上选择的每个帧
快捷键+![](https://cascadeur.com/images/category/2019/06/042c030b21f30a4257b6d3644a2278faf9.png)	|滤镜的效果被放大
快捷键+![](https://cascadeur.com/images/category/2019/06/0457a7f2bf991b968f92f90481bfaa8112.png)+![](https://cascadeur.com/images/category/2019/06/042c030b21f30a4257b6d3644a2278faf9.png)|将放大的效果应用于每个选定的帧
 
**注意：** 如果对区间应用过滤器，则该间隔上的插值类型将更改为[固定](../TimelineTools/interpolation.md/#固定插值)。

所有这些功能也可以作为菜单项使用。

在我们的教程中可以看到使用过滤器的示例：

[![](https://i2.hdslb.com/bfs/archive/854da7d8397f1f106b543a65060fdf69be95e622.jpg@640w_400h_100Q_1c.webp)](https://www.bilibili.com/video/BV11E41187c9/)
