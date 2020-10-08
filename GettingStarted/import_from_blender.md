# 从Blender导入动画

有时，从Blender导出的模型（以FBX或Collada格式）最终出现如下问题：  
![](https://cascadeur.com/images/category/2020/05/28/e0f06f4483d5c23b292250a80a2d099b.jpg)

此问题将在将来的版本中修复。目前可以通过执行以下步骤来规避它：

1. 在Blender中，打开**场景属性**（**Scene Properties**）面板：  
![](https://cascadeur.com/images/category/2020/05/28/08d9e36f4cfa80d3e79e152a1484c6f7.png)

2. 在 **单位** 选项卡上：
    * 将 **单位比例** 设置为0.01
    * 将 **长度单位** 设置为 **厘米**
    
    ![](https://cascadeur.com/images/category/2020/05/28/9abd350b58033e15658990f2ccdad490.png)

3. 将骨架缩放至0.01倍

4. 对骨架和网格模型都使用 **Apply Object Transform** 命令  
![](https://cascadeur.com/images/category/2020/05/28/1f7b8b077e8582e5b6cd05b6e117ab03.png)

5. 使用默认设置导出

6. 修改后的模型应该可以正常使用  
![](https://cascadeur.com/images/category/2020/05/28/2f250f9f9c874a2e492767c6de8c300c.jpg)

## 已知问题

- 导入的模型在Cascadeur中显得太大

在上述步骤3中，可尝试将模型改为缩放10倍而不是100倍。

## 参阅

[导入](import_fbxdae.md)