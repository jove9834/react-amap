---
category: Article
title: react-amap 1.1.0 升级
order: 0
---

高德官方的地图 JSSDK 升级到了 [1.4.0](http://lbs.amap.com/api/javascript-api/changelog)，react-amap 接入最新的 SDK 升级到 1.1.0，同时修复了一些 Bug。

主要内容包括：

1. 大幅重构 Map 组件；支持 `animateEnable`、`doubleClickZoom` 等属性的动态配置。
2. 支持 3D 模式。
3. 新增控件 ControlBar。
4. 删除了地图内层一个多余的 div。（[#48](https://github.com/ElemeFE/react-amap/issues/48)）
3. 支持给 Map 提供 loading 组件以渲染加载效果。
2. 支持给 Marker 组件添加 `className`。（[#40](https://github.com/ElemeFE/react-amap/issues/40)）
3. 补充了 TypeScript 模块声明，可以在 TypeScript 项目中使用。（[#47](https://github.com/ElemeFE/react-amap/issues/47)）


升级说明

0. 本次升级的高德 JSSDK 版本完全向后兼容，可以直接升级使用。
1. v1.4.0 的高德官方 JSSDK，在开启 3D 模式后，有一些细微的 bug，比如设置地图语言时会抛错，无法渲染环形的多边形。

