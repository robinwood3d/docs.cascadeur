# 从虚幻引擎导入动画

![](https://cascadeur.com/images/category/2020/04/22/fad32fa508a39fbf2de3b41ad5c49e3e.jpg)

如果在尝试将动画从虚幻引擎导出到Cascadeur时出现上图所示错误，请按照以下步骤进行修复：

1. 在 **内容浏览器**（**Content Browser**）中，打开动画资产  
![](https://cascadeur.com/images/category/2020/04/22/371fc8ce75b954bcdc262f7292f840d0.jpg)

2. 将会出现动画编辑器窗口  
![](https://cascadeur.com/images/category/2020/04/22/189abc0b66c43368eecce1e7ad50456f.jpg)  
在其中，您需要录制动画：

3. 点击 **Pause** 按钮暂停播放动画  
![](https://cascadeur.com/images/category/2020/04/22/c4e3065e4b6ddaec3e0c8264ad6707b8.png)

4. 点击 **To Front** 跳转到第一帧  
![](https://cascadeur.com/images/category/2020/04/22/2c76052a8fbf03734828929ab1e8dbfc.png)

5. 单击 **Record** 按钮开始录制  
![](https://cascadeur.com/images/category/2020/04/22/236be829c9ec7639bbece36e4cafb942.png)

6. 单击 **Play** 播放动画  
![](https://cascadeur.com/images/category/2020/04/22/60d8c1b595b5dc8740834e5bbce093ee.png)

7. 等待动画至少完整播放一次

8. 点击 **Stop** 按钮  
![](https://cascadeur.com/images/category/2020/04/22/2752b1d07d515762212f51016a602a05.png)

9. 此操作将创建一个新的动画资产  
![](https://cascadeur.com/images/category/2020/04/22/4e37d20ae36cad538c76b26933488721.jpg)

10. 打开这个新资产，我们需要将动画剪切到原始长度。

11. 在时间轴上，选择动作开始的帧  
![](https://cascadeur.com/images/category/2020/04/22/85a38588a3ee37a76b76fa4589108949.jpg)  
***注意：*** 您可以使用 **To Previous** 和 **To Next** 按钮来移动帧标记  
![](https://cascadeur.com/images/category/2020/04/22/5e378dfc270cce3c17bae8e97c56bf2d.png)


12. 右键选择的帧，然后选择 **Remove frame 0 to**（**选择的帧**）  
![](https://cascadeur.com/images/category/2020/04/22/993205d6bf344ea43aa178a5f60b1ca5.png)  
这将删除动画的开始部分

13. 选择动作结束的帧  
例如，如果初始动画长30帧，则应选择第30帧。

14. 右键单击所选帧，这一次选择 **Remove from**（**选择的帧**）**to**（**最后一帧**）   
![](https://cascadeur.com/images/category/2020/04/22/3c53a880ca3de1c8860440c586535e92.png)  
这将删除动画的结束部分

15. 保存该动画  
![](https://cascadeur.com/images/category/2020/04/22/6190b09d25210c779362c07da2acfb13.png)

16. 导出动画  
![](https://cascadeur.com/images/category/2020/04/22/bca2a501f1e6b47fa71a72fa6acb5c08.jpg)

17. 现在动画应该准备好导入到Cascadeur中了  
![](https://cascadeur.com/images/category/2020/04/22/93c10cdd98f5844af2b36e2bd51bfde8.jpg)

 ## 如何修复错误旋转

有时导入到Cascadeur的动画整体会出现错误朝向。要解决此问题：

1. 选择角色骨架中的每个关节

2. 选择动画的每一帧

3. 启用 **间隔编辑模式**（**Interval edit mode**）  
![](https://cascadeur.com/images/category/2020/04/22/c779e53df907236e8d6773aa9cd801ae.png)

4. 在 **Settings** 面板中，启用 **Fix angle** 并将其设置为 **90**  
![](https://cascadeur.com/images/category/2020/04/22/927a3484b96bd69af5b359aba1b132a5.png)

5. 旋转角色  
![](https://cascadeur.com/images/category/2020/04/22/6b02908bae84bdd884a0b0f2f6a48de7.gif)  
之后不要忘记禁用 **Fix angle** 和 **间隔编辑模式**（**Interval edit mode**） 

## 参阅

[导入](Import.md)

[导出到虚幻引擎](ExportToUnrealEngine.md)
