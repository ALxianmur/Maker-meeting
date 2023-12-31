# 建模那些事

建模通常需要专业的设计软件(CAD 软件)应用范围很广泛，建筑设计、土木工程、机械工程、电气工程等领域

## 常见的建模软件

常见的建模软件有这几种

- `AutoCAD`:

  _个人常将其用于平面建模_

  AutoCAD 是一种广泛使用的 CAD 软件，用于制作 2D 和 3D 建模、绘图和设计。它在建筑、土木工程、机械设计等领域被广泛采用。

- `SolidWorks`:

  _个人常将其用于 3d 建模_

  olidWorks 是一种专门用于机械设计和制造的 CAD 软件。它提供了强大的建模工具和功能，可以创建复杂的机械部件和装配体。

- `Autodesk Revit`:
  Revit 是一种专为建筑信息模型（BIM）设计而开发的软件。它可以创建建筑物的详细 3D 模型，并集成其他方面的设计和分析，如结构、机械、电气等。
- `SketchUp`:
  SketchUp 是一款直观易用的 3D 建模软件，适用于建筑设计、室内设计、景观设计等领域。它具有友好的用户界面和强大的建模工具。
- `Rhino`:
  Rhino 是一种专业的曲面建模软件，广泛应用于工业设计、船舶设计、珠宝设计等领域。它支持复杂的曲面建模和精确的几何操作。
- `3ds Max`:
  3ds Max 是一种功能强大的 3D 建模、动画和渲染软件，常用于电影、游戏和可视化效果的制作。它支持复杂的场景建模和动画制作。
- `Blender`:
  Blender 是一款免费的开源 3D 建模和动画软件，功能强大且灵活。它适用于各种领域，包括电影制作、游戏开发、建筑可视化等。

## 建模的基本流程

- 建模：使用 CAD 软件创建工程项目的三维模型。这可以包括建筑物、结构、管道、机械零件等。建模过程可以使用基本的几何体，如立方体、圆柱体，也可以使用更复杂的曲面和体积建模技术。

- 尺寸和标注：为了准确描述工程项目的尺寸和细节，需要在模型中添加尺寸和标注。这可以包括长度、角度、直径、孔距等参数的标注。

- 组装和连接：如果工程项目包含多个组件或部件，需要将它们组装和连接在一起。这可以通过 CAD 软件提供的组装功能来完成，确保各个组件符合设计要求。

- 材质和纹理：为工程项目的模型分配适当的材质和纹理属性。这可以使模型更加真实，并帮助可视化设计。

- 渲染和可视化：使用渲染技术将 3D 模型转换为逼真的图像或视频。这可以提供更好的视觉效果，帮助工程师和设计师展示他们的设计概念。

- 分析和仿真（可选）：在工程 3D 制图中，还可以使用特定的软件工具进行分析和仿真。例如，结构工程师可以使用有限元分析软件对建筑结构进行强度和稳定性分析。

## 建模的具体操作

> _以 Solidworks 为例 我常用,简单爱用_

- 规划和概念设计：在开始建模之前，你需要明确你要建模的物体或场景的概念和设计。这可以包括草图、参考图像或其他说明文档。
- 创建平面草图
- 使用拉伸,切除,放样等特征操作
- 重复上述操作完成基本的零件建模
- 将零件拼装形成组合体
- 保存文件

# 建模本身对于创客的用处

> 3d 打印
> 激光切割
> CNC

## 3d 打印

> 需要下好软件 _Bambu studio_

### 基本配置

![Alt text](annex/%E6%89%93%E5%8D%B0%E6%9C%BA%E9%85%8D%E7%BD%AE%E6%88%AA%E5%9B%BE.png)

### 基本操作

- 将 stl,step 等文件格式导入`Bambu studio` 切片
- 自动摆盘
- 调整大小
- 打开支撑(无论有没有都要打开)
- 改变填充强度,填充类型
- 切片
- 直接联网打印 or 以 G-code 文件形式导出到 TF 卡中进行冷数据传输打印

## 激光切割

> 需要下好软件 _LightBurn_(版本 1.4)

_激光切割机旁边的主机中装了此软件,可以直接用_

### 基本操作

- 将 dwg,png 文件导入

## CNC(数控铣)

> 需要下好软件 _Autodesk PowerMill_

### 基本操作

# 相关教程推荐

思维导图
![Alt text](annex/%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE.png)
[上海交通大学云汉交龙战队 第四届机甲大师校内赛第二次机械培训 ](https://www.bilibili.com/video/BV1Eh411n7WW/?share_source=copy_web&vd_source=528e49d949ae4899577360a618ad505)

[机械组竞培营 solidworks 建模基础](https://www.bilibili.com/video/BV1yF411N7ta/?share_source=copy_web&vd_source=528e49d949ae4899577360a618ad505b)

[【T-DT 机械组】SolidWorks 快速上手（2021.9.27）](https://www.bilibili.com/video/BV13f4y1A77m/?share_source=copy_web&vd_source=528e49d949ae4899577360a618ad505b)
