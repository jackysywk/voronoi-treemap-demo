# Weighted Voronoi Diagram (Power Diagram) 可视化工具 🎯

## 项目简介

这是一个为**香港大学计算机科学硕士项目 (MSc Computer Science)** 的 **COMP7507 Visualization & Visual Analytics** 课程设计的 **Weighted Voronoi Diagram (Power Diagram)** 交互式可视化工具。

通过直观的图形界面，帮助同学们理解：
- 🎨 Weighted Voronoi Diagram 的几何特性
- ⚖️ 权重对区域划分的影响
- 🔄 Lloyd 算法和 Centroidal Voronoi Tessellation (CVT)
- 📐 Power Distance 的计算方式

## 核心概念

### Power Diagram 特性
- **距离公式**: `d² = (x-sx)² + (y-sy)² - weight`
- **边界形状**: 直线（不是曲线！）
- **权重效应**: 权重越大 → 区域越大
- **应用场景**: 加权空间划分丶影响力范围分析

### 与普通 Voronoi 的区别
| 特性 | 普通 Voronoi | Weighted Voronoi (Power) |
|------|-------------|--------------------------|
| 距离公式 | 欧氏距离 | Power Distance |
| 权重影响 | 无 | 有（影响区域大小）|
| 边界 | 垂直平分线 | 加权後的直线 |
| 应用 | 最近邻问题 | 加权影响力问题 |
