# 编辑模式

>**本页内容**
>- [可用的编辑模式](#可用的编辑模式)
>- [自定义编辑模式](#自定义编辑模式)
>- [可见菜单](#可见菜单)
>- [可选菜单](#可选菜单)

由于使用一整个绑定控制器会非常麻烦且不方便，Cascadeur包含了几种**编辑模式**。每种编辑模式仅可用于编辑其中几种控制器，且每个编辑模式都有适用的特定情况。为了快速高效地处理角色姿势，需要针对不同情形选择使用合适的编辑模式。

通过单击**工具栏**（**Toolbar**）下方专用面板上的按钮来选择编辑模式 ：
![](https://cascadeur.com/images/category/2020/08/04/3a84bc4f493986795a7a65ef9bdae366.png)  
*用于在工具栏上选择**编辑模式**的面板*

## 可用的编辑模式

共有六种编辑模式：  

<table border="0" cellpadding="1" cellspacing="1" style="width:816px">
	<tbody>
		<tr>
			<td style="height:272px; width:272px"><img alt="" src="https://cascadeur.com/images/category/2019/08/14/cfea76d0cb7f8176898cb2ba5e0dd698.png" style="height:272px; width:272px"></td>
			<td style="height:272px; width:272px"><a href="https://cascadeur.com/help/category/18"><img alt="" src="https://cascadeur.com/images/category/2019/08/14/0712d55fa27db44c895b3e9f2eea3498.png" style="height:272px; width:272px"></a></td>
			<td style="height:272px; width:272px"><a href="https://cascadeur.com/help/category/19"><img alt="" src="https://cascadeur.com/images/category/2019/08/14/c728f0df4fcc06bdee90c0271750517e.png" style="height:272px; width:272px"></a></td>
		</tr>
		<tr>
			<td><strong>查看模式</strong>&nbsp;仅显示模型本身，隐藏控制器。</td>
			<td><a href="https://cascadeur.com/help/category/18"><strong>点控制器</strong></a>&nbsp;模式是编辑姿势的主要模式</td>
			<td><a href="https://cascadeur.com/help/category/19"><strong>盒体控制器</strong></a>&nbsp;模式用于调整精细的细节，例如手指或布料部分</td>
		</tr>
	</tbody>
</table>
<table border="0" cellpadding="1" cellspacing="1" style="width:816px">
	<tbody>
		<tr>
			<td style="height:272px; width:272px"><a href="https://cascadeur.com/help/category/20"><img alt="" src="https://cascadeur.com/images/category/2019/08/14/a36751aa3d034829f9a54c20f5c37304.png" style="height:272px; width:272px"></a></td>
			<td style="height:272px; width:272px"><a href="https://cascadeur.com/help/category/26"><img alt="" src="https://cascadeur.com/images/category/2019/08/14/20310288651f9a91f1cfbd6a7335a88c.png" style="height:272px; width:272px"></a></td>
			<td style="height:272px; width:272px"><a href="https://cascadeur.com/help/category/45"><img alt="" src="https://cascadeur.com/images/category/2020/08/04/f931b0bb713687dfa15fc905b6403f1c.png" style="height:272px; width:272px"></a></td>
		</tr>
		<tr>
			<td><a href="https://cascadeur.com/help/category/20"><strong>关节模式</strong></a>&nbsp;显示角色的骨架<br>
			&nbsp;</td>
			<td><strong>网格模式</strong>&nbsp;用于处理&nbsp;<a href="http://cascadeur.com/help/category/26">网格模型</a></td>
			<td><strong>绑定模式</strong>&nbsp;用于为角色创建&nbsp;<a href="https://cascadeur.com/help/category/45"><strong>绑定控制器</strong></a></td>
		</tr>
	</tbody>
</table>

## 自定义编辑模式

默认情况下，每种编辑模式都有预设好的可用于编辑的元素类型。但可以使用**Visible**（定义可见的对象类型）和**Selectable**（定义可编辑的对象类型）菜单自定义这些预设。

要访问这些菜单，请**右击**工具栏下方的编辑模式按钮：  
![](https://cascadeur.com/images/category/2020/08/04/79691213ab79630856a0715c98ebf20b.png)

### 可见类型菜单（Visible Menu）

此菜单列出了场景中可能存在的每种对象类型：

这些元素包括：

<table border="0" cellpadding="1" cellspacing="1" style="width:810px">
	<tbody>
		<tr>
			<td>
			<p><a href="https://cascadeur.com/help/category/19">盒体控制器</a></p>
			<p><a href="https://cascadeur.com/help/category/18">点控制器</a></p>
			<p><a href="https://cascadeur.com/help/category/50">点控制器连接线</a></p>
			<p><a href="https://cascadeur.com/help/category/49">方向控制器</a></p>
			<p>&nbsp;</p>
			<p>&nbsp;</p>
			</td>
			<td>
			<p><a href="https://cascadeur.com/help/category/39">质心</a></p>
			<p><a href="https://cascadeur.com/help/category/42">弹射轨迹</a></p>
			<p><a href="https://cascadeur.com/help/category/44">支点</a></p>
			<p><a href="https://cascadeur.com/help/category/40">角动量可视器</a></p>
			<p><a href="https://cascadeur.com/help/category/40#angmom_ghosts">角动量幽灵视图</a></p>
			<p><a href="https://cascadeur.com/help/category/41">支点作用力</a></p>
			</td>
			<td>
			<p>物理点</p>
			<p>物理点连接线</p>
			<p><a href="https://cascadeur.com/help/category/25">刚体</a></p>
			<p>&nbsp;</p>
			<p>&nbsp;</p>
			<p>&nbsp;</p>
			</td>
			<td>
			<p><a href="https://cascadeur.com/help/category/20">关节</a></p>
			<p><a href="https://cascadeur.com/help/category/26">模型着色</a></p>
			<p><a href="https://cascadeur.com/help/category/26#meshes_wireframe">模型线框</a></p>
			<p><a href="https://cascadeur.com/help/category/26#mesh_mode_textures">纹理</a></p>
			<p><a href="https://cascadeur.com/help/category/29#camera_objects">相机</a></p>
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>


### 可选类型菜单（Selectable Menu）

此菜单允许您定义可在视口中选中的对象类型。

它包含与**可见类型菜单**相同的对象类型列表。勾选此列表上的项目会将对应的对象类型标记为可选择的，即可以在视口中选中的对象类型。

***注意：*** *即使未将对象标记为可选对象，您仍可以在[大纲视图]()窗口中选中它。*

使用这两个菜单，您可以完全更改视口窗口的外观以及要使用的对象集。

所有可见类型和可选类型列表的更改可以通过在**设置**（**Settings**）菜单中选择**还原默认设置**（**Set default all settings**）进行还原

## 参阅

[绑定结构]()

[场景](Scenes.md)

[操纵工具]()