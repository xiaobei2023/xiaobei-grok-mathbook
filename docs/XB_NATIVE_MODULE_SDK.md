# XB Native Module SDK v1

主程序只认目录和协议。

## 目录

modules/<id>/manifest.json + index.html

id：geometry | insert-graphic | cube-views | function-plot

## 消息

INIT ACK CLOSE / READY COMMIT CANCEL LIBRARY_READ LIBRARY_WRITE EXPORT ERROR INSERT_OPTIONS

protocol: xb-module, apiVersion: 1

COMMIT: moduleId, apiVersion, moduleVersion, document, svg, widthMm(10-500), heightMm(1-1000)

例子：modules/function-plot/index.html
