# 骨骼动画资源（DragonBones）

DragonBones 骨骼动画资源是由 [DragonBones](http://dragonbones.com/) 编辑导出的数据格式。

## 导入 DragonBones 骨骼动画资源

DragonBones 骨骼动画资源有：

- .json 骨骼数据
- .json 图集数据
- .png 图集纹理

![DragonBones](dragonbones/import.png)

## 创建骨骼动画资源

在场景中使用 DragonBones 骨骼动画资源需要两个步骤：

**1. 创建节点并添加 DragonBones 组件，可以通过三种方式实现：**

   第一种方式：从 **资源管理器** 里将骨骼动画资源拖动到 **层级管理器** 中:

![DragonBones](dragonbones/create_1.png) 

   第二种方式：从 **资源管理器** 里将骨骼动画资源拖动到 **场景** 中:

![DragonBones](dragonbones/create_2.png)

   第三种方式：从 **资源管理器** 里将骨骼动画资源拖动到已创建 DragonBones 组件的 Dragon Asset 属性中：

![DragonBones](dragonbones/create_3.png)

**2. 为 DragonBones 组件设置图集数据**

从 **资源管理器** 里将图集数据拖动到 DragonBones 组件的 Dragon Atlas Asset 属性中：

![DragonBones](dragonbones/set_atlas.png)

## 在项目中的存放

为了提高资源管理效率，建议将导入的资源文件存放在单独的目录下，不要和其他资源混在一起。