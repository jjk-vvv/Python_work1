# Python_work1

Python 基础课程实验与作业。

- 姓名：欧阳洋
- 学号：20244080124
- 实验报告覆盖题目的 28 项任务，并保存全部 15 个代码单元格的实际运行结果。

## 项目文件

| 文件 | 说明 |
| --- | --- |
| `20244080124_欧阳洋_exp01.ipynb` | 实验报告：过程、代码、输出和结果分析 |
| `20244080124_欧阳洋_hw01.ipynb` | 作业 Notebook |
| `EXP01.pdf` / `HW01.pdf` | 原始实验及作业题目 |
| `student_utils.py` | 成绩记录解析模块 |
| `exp01_data/students.txt` | 题目给定的模拟记录 |
| `exp01_data/report.txt` | 成绩统计和无效记录明细 |
| `exp01_data/students.pkl` | 有效记录的序列化文件 |
| `environment.yml` | 独立 Conda 环境的依赖 |

## 运行方式

在项目目录中创建并激活环境，然后注册 Jupyter 内核：

```powershell
conda env create -f environment.yml
conda activate python_work1
python -m ipykernel install --user --name python_work1 --display-name "Python (python_work1)"
```

在已激活环境的终端启动支持 Jupyter Notebook 的编辑器，打开实验报告，选择
`Python (python_work1)` 内核，在 Notebook 所在目录重启内核并运行全部代码。
环境和机器指纹由首个代码单元格实际读取，不应手工改写运行输出。

实验报告已在独立 Conda 环境中使用 Python 3.12.15，从新内核顺序执行通过。
题目中的六条有效成绩记录得到平均分 `76.67`、及格率 `83.33%`；三条无效记录位于
原始文本的第 8、9、10 行。再次运行会重新写入实验数据和统计报告。

原始题目与项目来自 [课程仓库](https://gitee.com/little-rock-star/course_lr-code)，Git 历史保留原始提交记录。
