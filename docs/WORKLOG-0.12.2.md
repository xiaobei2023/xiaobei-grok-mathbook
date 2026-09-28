# 0.12.2 工作内容（截至 2026-09-28）

仓库：https://github.com/xiaobei2023/xiaobei-grok-mathbook

## 已完成

1. 几何模块 TypeScript + React 原生重写（1.0.34-native.9）
2. 插图、三视图按 XB Native Module SDK 接入
3. 界面 React，id 与成熟 HTML 对齐，不改按钮位置
4. 函数图像独立子程序
5. 插图数轴、不等式解集渲染迁入 TypeScript
6. 三视图领域：放置、表面积、三向投影
7. VERSION.json 与模块 manifest
8. 差异清单 DIFF_MATRIX.md

## 未完成

- 插图其余 13 类仍由 insert-engine.js 绘制（界面 1:1）
- 三视图斜二测/虚线网格仍由 engine.js 绘制
- 210MB 便携包无法经 GitHub 普通提交上传

## 验收

样式、字号、配色、按钮位置、操作步骤以成熟 HTML 为准。
