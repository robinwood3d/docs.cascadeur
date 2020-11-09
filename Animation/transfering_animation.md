# 转移动画

有时，您可能需要将动画从一个场景转移到另一个场景。此页面描述了可以完成此操作的几种方法。

## 单个角色

如果场景中只有一个绑定的角色，而带有动画的.fbx或.dae文件，则只需转到**File→Import Fbx/Dae→Animation**即可简单地导入动画。

![](https://cascadeur.com/images/category/2020/08/26/e0fbaef8a41c67d765ba4f08658d15a3.gif)

## 多个角色

如果场景中有多个角色，则只能为所选对象导入动画。步骤：

1. 切换到**关节模式**

2. 选择要对其应用动画的角色的**每个**关节

3. 从**File**菜单中选择**Import Fbx/Dae→Animation**到选定对象，然后打开包含动画的文件

之后，动画将应用于您选择的角色。

![](https://cascadeur.com/images/category/2020/08/26/f6b991fe7796e7f8b5aa65d0342ab022.gif)

## 复制动画

或者，您可以简单地将动画数据从一个场景复制并粘贴到另一个场景。去做这个： 

1. 在不同的选项卡中打开场景

2. 转到包含动画的选项卡

3. 选择角色的**所有**关节 

4. 选择要复制动画的时间轴区间

5. 复制选定的区间（按 **Ctrl + Shift + C** 或选择**Edit→Copy Interval**）。

6. 切换到要粘贴动画的选项卡

7. 选择所需的关节并粘贴动画（按 **Ctrl + Shift + V** 或选择**Edit→Paste Interval**）

![](https://cascadeur.com/images/category/2020/08/26/797433b914335cad9b87ea12d11b793c.gif)

请注意，如果您在具有多个角色的场景中尝试通过**File→Import Fbx/Dae→Animation**导入动画，则该动画将同时应用于场景中的每个角色。