# 自动姿势

此功能可预测您要做出的姿势并自动为您摆放姿势。该预测是根据您操作角色控制器的方式进行的。

**目前，自动姿势仅适用于标准Cascadeur模型。尚不支持自定义模型。**

该功能可在工具栏中调用：

![](https://cascadeur.com/images/category/2019/11/21/9f4089a816a6b93d845222016a697ece.png)

### （1）启用自动姿势

选择整个角色（每个点控制器），然后按此按钮以生成自动姿势控制器。

对于一个角色，只应单击一次按钮。如果再次单击该按钮，将出现以下错误消息：

![](https://cascadeur.com/images/category/2019/11/28/a65a8267515442e145e2ee124ef6bee5.png)

自动姿势可以应用在多个角色上。如果场景只包含单个角色，则自动姿势会自动应用在该角色上。如果场景中有多个角色，则需要选择要应用自动姿势的角色的点控制器。

### （2）显示/隐藏自动姿势控制点

生成控制器后，您可以使用此按钮显示/隐藏它们。

![](https://cascadeur.com/images/category/2020/04/03/16a788c8d567820d20179b0d977e4601.gif)

***显示和隐藏自动姿势控制器的示例***

## 自动定位控制器

启用该工具后，多个控制器将出现在角色模型上。

<table border="1" cellpadding="1" cellspacing="1" style="width:800px">
	<tbody>
		<tr>
			<td style="height:55px; text-align:center; width:300px"><strong>主控制器</strong></td>
			<td colspan="2" rowspan="1" style="text-align:center"><strong>附加控制器</strong></td>
		</tr>
		<tr>
			<td style="height:55px">&nbsp;亮绿色</td>
			<td style="height:55px">&nbsp;暗绿色(未启用)</td>
			<td style="height:55px">&nbsp;蓝色(启用)</td>
		</tr>
		<tr>
			<td style="height:55px">&nbsp;用于生成姿势</td>
			<td style="height:55px">&nbsp;不用于生成姿势</td>
			<td style="height:55px">&nbsp;用于生成姿势</td>
		</tr>
	</tbody>
</table>
<br>
所有类型的控制器均可按以下方式使用：

<table border="1" cellpadding="1" cellspacing="1" style="width:800px">
	<tbody>
		<tr>
			<td style="height:55px; width:300px">&nbsp;&nbsp;<strong><img alt="" src="https://cascadeur.com/images/category/2019/06/04bba9a4c2865c96fa85a7af70a99a5aba.png" style="height:26px; width:18px"></strong></td>
			<td style="height:55px">&nbsp;选择控制器</td>
		</tr>
		<tr>
			<td style="height:55px">&nbsp;&nbsp;<strong><img alt="" src="https://cascadeur.com/images/category/2019/06/04bba9a4c2865c96fa85a7af70a99a5aba.png" style="height:26px; width:18px">&nbsp;x2</strong></td>
			<td style="height:55px">&nbsp;选择控制器及其附属控制器</td>
		</tr>
		<tr>
			<td style="height:55px"><strong>&nbsp; 按住</strong>&nbsp;<strong><img alt="" src="https://cascadeur.com/images/category/2019/06/04bba9a4c2865c96fa85a7af70a99a5aba.png" style="height:26px; width:18px">&nbsp;并拖拽</strong></td>
			<td style="height:55px">&nbsp;选择红框中所有启用的控制器</td>
		</tr>
		<tr>
			<td style="height:55px">&nbsp;&nbsp;<img alt="" src="https://cascadeur.com/images/category/2020/04/03/2ac1a88090501d467e79d000831787ed.png" style="height:20px; width:32px">&nbsp;<strong>+ R</strong></td>
			<td style="height:55px">&nbsp;固定/取消固定</td>
		</tr>
		<tr>
			<td style="height:55px">&nbsp;&nbsp;<img alt="" src="https://cascadeur.com/images/category/2020/04/03/0c0632779d2e511ab8c2184462aca0f9.png" style="height:37px; width:200px"></td>
			<td style="height:55px">&nbsp;编辑与调整</td>
		</tr>
	</tbody>
</table>
<br>

***注意1：*** 我们建议您在使用自动姿势之前切换到**查看模式**，以免[点控制器]()受到干扰。

***注意2：*** 在启用自动姿势的情况下调整姿势之前，需要先停用[肢体朝向控制器]()。

***注意3：*** 一旦取消固定，控制器将根据自动姿势模拟来预测新的位置。

![](https://cascadeur.com/images/category/2019/10/14/468a449b265a96eb579cad4f6a2c9bba.gif)

*自动姿势使用示例*

![](https://cascadeur.com/images/category/2019/10/25/55f2d61b622a880b6c43684127f52cae.gif)

*固定/取消固定一个控制器*

## 参阅

[角色](../../GettingStarted/scenes.md/#角色)

[绑定结构]()