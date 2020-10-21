# 镜像工具

这套工具用于镜像角色绑定的部分位置以调整角色姿势。您可以镜像：

- [点控制器]()
- [盒体控制器]()

镜像操作是相对于**镜像平面**执行的：

![](https://cascadeur.com/images/category/2019/07/30/eb0022c6ec95229de22c44512761795d.jpg)

在不同的镜像平面上使用镜像工具的示例。从左到右：基本姿势（左）及其在**XY**，**XZ**和 **YZ**（右）平面上的镜像副本

## 镜像工具菜单

![](https://cascadeur.com/images/category/2020/08/06/daad1c223172b5c80fbed590b6f19bde.png)

### Mirror on current frame

在当前选中的**帧**上镜像所选控制器

### Mirror on interval

在当前选中的**区间**上镜像所选控制器。  
此区间上的插值类型更改为[固定插值](../TimelineTools/interpolation.md/#固定插值)。

下面四个选项用于设置**镜像平面**。

![](https://cascadeur.com/images/category/2020/03/10/36955c48edaf273fe13b2f7987ae0a53.png)

- **Plane XY** ***(默认)*** -使用X和Y坐标轴定义的平面作为镜像平面。
- **Plane XZ** -使用X和Z坐标轴定义的平面作为镜像平面。即放置在地面上的水平面。
- **Plane YZ** -使用由Y和Z坐标轴定义的平面作为镜像平面
- **Set by 3 objects** -使用三个选定对象的坐标来设置镜像平面。必须事先选择对象。

## 镜像问题

不正确的绑定可能会导致Mirror Tool无法正常工作。为防止问题，在**绑定**过程中：

- 在[**Rigging Tool**]()面板上 设置适当的角色镜像平面
- 确保角色模型处于T型姿势