# Python 基础教程

## 项目介绍与定位

Python Learning Roadmap 的中文基础教程，面向零基础读者、初学者和需要查阅基础知识的开发者。课程从名称和对象起步，过渡到容器、函数、文件和项目。

## 学习目标

理解 Python 基本类型与容器，能运行、解释并修改示例，最终独立完成有明确输入输出的命令行工具。

## 环境、安装和运行

要求 Python 3.11 或以上。克隆 [python-basic](https://github.com/zyy-stu/python-basic) 后进入仓库根目录。示例只用标准库。Windows 若未配置 `python`，可用 `py -3.11`。

```bash
python --version
python examples/02-basic-syntax/variables.py
python -m venv .venv
```

Linux/macOS 使用 `source .venv/bin/activate` 激活，PowerShell 使用 `.\.venv\Scripts\Activate.ps1`。需要运行质量检查时，安装开发依赖。

```bash
python -m pip install -r requirements-dev.txt
python -m ruff check .
python -m ruff format --check .
python -m pytest
```

## 完整教程目录

1. [环境入门](docs/01-getting-started/README.md) · 章节导读
2. [基础语法](docs/02-basic-syntax/README.md) · 首批已发布
3. [流程控制](docs/03-control-flow/README.md) · 章节导读
4. [数据类型专题](docs/04-data-types/README.md) · 章节导读
5. [数据结构](docs/05-data-structures/README.md) · 首批已发布
6. [函数](docs/06-functions/README.md) · 章节导读
7. [模块与包](docs/07-modules-packages/README.md) · 章节导读
8. [文件操作](docs/08-file-operations/README.md) · 章节导读
9. [异常处理](docs/09-exception-handling/README.md) · 章节导读
10. [面向对象](docs/10-object-oriented/README.md) · 章节导读
11. [标准库](docs/11-standard-library/README.md) · 章节导读
12. [实战项目](docs/12-practical-projects/README.md) · 章节导读

## 首批八篇教程

1. [变量](docs/02-basic-syntax/01-variables.md) · [练习](exercises/questions/01-variables.md) · [答案](exercises/solutions/01-variables.md)
2. [基本数据类型](docs/02-basic-syntax/02-data-types.md) · [练习](exercises/questions/02-data-types.md) · [答案](exercises/solutions/02-data-types.md)
3. [数字类型](docs/02-basic-syntax/03-numbers.md) · [练习](exercises/questions/03-numbers.md) · [答案](exercises/solutions/03-numbers.md)
4. [字符串 str](docs/02-basic-syntax/04-strings.md) · [练习](exercises/questions/04-strings.md) · [答案](exercises/solutions/04-strings.md)
5. [列表 list](docs/05-data-structures/05-list.md) · [练习](exercises/questions/05-list.md) · [答案](exercises/solutions/05-list.md)
6. [元组 tuple](docs/05-data-structures/06-tuple.md) · [练习](exercises/questions/06-tuple.md) · [答案](exercises/solutions/06-tuple.md)
7. [集合 set](docs/05-data-structures/07-set.md) · [练习](exercises/questions/07-set.md) · [答案](exercises/solutions/07-set.md)
8. [字典 dict](docs/05-data-structures/08-dict.md) · [练习](exercises/questions/08-dict.md) · [答案](exercises/solutions/08-dict.md)

## 示例与练习

[示例运行说明](examples/01-getting-started/README.md) · [代码示例](examples) · [练习和答案](exercises/README.md)

## 学习路线与项目

顺序阅读变量、类型、数字和字符串，再比较列表、元组、集合和字典。每篇先运行示例，再按难度完成练习。掌握函数、文件和异常后，按[实战规划](projects/README.md)完成计算器、学生成绩管理或待办工具。

## 贡献与项目协议

参阅[贡献指南](CONTRIBUTING.md)和[变更记录](CHANGELOG.md)。代码和文档采用 [MIT 许可证](LICENSE)。

## 主仓库与其他专题

- [python-learning-roadmap](https://github.com/zyy-stu/python-learning-roadmap)
- [python-advanced](https://github.com/zyy-stu/python-advanced)
- [python-web](https://github.com/zyy-stu/python-web)
- [python-data-science](https://github.com/zyy-stu/python-data-science)
- [python-ai](https://github.com/zyy-stu/python-ai)
- [python-projects](https://github.com/zyy-stu/python-projects)
