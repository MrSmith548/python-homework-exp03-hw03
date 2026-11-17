# Python 课程作业：EXP03 & HW03

**学号**：20244081132　　**姓名**：唐林

本仓库存放 Python 基础与数据处理课程的第 3 组作业，均在独立 conda 环境 `exp03`（Python 3.13）中完成，并已重启内核全量运行、输出嵌入、无报错。

## 作业清单

| 文件 | 说明 |
|---|---|
| `20244081132_唐林_exp03.ipynb` | 实验 03：正则表达式基础匹配、分组/回溯引用/替换、BeautifulSoup 解析 HTML |
| `20244081132_唐林_hw03.ipynb` | 作业 03：Wigner 矩阵与半圆定律、Conway 生命游戏、pandas DataFrame（iris 数据纠错与汇总） |
| `iris.csv` | 作业读取的原始 iris 数据（已按题目植入两处错误） |
| `iris_corrected.csv` | 修正并新增 `Petal.Ratio` / `Sepal.Ratio` 后的结果数据 |

## 运行环境

- conda 虚拟环境：`exp03`（非 base）
- Python 3.13.9 / NumPy / pandas / Matplotlib / SciPy / BeautifulSoup4 / Jupyter
- Matplotlib 已配置中文字体（Microsoft YaHei），图表中文正常显示

## 内容与提交对照

- EXP03：正则转义字符（`\d` `\s` `\b`）、择一与量词、捕获组与后向引用、日期/电话格式化、BeautifulSoup 的 `find_all()` 与 `get_text()`。
- HW03：`wigner_density` / `generate_wigner` / `get_spectrum` 及四子图半圆定律可视化；`is_valid_board` / `gol_step` / `draw_gol_board`；iris 数据读取、纠错、比例特征、保存与 `groupby` 汇总。
