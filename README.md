# python-coursework

Python 基础课程实验与作业。姓名：欧阳洋，学号：20244080124。

## 按次数查找文件

| 次数 | 实验报告 | 作业 | 题目与配套文件 |
| --- | --- | --- | --- |
| [第01次作业](./第01次作业/) | [exp01 实验报告](./第01次作业/20244080124_欧阳洋_exp01.ipynb) | [hw01 作业](./第01次作业/20244080124_欧阳洋_hw01.ipynb) | EXP01.pdf、HW01.pdf、student_utils.py、exp01_data/ |
| [第02次作业](./第02次作业/) | [exp02 实验报告](./第02次作业/20244080124_欧阳洋_exp02.ipynb) | [hw02 作业](./第02次作业/20244080124_欧阳洋_hw02.ipynb) | EXP02.pdf、HW02.pdf |

文件名中的 `exp` 表示实验报告，`hw` 表示作业，末尾 `01`、`02` 对应次数。查看题目时打开同文件夹中的 PDF；提交时选择该次对应的 Notebook。

```text
python-coursework/
├── 第01次作业/
│   ├── 20244080124_欧阳洋_exp01.ipynb
│   ├── 20244080124_欧阳洋_hw01.ipynb
│   ├── EXP01.pdf
│   ├── HW01.pdf
│   ├── student_utils.py
│   └── exp01_data/
│       ├── students.txt
│       ├── report.txt
│       └── students.pkl
├── 第02次作业/
│   ├── 20244080124_欧阳洋_exp02.ipynb
│   ├── 20244080124_欧阳洋_hw02.ipynb
│   ├── EXP02.pdf
│   └── HW02.pdf
├── environment.yml
└── README.md
```

第01次实验覆盖 28 项任务，第02次实验覆盖 22 项任务，第02次作业覆盖 14 项任务。
第二次实验的表格和 CSV 在内存中处理，图像已嵌入 Notebook，因此没有额外的数据文件夹。

## 运行方式

所有次数共用项目根目录中的 `environment.yml`。在根目录创建并激活环境，注册 Jupyter 内核：

```powershell
conda env create -f environment.yml
conda activate python_work1
python -m ipykernel install --user --name python_work1 --display-name "Python (python_work1)"
```

打开所需次数文件夹中的 Notebook，选择 `Python (python_work1)` 内核，重启并运行全部代码。
内核的工作目录应为该 Notebook 所在文件夹。第01次实验需要读取同文件夹的 `student_utils.py`，并在同文件夹的 `exp01_data/` 中读写数据。

身份、环境和机器指纹由代码实际读取，运行记录应通过执行刷新。原始题目来自 [课程仓库](https://gitee.com/little-rock-star/course_lr-code)。
