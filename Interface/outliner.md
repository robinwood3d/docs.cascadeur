# 场景大纲

>**本页内容**
>- [场景大纲视图](#场景大纲视图)
>- [对象属性](#对象属性)
>   - [共同属性](#共同属性)

![](https://cascadeur.com/images/category/2019/08/13/5f7629826bcce7357471c55ee1d4e576.png)

## 场景大纲视图

该菜单列出了场景中所有对象，包括绑定元素。

![](https://cascadeur.com/images/category/2020/02/10/70b44f63b5ea36f13b05a8a84d588841.png)

- (1) 按字母顺序或层级顺序对列表进行排序
- (2) +和-展开和折叠分支
- (3) 将选定对象附加到父对象的父对象

***注意：*** 即使无法在视口窗口中​​选择对象（其[Selectable]()属性设置为 *False*），也仍然可以在大纲视图中选择对象。

## 对象属性

![](https://cascadeur.com/images/category/2019/07/24/cd3b2e210f4c3cc6625338bb23d4e967.png)

该面板包括与所选对象关联的属性的完整列表，并允许您对其进行编辑。根据对象的类型，将提供不同的选项。

面板标题右侧的四个按钮可用于切换不同类型的属性的可见性。

- (1) **Only coordinate button visible** 显示定义对象坐标，空间方向等属性
- (2) **Only boolean button visible** 显示具有布尔值的属性（可以启用或禁用的属性）
- (3) **Only variable button visible** 显示具有数值的属性
- (4) **All button visible** 显示每个可用属性。这是默认模式

### 共同属性

每种对象类型都有其自己的属性集。但是，某些属性对于每种类型的对象都是公用的，并且无论可见性模式如何，它们始终是可见的。

#### Name

对象的名称：大纲窗口中显示的层级结构中用于表示对象的标识文本。

#### Is Selectable

定义该对象是否可以在视口窗口中​​被选中。

***注意：*** 如果禁用此属性，则仍可以在大纲视图中选择该对象

#### Visible/Hidden/Invisible

定义该对象在视口窗口中​​是否可见。

- **Visible**选项表示该对象在视口窗口中会被​​渲染。
- **Hidden**选项意味着该对象不会在视口中渲染。按![](https://cascadeur.com/images/category/2019/11/06/76c6df871da2dba912c9816aaf31c517.png)下即可使隐藏的对象可见（请参阅[隐藏工具]()，以了解有关隐藏对象的更多信息） 
- 选择**Invisible**选项也会从视图中隐藏对象。勾选Invisible选项的对象只有在属性面板中取消勾选Invisible选项之后才可见

**注意：** 无论为属性编辑器设置为哪一种可见性模式，上述三个属性始终可见

**Additional Info**选项卡上还有三个属性。这些仅在**All button Visible**模式下可见

#### 轨道名称

此属性显示对象所属的[动画轨道]()的名称。

#### 控制器

定义对象的控制器。如果对象没有控制器，该属性值为“无控制器”。

#### 局唯一标识符

这是场景中对象的唯一标识符。

## 参阅

[场景结构](../GettingStarted/scenes.md)