# Floorplan Game Demo

基于 [wy51ai/floorplan-3d](https://github.com/wy51ai/floorplan-3d) 的 MIT 许可代码做的第一版“装修挑战”游戏化 Demo。

## 这一版增加

- ¥50,000 装修预算
- 家具价格
- 6 项客户任务
- 房间归属判定
- 提交验收
- 100 分评分 + 星级
- 家具重叠 / 挡门快速检查
- 3D 第一人称验收
- 第一人称家具碰撞
- 浏览器本地存档
- GitHub Pages 自动部署

## 操作

1. 从左侧家具库把家具拖入对应房间。
2. 完成右上角任务清单。
3. 点击「提交验收」查看评分。
4. 点击「进入 3D 验收」，可从入户门第一人称漫游。

> 这是 v0.1 游戏原型。评分中的空间检查目前使用简化 AABB 规则，后续可升级为真实可通行区域、门扇旋转包络、家具语义间距和关卡系统。

## Upstream

Original project: wy51ai/floorplan-3d  
License: MIT
