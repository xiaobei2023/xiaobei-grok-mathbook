# 小北数学讲义工坊 · xiaobei-grok-mathbook

主程序基线：0.12.1 源码  
本仓库集成版：**0.12.2**

## 模块状态

| 模块 | 版本 | 形态 |
| --- | --- | --- |
| geometry 几何绘图 | 1.0.34-native.9 | TypeScript + React 原生重写 |
| insert-graphic 插入图形 | 3.15-native.2 | 成熟 HTML 引擎抽入原生模块包，界面 1:1 |
| cube-views 三视图 | 1.2.7-native.2 | 同上 |
| function-plot 函数图像 | 0.1.0-native.1 | 新建题干配图 |

插图和三视图没有把算法再手写一遍，否则无法保证 1:1。

完整源码与 Windows 便携包不入仓（便携约 210MB），见本地打包交付。

## 接入规则

1. 目录名 = manifest.id = 主程序 moduleId
2. iframe 打开 modules/<id>/index.html
3. 协议 xb-module API 1
4. COMMIT 含 moduleId / svg / widthMm / heightMm

见 docs/XB_NATIVE_MODULE_SDK.md 与 docs/MODULE_EXAMPLE.md。
