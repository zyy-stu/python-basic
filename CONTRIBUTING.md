# 贡献指南

1. 先搜索现有 Issue，报告问题时附教程链接、Python 版本、复现命令和期望输出。
2. 从 `main` 建立分支。使用[教程模板](templates/tutorial-template.md)组织章节，同步更新示例、练习、答案与导航。
3. Python 文件按模块使用英文小写及下划线，编号示例延续所在目录原命名。注释与文档字符串使用中文。
4. 安装 `requirements-dev.txt`，运行 `python -m ruff check .`、`python -m ruff format --check .` 和 `python -m pytest`。另外核对实际示例输出。
5. 使用 `docs: ...`、`feat: ...`、`fix: ...`、`test: ...`、`refactor: ...` 或 `chore: ...` 提交。PR 说明背景、内容范围和验证结果。

外部资料优先引用对应版本的官方文档。只提交有权分发的内容。
