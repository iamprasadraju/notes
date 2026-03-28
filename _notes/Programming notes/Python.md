---
title: "Python"
date: 2026-03-28
tags: []
---

___
**Bolierplate**

```python
	print("Hello, World!")
```



Popular Machine Learning Libraries
	1.[[Numpy]]
	2. [[Pandas]]
	3. [[Pytorch]]
	4. [[Sckit-learn]]



PEP8: **PEP 8** stands for **Python Enhancement Proposal 8** and is a style guide for Python code. Its main goal is to improve the readability and consistency of Python code by providing conventions that developers can follow. [Style Guide](https://peps.python.org/pep-0008/)



#### Python Project Management

**Modern tools:**

- uv - A single tool to replace `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`, and more.

- poetry - Poetry is a tool for **dependency management** and **packaging** in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you. Poetry offers a lockfile to ensure repeatable installs, and can build your project for distribution.

- venv - The `venv` module in Python is a built-in tool used to create isolated virtual environments. These environments allow you to manage project-specific dependencies separately, preventing version conflicts between different projects and keeping your system-wide Python installation clean.

-  `pyproject.toml` - is a **standard configuration file for Python projects**. It defines **how your project is built**, **its dependencies**, and **which tools it uses**—all in **one place**. [Writing your `pyproject.toml`](https://packaging.python.org/en/latest/guides/writing-pyproject-toml/)

Overall - **uv** best for project management.

#### UV
 - [uv docs](https://docs.astral.sh/uv/)

**Project Structure**

 ```
.
├── .venv
│   ├── bin
│   ├── lib
│   └── pyvenv.cfg
├── .python-version
├── README.md
├── main.py
├── pyproject.toml
└── uv.lock

```





