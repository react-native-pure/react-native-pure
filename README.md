# react-native-pure

react-native 纯js组件库。

## Guideline

- 所有的组件推荐使用hooks进行开发
- 所有组件的样式都需要创建对应的样式表，以独立文件的形式存在,样式文件命名格式：`xxx.style.js`，所有的样式文件都统一放在 `styles` 中。
- 共享数据，共享逻辑的使用使用hooks进行实现
- 尽量不要使用HOC
- 基于flow开发，类型文件命名格式：`xxx.flow.js`，文件存放在所在组件的文件夹下
- 尽量减少第三方组件的引用，工具库除外
- 每个组件一个文件夹
- 所有的组件都需要有单元测试，文档，截图（gif或者视频）

## Components

- [Toast]()
- [Gallery]()
- [Button]()
- [Skeleton]()
- [TreeView]()
- [Tag]()
