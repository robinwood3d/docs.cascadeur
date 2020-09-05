# 文件结构

此页面描述了Cascadeur应用程序的文件结构

## 主程序文件夹

主程序文件夹名

- 在Windows系统上为**cascadeur-windows**

- 在Ubuntu系统上为**cascadeur-linux**

默认情况下，此文件夹包含两个子目录

- **cascadeur** - 包含所有的程序文件

- **scenes** - 预设示例场景

**注意**：在安装过程中，您可以为主文件夹指定另一个名称；在这种情况下，将使用该名称代替默认名称

## 应用数据

程序数据存储在以下位置的专用文件夹中：

- **Windows**: C:\Users\<user_name>\AppData\Local\Nekki Limited\Cascadeur\logs

- **Ubuntu**: /home/<user_name>/.local/share/Nekki Limited\Cascadeur

所有程序设置都存储在此路径根目录下的多个.ini文件中。它还包括一些文件夹：

- **autosave** 存储最近使用场景的备份保存文件。自动保存会被自动执行，其频率可以在Cascadeur的**设置**（**Settings**）窗口中进行调整。可以通过从**文件**（**File**）菜单中选择**打开自动保存文件**（**Open autosave file**）来访问此文件夹中的文件。

- **cache** 存储缓存文件

- **dumps** 包含Cascadeur崩溃记录

- **file_preview** 包含描述最近使用场景的.png图像（这些图像在**最近文件**（**Recent Files**）标签下的初始屏幕上可见）

- **logs** 包含文本文件形式的程序日志

**注意**：如果删除了这些文件，则所有用户设置将被重置（缺少文件将在启动程序时重新创建，但使用默认设置）

## 参阅

[安装Cascadeur](Installation.md)