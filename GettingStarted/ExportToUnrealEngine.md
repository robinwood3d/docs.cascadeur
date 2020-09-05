# 导出到虚幻引擎

>**本页内容**
>- [UE4小白人动画](#UE4小白人动画)
>- [导入Cascadeur角色](#导入Cascadeur角色)
>   - [导入模型](#导入模型)
>   - [导入动画](#导入动画)
>- [修正旋转错误](#修正旋转错误)
>   - [在导入时调整旋转](#在导入时调整旋转)
>   - [重新导入动画前设置旋转](#重新导入动画前设置旋转)
 
## UE4小白人动画

可以将用Cascadeur创建的动画导入到虚幻4项目中，并附加到已有骨架上。

注意：如果您在项目中使用默认的小白人骨架，我们建议在Cascadeur中直接使用UE4_SK_Mannequin.casc文件创建动画。软件包中包含的其他模型具有明显不同的骨架，这可能会导致兼容性问题。

1. 右键单击**内容浏览器**窗口  
![](https://cascadeur.com/images/category/2020/03/24/2248c1f16c9b1d92ab0e12cb8f983d2b.png)

2. 从菜单中选择**导入到...**。  
![](https://cascadeur.com/images/category/2020/03/24/d6221cd90f549431f4d3566f226bcbae.png)

3. 选择包含模型的文件  
该文件应为二进制FBX格式。查阅[此处](Export.md)关于文件格式

4. 将会出现**FBX导入选项**窗口  
![](https://cascadeur.com/images/category/2020/03/24/ce84037d5493fb939b9d2c0c4c5cd764.jpg)

5. 将**骨架**选项设置为小白人骨架  
![](https://cascadeur.com/images/category/2020/03/24/28424c3a88677bfbd77d4aa24851ea57.png)

6. 取消勾选**导入网格体**  
![](https://cascadeur.com/images/category/2020/03/24/4eabbb6144b7be5056e2a4984d0e9a33.png)

7. 取消勾选**转换场景**  
![](https://cascadeur.com/images/category/2020/03/24/4f7d42e42d14b924d476b00fedc67309.png)

8. 单击**导入**按钮  
![](https://cascadeur.com/images/category/2020/03/24/4605313ecb1b3e6182e4cc6d33969820.png)

9. 将创建相应**动画**资产  
![](https://cascadeur.com/images/category/2020/03/24/416b582f116c7cad0e315c5b2b6e877c.png)

## 导入Cascadeur角色

要使用自定义角色，您需要首先导入角色模型，然后为其导入动画。

### 导入模型

1. 右键单击**内容浏览器**窗口  
![](https://cascadeur.com/images/category/2020/03/24/2248c1f16c9b1d92ab0e12cb8f983d2b.png)

2. 从菜单中选择**导入到...**。  
![](https://cascadeur.com/images/category/2020/03/24/d6221cd90f549431f4d3566f226bcbae.png)

3. 选择包含模型的文件  
该文件应为二进制FBX格式。查阅[此处](Export.md)关于文件格式

4. 将会出现**FBX导入选项**窗口  
![](https://cascadeur.com/images/category/2020/03/24/ce84037d5493fb939b9d2c0c4c5cd764.jpg)

5. 将**骨架**设置为**None**  
![](https://cascadeur.com/images/category/2020/03/24/8bd6e8ce938b9ce75659bf70ba063ba9.jpg)

6. 取消勾选**导入动画**  
![](https://cascadeur.com/images/category/2020/03/24/5de9d8b73bca59a4db6f7aefbec521c8.png)

7. 勾选**转换场景**  
![](https://cascadeur.com/images/category/2020/03/24/6c1b3e551fc2abf59e773682862147c8.png)

8. 取消勾选**Force Front XAxis**  
![](https://cascadeur.com/images/category/2020/03/24/fffb5bb9e782bb28c0b2bca2253b8176.png)

9. 将**Material Import Method**设置为**Do Not Create Material**（除非您希望将纹理与模型一起导入）  
![](https://cascadeur.com/images/category/2020/03/24/85241e27c8d4e035053cb2fa36143088.png)

10. 单击**导入**按钮  
![](https://cascadeur.com/images/category/2020/03/24/4605313ecb1b3e6182e4cc6d33969820.png)

11. 导入后会自动创建几个资产：
    - 一个骨架网格模型资产（包含导入的模型）
    - 一个物理资源
    - （可选）材质纹理资产（如果勾选导入）  
![](https://cascadeur.com/images/category/2020/03/24/1bb07d8881b312d964f52ae67879b8cd.png)

### 导入动画

1. 右键单击**内容浏览器**窗口  
![](https://cascadeur.com/images/category/2020/03/24/2248c1f16c9b1d92ab0e12cb8f983d2b.png)

2. 从菜单中选择**导入到...**。  
![](https://cascadeur.com/images/category/2020/03/24/d6221cd90f549431f4d3566f226bcbae.png)

3. 选择包含模型的文件  
该文件应为二进制FBX格式。查阅[此处](Export.md)关于文件格式

4. 将会出现**FBX导入选项**窗口  
![](https://cascadeur.com/images/category/2020/03/24/ce84037d5493fb939b9d2c0c4c5cd764.jpg)

5. 将**骨架**选项设置自定义的骨架  
![](https://cascadeur.com/images/category/2020/03/24/df39f3f51ea558d6db7164e9f2afaa71.png)

6. 取消勾选**导入网格体**  
![](https://cascadeur.com/images/category/2020/03/24/0a5f492170a310c34284b243a848a6aa.png) 

7. 取消勾选**转换场景**  
![](https://cascadeur.com/images/category/2020/03/24/4f7d42e42d14b924d476b00fedc67309.png)

8. 取消勾选**Force Front XAxis**  
![](https://cascadeur.com/images/category/2020/03/24/66046b777f97a3aaabbfa06121cdc2eb.png)

9. 单击**导入**按钮  
![](https://cascadeur.com/images/category/2020/03/24/4605313ecb1b3e6182e4cc6d33969820.png)

10. 将创建相应**动画**资产  
![](https://cascadeur.com/images/category/2020/03/24/416b582f116c7cad0e315c5b2b6e877c.png)

## 修正旋转错误

如果导入的模型和动画旋转不正确，有两种方法可以解决此问题：

### 在导入时调整旋转

1. 在**导入**窗口中，在**变换**面板下设置**Import Rotation**值。  
![](https://cascadeur.com/images/category/2020/03/24/e1c984bfd340212c8f76f120efccb0f8.png)

2. 按照**自定义骨架**部分中的说明继续导入模型

***注意***：无法预览导入期间设置的旋转。您可能需要尝试几次以找出所需的确切旋转角度。

### 重新导入动画前设置旋转

1. 在内容浏览器中，双击动画资产进入动画预览窗口

2. 调整导入旋转  
![](https://cascadeur.com/images/category/2020/03/24/1fd84e911b50f52d6c1da92b2a61dfd4.png)

3. 保存模型/动画  
![](https://cascadeur.com/images/category/2020/03/24/89cc8ba25bbdadc4db772755036d512e.png)

4. 关闭动画预览窗口。
5. 右键单击模型/动画资产，然后从菜单中选择**重新导入**  
![](https://cascadeur.com/images/category/2020/03/24/f2aa74fac93223b24b8d356987c58d91.jpg)

6. 之后资产将应用新的旋转

在不同情况下都应手动选择旋转轴  
![](https://cascadeur.com/images/category/2020/03/24/e047c4b5cd1c0641100adab9e69f49cb.png)

例如，此处的字符应沿X轴旋转90度：  
![](https://cascadeur.com/images/category/2020/03/24/34781d100083d6a8c6f2c7afd907cdfa.png)

## 参阅

[导出](Export.md)