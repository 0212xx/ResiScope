# ResiScope

https://0212xx.github.io/ResiScope/ResiScope.html
电阻曲线预览、编辑与导出工具。
在原项目[chengzhiyaoguoli/self-developed-tools — ResiScope](https://github.com/chengzhiyaoguoli/self-developed-tools/tree/main/research-lab/ResiScope)基础上增加了坐标轴拉伸压缩与csv文件导出功能。

## 使用方法

1. 下载本仓库的 `ResiScope.html`。
2. 使用现代桌面浏览器打开文件，无需部署服务器。
3. 导入 `.xlsx`、`.csv` 或 `.tsv` 数据，选择工作表和通道开始处理。
4. 使用右上角导出按钮保存处理结果。请保留原始实验数据。

## 功能

- 多通道电阻曲线、基线响应值和响应百分比显示。
- 框选区间、公式处理、时间伸缩与滤波；工具位于通道显示下方，点击展开。
- 画布拖动调节坐标范围；滚轮放大/缩小，底部时间滑块平移视图。
- Excel 和 CSV 导出，以及 TXT 与 Excel 数据转换。
- 数据操作撤销与重做。

CSV 使用 UTF-8 BOM 编码，便于在 Excel 中打开中文内容。

## 来源与说明

原项目：[chengzhiyaoguoli/self-developed-tools — ResiScope](https://github.com/chengzhiyaoguoli/self-developed-tools/tree/main/research-lab/ResiScope)。

此版本包含界面、CSV 导出及图表交互调整。
