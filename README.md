<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Python Developer Tools
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome python developer tools and libraries. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-250-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-python-dev/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-python-dev?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 250 awesome open-source projects with a total of 650K stars grouped into 15 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-python-dev/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-python-dev/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-python-dev/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Linters & Style Checkers](#linters--style-checkers) _42 projects_
- [Code Formatters](#code-formatters) _6 projects_
- [Code Refactoring](#code-refactoring) _18 projects_
- [Code Security](#code-security) _8 projects_
- [Virtual Environments](#virtual-environments) _8 projects_
- [Dependency & Package Mangers](#dependency--package-mangers) _10 projects_
- [Code Metrics & Complexity](#code-metrics--complexity) _6 projects_
- [Logging](#logging) _21 projects_
- [Documentation](#documentation) _26 projects_
- [Debugging Tools](#debugging-tools) _13 projects_
- [Testing Tools](#testing-tools) _43 projects_
- [Code Packaging](#code-packaging) _16 projects_
- [Build Tools](#build-tools) _14 projects_
- [System Monitoring & Profiling](#system-monitoring--profiling) _17 projects_
- [AST Tools](#ast-tools) _5 projects_
- [Others](#others) _1 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13">&nbsp; Flake8 related project
- <img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13">&nbsp; Pytest related project
- <img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Pylint related project
- <img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13">&nbsp; Sphinx related project
- <img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13">&nbsp; MkDocs related project

<br>

## Linters & Style Checkers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python/mypy">mypy</a></b> (🥇43 ·  ⭐ 12K) - Optional static typing for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python/mypy) (👨‍💻 530 · 🔀 2K · 📦 56K · 📋 7.2K - 28% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/python/mypy
	```
- [PyPi](https://pypi.org/project/mypy) (📥 6.9M / month · 📦 5.4K · ⏱️ 07.01.2022):
	```
	pip install mypy
	```
- [Conda](https://anaconda.org/conda-forge/mypy) (📥 1.5M · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge mypy
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8">flake8</a></b> (🥇41 ·  ⭐ 1.7K) - Flake8 is a wrapper around these tools: PyFlakes; pycodestyle; Ned.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/flake8) (👨‍💻 160 · 🔀 180 · 📦 220K · 📋 1.4K - 2% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/PyCQA/flake8
	```
- [PyPi](https://pypi.org/project/flake8) (📥 11M / month · 📦 41K · ⏱️ 11.10.2021):
	```
	pip install flake8
	```
- [Conda](https://anaconda.org/conda-forge/flake8) (📥 3.5M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge flake8
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint">pylint</a></b> (🥇40 ·  ⭐ 3.8K) - Its not just a linter that annoys you!. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/pylint) (👨‍💻 440 · 🔀 800 · 📋 3.9K - 19% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/PyCQA/pylint
	```
- [PyPi](https://pypi.org/project/pylint) (📥 7.8M / month · 📦 21K · ⏱️ 03.12.2021):
	```
	pip install pylint
	```
- [Conda](https://anaconda.org/conda-forge/pylint) (📥 2.5M · ⏱️ 03.12.2021):
	```
	conda install -c conda-forge pylint
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pycodestyle">pycodestyle</a></b> (🥇37 ·  ⭐ 4.5K) - Simple Python style checker in one Python file. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/pycodestyle) (👨‍💻 130 · 🔀 610 · 📦 180K · 📋 670 - 16% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/PyCQA/pycodestyle
	```
- [PyPi](https://pypi.org/project/pycodestyle) (📥 16M / month · 📦 11K · ⏱️ 11.10.2021):
	```
	pip install pycodestyle
	```
- [Conda](https://anaconda.org/conda-forge/pycodestyle) (📥 3.7M · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge pycodestyle
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/wemake-python-styleguide">wemake-python-styleguide</a></b> (🥇35 ·  ⭐ 1.7K) - The strictest and most opinionated python linter ever!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-python-styleguide) (👨‍💻 160 · 🔀 310 · 📦 920 · 📋 990 - 8% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/wemake-services/wemake-python-styleguide
	```
- [PyPi](https://pypi.org/project/wemake-python-styleguide) (📥 70K / month · 📦 24 · ⏱️ 13.12.2021):
	```
	pip install wemake-python-styleguide
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pyflakes">pyflakes</a></b> (🥇35 ·  ⭐ 1.1K) - A simple program which checks Python source files for errors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pyflakes) (👨‍💻 79 · 🔀 160 · 📦 110K · 📋 450 - 18% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/PyCQA/pyflakes
	```
- [PyPi](https://pypi.org/project/pyflakes) (📥 12M / month · 📦 14K · ⏱️ 06.10.2021):
	```
	pip install pyflakes
	```
- [Conda](https://anaconda.org/conda-forge/pyflakes) (📥 3.5M · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge pyflakes
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/pyright">pyright</a></b> (🥈34 ·  ⭐ 7.5K) - Static type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/pyright) (👨‍💻 69 · 🔀 410 · 📦 180 · 📋 2.3K - 0% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/Microsoft/pyright
	```
- [npm](https://www.npmjs.com/package/pyright) (📥 210K / month · 📦 3 · ⏱️ 12.01.2022):
	```
	npm install pyright
	```
</details>
<details><summary><b><a href="https://github.com/facebook/pyre-check">pyre-check</a></b> (🥈33 ·  ⭐ 5.7K) - Performant type-checking for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/pyre-check) (👨‍💻 190 · 🔀 380 · 📋 300 - 31% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/facebook/pyre-check
	```
- [PyPi](https://pypi.org/project/pyre-check) (📥 23K / month · 📦 32 · ⏱️ 11.01.2022):
	```
	pip install pyre-check
	```
</details>
<details><summary><b><a href="https://github.com/google/pytype">pytype</a></b> (🥈33 ·  ⭐ 3.6K) - A static type analyzer for Python code. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/pytype) (👨‍💻 71 · 🔀 230 · 📋 470 - 20% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/google/pytype
	```
- [PyPi](https://pypi.org/project/pytype) (📥 130K / month · 📦 87 · ⏱️ 07.01.2022):
	```
	pip install pytype
	```
- [Conda](https://anaconda.org/conda-forge/pytype) (📥 66K · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge pytype
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint-django">pylint-django</a></b> (🥈32 ·  ⭐ 490) - Pylint plugin for improving code analysis for when.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/pylint-django) (👨‍💻 62 · 🔀 100 · 📥 200 · 📦 16K · 📋 190 - 16% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/PyCQA/pylint-django
	```
- [PyPi](https://pypi.org/project/pylint-django) (📥 540K / month · 📦 1.2K · ⏱️ 02.01.2022):
	```
	pip install pylint-django
	```
- [Conda](https://anaconda.org/conda-forge/pylint-django) (📥 89K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge pylint-django
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pydocstyle">pydocstyle</a></b> (🥈31 ·  ⭐ 840) - docstring style checker. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pydocstyle) (👨‍💻 77 · 🔀 150 · 📥 56 · 📦 22K · 📋 280 - 28% open · ⏱️ 30.12.2021):

	```
	git clone https://github.com/PyCQA/pydocstyle
	```
- [PyPi](https://pypi.org/project/pydocstyle) (📥 1.6M / month · 📦 2.4K · ⏱️ 17.05.2021):
	```
	pip install pydocstyle
	```
- [Conda](https://anaconda.org/conda-forge/pydocstyle) (📥 500K · ⏱️ 18.05.2021):
	```
	conda install -c conda-forge pydocstyle
	```
</details>
<details><summary><b><a href="https://github.com/davidhalter/parso">parso</a></b> (🥈31 ·  ⭐ 470) - A Python Parser. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/parso) (👨‍💻 43 · 🔀 79 · 📦 170K · 📋 100 - 6% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/davidhalter/parso
	```
- [PyPi](https://pypi.org/project/parso) (📥 16M / month · 📦 5.9K · ⏱️ 30.11.2021):
	```
	pip install parso
	```
- [Conda](https://anaconda.org/conda-forge/parso) (📥 6M · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge parso
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-bugbear">flake8-bugbear</a></b> (🥈30 ·  ⭐ 660) - A plugin for Flake8 finding likely bugs and design problems.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-bugbear) (👨‍💻 47 · 🔀 55 · 📦 6.3K · 📋 110 - 37% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/PyCQA/flake8-bugbear
	```
- [PyPi](https://pypi.org/project/flake8-bugbear) (📥 920K / month · 📦 880 · ⏱️ 12.01.2022):
	```
	pip install flake8-bugbear
	```
- [Conda](https://anaconda.org/conda-forge/flake8-bugbear) (📥 540K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge flake8-bugbear
	```
</details>
<details><summary><b><a href="https://github.com/coala/coala">coala</a></b> (🥈29 ·  ⭐ 3.3K · 💤) - coala provides a unified command-line interface for linting and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/coala/coala) (👨‍💻 480 · 🔀 1.4K · 📥 150 · 📦 10 · 📋 3.2K - 26% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/coala/coala
	```
- [PyPi](https://pypi.org/project/coala-bears) (📥 3.7K / month · 📦 100 · ⏱️ 10.11.2017):
	```
	pip install coala-bears
	```
</details>
<details><summary><b><a href="https://github.com/klen/pylama">pylama</a></b> (🥈29 ·  ⭐ 850) - Code audit tool for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/klen/pylama) (👨‍💻 46 · 🔀 88 · 📦 3.2K · 📋 120 - 28% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/klen/pylama
	```
- [PyPi](https://pypi.org/project/pylama) (📥 88K / month · 📦 590 · ⏱️ 10.01.2022):
	```
	pip install pylama
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/mypy-protobuf">mypy-protobuf</a></b> (🥈28 ·  ⭐ 420) - open source tools to generate mypy stubs from protobufs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/mypy-protobuf) (👨‍💻 31 · 🔀 64 · 📋 97 - 4% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/dropbox/mypy-protobuf
	```
- [PyPi](https://pypi.org/project/mypy-protobuf) (📥 940K / month · 📦 49 · ⏱️ 24.12.2021):
	```
	pip install mypy-protobuf
	```
</details>
<details><summary><b><a href="https://github.com/openstack/hacking">hacking</a></b> (🥈28 ·  ⭐ 220) - OpenStack Hacking Style Checks. Mirror of code maintained at.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/openstack/hacking) (👨‍💻 180 · 🔀 66 · ⏱️ 10.01.2022):

	```
	git clone https://github.com/openstack/hacking
	```
- [PyPi](https://pypi.org/project/hacking) (📥 490K / month · 📦 4.4K · ⏱️ 21.04.2021):
	```
	pip install hacking
	```
</details>
<details><summary><b><a href="https://github.com/terrencepreilly/darglint">darglint</a></b> (🥉27 ·  ⭐ 380) - A python documentation linter which checks that the docstring description.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/terrencepreilly/darglint) (👨‍💻 22 · 🔀 34 · 📦 1.5K · 📋 140 - 34% open · ⏱️ 18.10.2021):

	```
	git clone https://github.com/terrencepreilly/darglint
	```
- [PyPi](https://pypi.org/project/darglint) (📥 200K / month · 📦 53 · ⏱️ 18.10.2021):
	```
	pip install darglint
	```
- [Conda](https://anaconda.org/conda-forge/darglint) (📥 28K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge darglint
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/flake8-comprehensions">flake8-comprehensions</a></b> (🥉26 ·  ⭐ 320) - A flake8 plugin to help you write better.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adamchainz/flake8-comprehensions) (👨‍💻 12 · 🔀 16 · 📋 42 - 19% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/adamchainz/flake8-comprehensions
	```
- [PyPi](https://pypi.org/project/flake8-comprehensions) (📥 470K / month · 📦 530 · ⏱️ 10.01.2022):
	```
	pip install flake8-comprehensions
	```
- [Conda](https://anaconda.org/conda-forge/flake8-comprehensions) (📥 480K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge flake8-comprehensions
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-isort">flake8-isort</a></b> (🥉26 ·  ⭐ 110) - flake8 plugin that integrates isort. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-isort) (👨‍💻 30 · 🔀 40 · 📦 4.4K · 📋 53 - 24% open · ⏱️ 03.12.2021):

	```
	git clone https://github.com/gforcada/flake8-isort
	```
- [PyPi](https://pypi.org/project/flake8-isort) (📥 460K / month · 📦 590 · ⏱️ 14.10.2021):
	```
	pip install flake8-isort
	```
- [Conda](https://anaconda.org/conda-forge/flake8-isort) (📥 15K · ⏱️ 14.10.2021):
	```
	conda install -c conda-forge flake8-isort
	```
</details>
<details><summary><b><a href="https://github.com/zheller/flake8-quotes">flake8-quotes</a></b> (🥉25 ·  ⭐ 140) - Flake8 extension for checking quotes in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zheller/flake8-quotes) (👨‍💻 30 · 🔀 33 · 📦 4.1K · 📋 43 - 6% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/zheller/flake8-quotes
	```
- [PyPi](https://pypi.org/project/flake8-quotes) (📥 410K / month · 📦 820 · ⏱️ 15.12.2021):
	```
	pip install flake8-quotes
	```
- [Conda](https://anaconda.org/conda-forge/flake8-quotes) (📥 590K · ⏱️ 19.10.2021):
	```
	conda install -c conda-forge flake8-quotes
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/flake8-eradicate">flake8-eradicate</a></b> (🥉24 ·  ⭐ 220) - Flake8 plugin to find commented out or dead code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/wemake-services/flake8-eradicate) (👨‍💻 13 · 🔀 7 · 📋 28 - 3% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/wemake-services/flake8-eradicate
	```
- [PyPi](https://pypi.org/project/flake8-eradicate) (📥 210K / month · 📦 65 · ⏱️ 19.10.2021):
	```
	pip install flake8-eradicate
	```
</details>
<details><summary><b><a href="https://github.com/beartype/beartype">beartype</a></b> (🥉23 ·  ⭐ 1K) - Unbearably fast O(1) runtime type-checking in pure Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beartype/beartype) (👨‍💻 9 · 🔀 18 · 📋 64 - 15% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/beartype/beartype
	```
- [PyPi](https://pypi.org/project/beartype) (📥 40K / month · 📦 23 · ⏱️ 06.11.2021):
	```
	pip install beartype
	```
- [Conda](https://anaconda.org/conda-forge/beartype) (📥 9.6K · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge beartype
	```
</details>
<details><summary><b><a href="https://github.com/mgedmin/check-manifest">check-manifest</a></b> (🥉23 ·  ⭐ 250) - Tool to check the completeness of MANIFEST.in for Python packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mgedmin/check-manifest) (👨‍💻 20 · 🔀 31 · 📦 7K · 📋 88 - 18% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/mgedmin/check-manifest
	```
- [PyPi](https://pypi.org/project/check-manifest) (📥 130K / month · 📦 2.5K · ⏱️ 22.09.2021):
	```
	pip install check-manifest
	```
- [Conda](https://anaconda.org/conda-forge/check-manifest) (📥 37K · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge check-manifest
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-commas">flake8-commas</a></b> (🥉23 ·  ⭐ 130) - Flake8 extension for enforcing trailing commas in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-commas) (👨‍💻 12 · 🔀 23 · 📋 31 - 16% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/PyCQA/flake8-commas
	```
- [PyPi](https://pypi.org/project/flake8-commas) (📥 220K / month · 📦 330 · ⏱️ 13.10.2021):
	```
	pip install flake8-commas
	```
</details>
<details><summary><b><a href="https://github.com/andreoliwa/nitpick">nitpick</a></b> (🥉22 ·  ⭐ 210) - Enforce the same settings on multiple projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andreoliwa/nitpick) (👨‍💻 13 · 🔀 13 · 📥 4 · 📋 96 - 33% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/andreoliwa/nitpick
	```
- [PyPi](https://pypi.org/project/nitpick) (📥 11K / month · 📦 3 · ⏱️ 08.11.2021):
	```
	pip install nitpick
	```
</details>
<details><summary><b><a href="https://github.com/predictive-analytics-lab/data-science-types">data-science-types</a></b> (🥉22 ·  ⭐ 190 · 💤) - Mypy stubs, i.e., type information, for numpy, pandas.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/predictive-analytics-lab/data-science-types) (👨‍💻 44 · 🔀 57 · 📦 160 · 📋 62 - 62% open · ⏱️ 16.02.2021):

	```
	git clone https://github.com/predictive-analytics-lab/data-science-types
	```
- [PyPi](https://pypi.org/project/data-science-types) (📥 34K / month · 📦 8 · ⏱️ 16.02.2021):
	```
	pip install data-science-types
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/Fixit">Fixit</a></b> (🥉21 ·  ⭐ 290) - Fixit is a Python Lint Framework based on LibCST. It comes with useful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Instagram/Fixit) (👨‍💻 29 · 🔀 41 · 📦 14 · 📋 57 - 56% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/Instagram/Fixit
	```
- [PyPi](https://pypi.org/project/fixit) (📥 6.4K / month · 📦 2 · ⏱️ 30.07.2021):
	```
	pip install fixit
	```
</details>
<details><summary><b><a href="https://github.com/peterjc/flake8-black">flake8-black</a></b> (🥉20 ·  ⭐ 100 · 📉) - flake8 plugin to run black for checking Python coding style. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/peterjc/flake8-black) (👨‍💻 5 · 🔀 8 · 📦 1.6K · 📋 21 - 33% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/peterjc/flake8-black
	```
- [PyPi](https://pypi.org/project/flake8-black) (📥 200K / month · 📦 120 · ⏱️ 16.07.2021):
	```
	pip install flake8-black
	```
- [Conda](https://anaconda.org/conda-forge/flake8-black) (📥 190K · ⏱️ 17.07.2021):
	```
	conda install -c conda-forge flake8-black
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-builtins">flake8-builtins</a></b> (🥉20 ·  ⭐ 76) - Check for python builtins being used as variables or.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-builtins) (👨‍💻 15 · 🔀 19 · 📦 3.1K · 📋 34 - 5% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/gforcada/flake8-builtins
	```
- [PyPi](https://pypi.org/project/flake8-builtins) (📥 330K / month · 📦 300 · ⏱️ 14.05.2020):
	```
	pip install flake8-builtins
	```
- [Conda](https://anaconda.org/conda-forge/flake8-builtins) (📥 130K · ⏱️ 18.05.2020):
	```
	conda install -c conda-forge flake8-builtins
	```
</details>
<details><summary><b><a href="https://github.com/life4/flakehell">flakehell</a></b> (🥉19 ·  ⭐ 220 · 💤) - Flake8 wrapper to make it nice, legacy-friendly, configurable. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/life4/flakehell) (👨‍💻 16 · 🔀 33 · 📥 57 · ⏱️ 11.01.2021):

	```
	git clone https://github.com/life4/flakehell
	```
- [PyPi](https://pypi.org/project/flakehell) (📥 31K / month · 📦 12 · ⏱️ 11.01.2021):
	```
	pip install flakehell
	```
</details>
<details><summary><b><a href="https://github.com/deppen8/pandas-vet">pandas-vet</a></b> (🥉19 ·  ⭐ 120 · 💤) - A plugin for Flake8 that checks pandas code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deppen8/pandas-vet) (👨‍💻 10 · 🔀 15 · 📥 39 · 📦 58 · 📋 50 - 42% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/deppen8/pandas-vet
	```
- [PyPi](https://pypi.org/project/pandas-vet) (📥 4.9K / month · 📦 3 · ⏱️ 01.02.2020):
	```
	pip install pandas-vet
	```
- [Conda](https://anaconda.org/conda-forge/pandas-vet) (📥 7.9K · ⏱️ 01.02.2020):
	```
	conda install -c conda-forge pandas-vet
	```
</details>
<details><summary><b><a href="https://github.com/jschaf/pylint-flask">pylint-flask</a></b> (🥉19 ·  ⭐ 59 · 💤) - A Pylint plugin to analyze Flask applications. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jschaf/pylint-flask) (👨‍💻 7 · 🔀 9 · 📦 5.6K · 📋 10 - 50% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/jschaf/pylint-flask
	```
- [PyPi](https://pypi.org/project/pylint-flask) (📥 160K / month · 📦 360 · ⏱️ 30.01.2019):
	```
	pip install pylint-flask
	```
- [Conda](https://anaconda.org/conda-forge/pylint-flask) (📥 54K · ⏱️ 02.02.2019):
	```
	conda install -c conda-forge pylint-flask
	```
</details>
<details><summary><b><a href="https://github.com/justinabrahms/imhotep">imhotep</a></b> (🥉18 ·  ⭐ 220) - A static-analysis bot for Github. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/justinabrahms/imhotep) (👨‍💻 16 · 🔀 37 · 📦 9 · 📋 46 - 50% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/justinabrahms/imhotep
	```
- [PyPi](https://pypi.org/project/imhotep) (📥 46 / month · 📦 5 · ⏱️ 18.09.2016):
	```
	pip install imhotep
	```
</details>
<details><summary><b><a href="https://github.com/hchasestevens/bellybutton">bellybutton</a></b> (🥉16 ·  ⭐ 230) - Custom Python linting through AST expressions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hchasestevens/bellybutton) (👨‍💻 5 · 🔀 11 · 📦 15 · 📋 14 - 57% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/hchasestevens/bellybutton
	```
- [PyPi](https://pypi.org/project/bellybutton) (📥 5.5K / month · 📦 1 · ⏱️ 27.11.2020):
	```
	pip install bellybutton
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/pep8-naming">pep8-naming</a></b> (🥈28 ·  ⭐ 350) - Naming Convention checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/PyCQA/flake8-import-order">flake8-import-order</a></b> (🥉24 ·  ⭐ 250 · 💀) - Flake8 plugin that checks import order against.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ambv/flake8-mypy">flake8-mypy</a></b> (🥉19 ·  ⭐ 100 · 💀) - A plugin for flake8 integrating Mypy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tylerwince/flake8-bandit">flake8-bandit</a></b> (🥉18 ·  ⭐ 65 · 💀) - Automated security testing using bandit and flake8. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/cemsbr/yala">yala</a></b> (🥉17 ·  ⭐ 13) - Yet Another Linter Aggregator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bndr/pycycle">pycycle</a></b> (🥉15 ·  ⭐ 300 · 💀) - Tool for pinpointing circular imports in Python. Find cyclic imports.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lyft/linty_fresh">linty_fresh</a></b> (🥉13 ·  ⭐ 180 · 💀) - Surface lint errors during code review. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code>mypy</code>
</details>
<br>

## Code Formatters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/psf/black">black</a></b> (🥇43 ·  ⭐ 24K · 📈) - The uncompromising Python code formatter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/black) (👨‍💻 290 · 🔀 1.5K · 📥 20K · 📦 110K · 📋 1.8K - 19% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/psf/black
	```
- [PyPi](https://pypi.org/project/black) (📥 8.7M / month · 📦 6.5K · ⏱️ 05.12.2021):
	```
	pip install black
	```
- [Conda](https://anaconda.org/conda-forge/black) (📥 2.7M · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/isort">isort</a></b> (🥈40 ·  ⭐ 4.4K) - A Python utility / library to sort imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/isort) (👨‍💻 250 · 🔀 430 · 📦 210K · 📋 1K - 3% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/PyCQA/isort
	```
- [PyPi](https://pypi.org/project/isort) (📥 14M / month · 📦 14K · ⏱️ 09.11.2021):
	```
	pip install isort
	```
- [Conda](https://anaconda.org/conda-forge/isort) (📥 2.7M · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge isort
	```
</details>
<details><summary><b><a href="https://github.com/google/yapf">yapf</a></b> (🥈38 ·  ⭐ 12K) - A formatter for Python files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/yapf) (👨‍💻 140 · 🔀 840 · 📦 28K · 📋 730 - 46% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/google/yapf
	```
- [PyPi](https://pypi.org/project/yapf) (📥 1.4M / month · 📦 2.1K · ⏱️ 26.12.2021):
	```
	pip install yapf
	```
- [Conda](https://anaconda.org/conda-forge/yapf) (📥 910K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge yapf
	```
</details>
<details><summary><b><a href="https://github.com/hhatto/autopep8">autopep8</a></b> (🥉36 ·  ⭐ 4K) - A tool that automatically formats Python code to conform to the PEP 8.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/autopep8) (👨‍💻 51 · 🔀 250 · 📦 100K · 📋 430 - 21% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/hhatto/autopep8
	```
- [PyPi](https://pypi.org/project/autopep8) (📥 2.2M / month · 📦 5.6K · ⏱️ 24.10.2021):
	```
	pip install autopep8
	```
- [Conda](https://anaconda.org/conda-forge/autopep8) (📥 590K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge autopep8
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/myint/docformatter">docformatter</a></b> (🥉24 ·  ⭐ 240 · 💀) - Formats docstrings to follow PEP 257. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/myint/pyformat">pyformat</a></b> (🥉17 ·  ⭐ 84 · 💀) - Formats Python code to follow a consistent style. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
</details>
<br>

## Code Refactoring

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/davidhalter/jedi">jedi</a></b> (🥇41 ·  ⭐ 5K) - Awesome autocompletion, static analysis and refactoring library for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/jedi) (👨‍💻 150 · 🔀 460 · 📦 170K · 📋 1.3K - 2% open · ⏱️ 25.12.2021):

	```
	git clone https://github.com/davidhalter/jedi
	```
- [PyPi](https://pypi.org/project/jedi) (📥 16M / month · 📦 8.3K · ⏱️ 17.11.2021):
	```
	pip install jedi
	```
- [Conda](https://anaconda.org/conda-forge/jedi) (📥 7.4M · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge jedi
	```
</details>
<details><summary><b><a href="https://github.com/python-rope/rope">rope</a></b> (🥇36 ·  ⭐ 1.3K) - a python refactoring library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-rope/rope) (👨‍💻 68 · 🔀 150 · 📦 34K · 📋 230 - 30% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/python-rope/rope
	```
- [PyPi](https://pypi.org/project/rope) (📥 490K / month · 📦 1.6K · ⏱️ 15.12.2021):
	```
	pip install rope
	```
- [Conda](https://anaconda.org/conda-forge/rope) (📥 610K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge rope
	```
</details>
<details><summary><b><a href="https://github.com/asottile/pyupgrade">pyupgrade</a></b> (🥈29 ·  ⭐ 1.3K) - A tool (and pre-commit hook) to automatically upgrade syntax for newer.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/pyupgrade) (👨‍💻 22 · 🔀 91 · 📋 260 - 3% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/asottile/pyupgrade
	```
- [PyPi](https://pypi.org/project/pyupgrade) (📥 150K / month · 📦 34 · ⏱️ 01.01.2022):
	```
	pip install pyupgrade
	```
- [Conda](https://anaconda.org/conda-forge/pyupgrade) (📥 300K · ⏱️ 01.01.2022):
	```
	conda install -c conda-forge pyupgrade
	```
</details>
<details><summary><b><a href="https://github.com/jendrikseipp/vulture">vulture</a></b> (🥈25 ·  ⭐ 2K) - Find dead Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jendrikseipp/vulture) (👨‍💻 30 · 🔀 93 · 📦 1.4K · 📋 150 - 9% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/jendrikseipp/vulture
	```
- [PyPi](https://pypi.org/project/vulture) (📥 180K / month · 📦 220 · ⏱️ 16.01.2021):
	```
	pip install vulture
	```
- [Conda](https://anaconda.org/conda-forge/vulture) (📥 51K · ⏱️ 11.08.2020):
	```
	conda install -c conda-forge vulture
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/redbaron">redbaron</a></b> (🥈25 ·  ⭐ 620) - Bottom-up approach to refactoring in python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/redbaron) (👨‍💻 34 · 🔀 67 · 📦 340 · 📋 130 - 63% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/pycqa/redbaron
	```
- [PyPi](https://pypi.org/project/redbaron) (📥 24K / month · 📦 120 · ⏱️ 17.03.2019):
	```
	pip install redbaron
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/baron">baron</a></b> (🥈25 ·  ⭐ 270) - IDE allow you to refactor code, Baron allows you to write refactoring.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/baron) (👨‍💻 33 · 🔀 52 · 📦 190 · 📋 75 - 61% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/PyCQA/baron
	```
- [PyPi](https://pypi.org/project/baron) (📥 25K / month · 📦 59 · ⏱️ 09.12.2021):
	```
	pip install baron
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/MonkeyType">MonkeyType</a></b> (🥉24 ·  ⭐ 3.6K) - A Python library that generates static type annotations by.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Instagram/MonkeyType) (👨‍💻 37 · 🔀 130 · 📦 160 · 📋 150 - 24% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/Instagram/MonkeyType
	```
- [PyPi](https://pypi.org/project/monkeytype) (📥 25K / month · 📦 23 · ⏱️ 21.05.2021):
	```
	pip install monkeytype
	```
- [Conda](https://anaconda.org/conda-forge/monkeytype) (📥 38K · ⏱️ 22.05.2021):
	```
	conda install -c conda-forge monkeytype
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/Bowler">Bowler</a></b> (🥉23 ·  ⭐ 1.3K) - Safe code refactoring for modern Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/Bowler) (👨‍💻 26 · 🔀 88 · 📋 80 - 57% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/facebookincubator/Bowler
	```
- [PyPi](https://pypi.org/project/bowler) (📥 39K / month · 📦 7 · ⏱️ 17.09.2020):
	```
	pip install bowler
	```
- [Conda](https://anaconda.org/conda-forge/bowler) (📥 11K · ⏱️ 12.06.2019):
	```
	conda install -c conda-forge bowler
	```
</details>
<details><summary><b><a href="https://github.com/asottile/add-trailing-comma">add-trailing-comma</a></b> (🥉22 ·  ⭐ 210) - A tool (and pre-commit hook) to automatically add trailing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/add-trailing-comma) (👨‍💻 9 · 🔀 14 · 📋 38 - 2% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/asottile/add-trailing-comma
	```
- [PyPi](https://pypi.org/project/add-trailing-comma) (📥 17K / month · 📦 11 · ⏱️ 20.11.2021):
	```
	pip install add-trailing-comma
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/pyannotate">pyannotate</a></b> (🥉21 ·  ⭐ 1.3K) - Auto-generate PEP-484 annotations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/pyannotate) (👨‍💻 17 · 🔀 54 · 📦 66 · 📋 59 - 44% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dropbox/pyannotate
	```
- [PyPi](https://pypi.org/project/pyannotate) (📥 2.9K / month · 📦 18 · ⏱️ 16.09.2019):
	```
	pip install pyannotate
	```
</details>
<details><summary><b><a href="https://github.com/hakancelik96/unimport">unimport</a></b> (🥉19 ·  ⭐ 120) - A linter, formatter for finding and removing unused import statements. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hakancelik96/unimport) (👨‍💻 13 · 🔀 13 · 📦 17 · 📋 76 - 13% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/hakancelik96/unimport
	```
- [PyPi](https://pypi.org/project/unimport) (📥 3.5K / month · ⏱️ 14.09.2021):
	```
	pip install unimport
	```
</details>
<details><summary><b><a href="https://github.com/ambv/retype">retype</a></b> (🥉16 ·  ⭐ 120) - Re-apply type annotations from .pyi stubs to your codebase. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ambv/retype) (👨‍💻 8 · 🔀 17 · 📋 15 - 46% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/ambv/retype
	```
- [PyPi](https://pypi.org/project/retype) (📥 960 / month · 📦 18 · ⏱️ 29.12.2021):
	```
	pip install retype
	```
- [Conda](https://anaconda.org/conda-forge/retype) (📥 16K · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge retype
	```
</details>
<details><summary><b><a href="https://github.com/ilevkivskyi/com2ann">com2ann</a></b> (🥉15 ·  ⭐ 100) - Tool for translation type comments to type annotations in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ilevkivskyi/com2ann) (👨‍💻 4 · 🔀 7 · 📦 7 · 📋 20 - 25% open · ⏱️ 21.08.2021):

	```
	git clone https://github.com/ilevkivskyi/com2ann
	```
- [PyPi](https://pypi.org/project/com2ann) (📥 3.7K / month · 📦 1 · ⏱️ 21.08.2021):
	```
	pip install com2ann
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/myint/autoflake">autoflake</a></b> (🥈26 ·  ⭐ 470 · 💀) - Removes unused imports and unused variables as reported by pyflakes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/myint/eradicate">eradicate</a></b> (🥉18 ·  ⭐ 120 · 💀) - Removes commented-out code from Python files. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/myint/unify">unify</a></b> (🥉18 ·  ⭐ 64 · 💀) - Modifies strings to all use the same quote where possible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/spulec/pep8ify">pep8ify</a></b> (🥉15 ·  ⭐ 120 · 💀) - A library that modifies python source code to conform to pep8. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/elmotec/massedit">massedit</a></b> (🥉15 ·  ⭐ 95 · 💀) - Programmatically edit text files with Python. Useful for source to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Code Security

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/bandit">bandit</a></b> (🥇34 ·  ⭐ 3.8K) - Bandit is a tool designed to find common security issues in Python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PyCQA/bandit) (👨‍💻 140 · 🔀 390 · 📥 140 · 📦 10K · 📋 560 - 33% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/PyCQA/bandit
	```
- [PyPi](https://pypi.org/project/bandit) (📥 1.6M / month · 📦 1.5K · ⏱️ 12.11.2021):
	```
	pip install bandit
	```
- [Conda](https://anaconda.org/conda-forge/bandit) (📥 100K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge bandit
	```
</details>
<details><summary><b><a href="https://github.com/sqlmapproject/sqlmap">sqlmap</a></b> (🥈30 ·  ⭐ 22K) - Automatic SQL injection and database takeover tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sqlmapproject/sqlmap) (👨‍💻 110 · 🔀 4.6K · 📋 4.5K - 1% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/sqlmapproject/sqlmap
	```
- [PyPi](https://pypi.org/project/sqlmap) (📥 6.1K / month · 📦 6 · ⏱️ 03.01.2022):
	```
	pip install sqlmap
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/detect-secrets">detect-secrets</a></b> (🥉29 ·  ⭐ 2.1K) - An enterprise friendly way of detecting and preventing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Yelp/detect-secrets) (👨‍💻 54 · 🔀 240 · 📋 240 - 34% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/Yelp/detect-secrets
	```
- [PyPi](https://pypi.org/project/detect-secrets) (📥 220K / month · 📦 23 · ⏱️ 14.04.2021):
	```
	pip install detect-secrets
	```
</details>
<details><summary><b><a href="https://github.com/pyupio/safety">safety</a></b> (🥉29 ·  ⭐ 1.2K · 💤) - Safety checks your installed dependencies for known security.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyupio/safety) (👨‍💻 35 · 🔀 100 · 📥 120K · 📦 3.3K · 📋 120 - 36% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pyupio/safety
	```
- [PyPi](https://pypi.org/project/safety) (📥 630K / month · 📦 320 · ⏱️ 15.01.2021):
	```
	pip install safety
	```
- [Conda](https://anaconda.org/conda-forge/safety) (📥 26K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge safety
	```
</details>
<details><summary><b><a href="https://github.com/landscapeio/dodgy">dodgy</a></b> (🥉20 ·  ⭐ 97 · 💤) - Looks at Python code to search for things which look dodgy such as.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/landscapeio/dodgy) (👨‍💻 14 · 🔀 19 · 📦 1.5K · 📋 12 - 75% open · ⏱️ 21.03.2021):

	```
	git clone https://github.com/landscapeio/dodgy
	```
- [PyPi](https://pypi.org/project/dodgy) (📥 150K / month · 📦 280 · ⏱️ 31.12.2019):
	```
	pip install dodgy
	```
- [Conda](https://anaconda.org/conda-forge/dodgy) (📥 27K · ⏱️ 10.06.2020):
	```
	conda install -c conda-forge dodgy
	```
</details>
<details><summary><b><a href="https://github.com/dlint-py/dlint">dlint</a></b> (🥉19 ·  ⭐ 79) - Dlint is a tool for encouraging best coding practices and helping ensure.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dlint-py/dlint) (👨‍💻 8 · 🔀 6 · 📋 33 - 57% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/dlint-py/dlint
	```
- [PyPi](https://pypi.org/project/dlint) (📥 82K / month · 📦 29 · ⏱️ 27.10.2021):
	```
	pip install dlint
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/dashingsoft/pyarmor">pyarmor</a></b> (🥈30 ·  ⭐ 1.3K) - A tool used to obfuscate python scripts, bind obfuscated scripts.. <code><a href="https://tldrlegal.com/search?q=SGI-B-2.0">❗️SGI-B-2.0</a></code>
- <b><a href="https://github.com/python-security/pyt">pyt</a></b> (🥉23 ·  ⭐ 2.1K · 💀) - A Static Analysis Tool for Detecting Security Vulnerabilities in.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
</details>
<br>

## Virtual Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pipenv">pipenv</a></b> (🥇43 ·  ⭐ 23K) - Python Development Workflow for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipenv) (👨‍💻 400 · 🔀 1.7K · 📦 24K · 📋 3.6K - 15% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/pypa/pipenv
	```
- [PyPi](https://pypi.org/project/pipenv) (📥 3.6M / month · 📦 1.2K · ⏱️ 08.01.2022):
	```
	pip install pipenv
	```
- [Conda](https://anaconda.org/conda-forge/pipenv) (📥 46K · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge pipenv
	```
</details>
<details><summary><b><a href="https://github.com/pypa/virtualenv">virtualenv</a></b> (🥈40 ·  ⭐ 4K) - Virtual Python Environment builder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/virtualenv) (👨‍💻 220 · 🔀 920 · 📋 1.2K - 5% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/pypa/virtualenv
	```
- [PyPi](https://pypi.org/project/virtualenv) (📥 20M / month · 📦 18K · ⏱️ 02.01.2022):
	```
	pip install virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/virtualenv) (📥 1.4M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv">pyenv</a></b> (🥈32 ·  ⭐ 26K) - Simple Python version management. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv) (👨‍💻 360 · 🔀 2.3K · 📋 1.4K - 2% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/pyenv/pyenv
	```
- [PyPi](https://pypi.org/project/pyenv) (📥 6.1K / month · 📦 1 · ⏱️ 12.01.2019):
	```
	pip install pyenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-virtualenv">pyenv-virtualenv</a></b> (🥉20 ·  ⭐ 4.7K) - a pyenv plugin to manage virtualenv (a.k.a. python-virtualenv). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-virtualenv) (👨‍💻 46 · 🔀 310 · 📋 330 - 40% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/pyenv/pyenv-virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-installer">pyenv-installer</a></b> (🥉16 ·  ⭐ 3K) - This tool is used to install `pyenv` and friends. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-installer) (👨‍💻 33 · 🔀 320 · 📋 69 - 7% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/pyenv/pyenv-installer
	```
</details>
<details><summary><b><a href="https://github.com/spotify/dh-virtualenv">dh-virtualenv</a></b> (🥉16 ·  ⭐ 1.5K) - Python virtualenvs in Debian packages. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/spotify/dh-virtualenv) (👨‍💻 58 · 🔀 160 · 📋 190 - 12% open · ⏱️ 10.11.2021):

	```
	git clone https://github.com/spotify/dh-virtualenv
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/sashahart/vex">vex</a></b> (🥉18 ·  ⭐ 370 · 💀) - Run a command in the named virtualenv. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gtalarico/pipenv-pipes">pipenv-pipes</a></b> (🥉12 ·  ⭐ 130 · 💀) - A PipEnv Environment Switcher. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Dependency & Package Mangers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pip">pip</a></b> (🥇45 ·  ⭐ 7.7K · 📈) - The Python package installer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pip) (👨‍💻 650 · 🔀 2.4K · 📦 69K · 📋 6.1K - 15% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/pypa/pip
	```
- [PyPi](https://pypi.org/project/pip) (📥 74M / month · 📦 10K · ⏱️ 22.10.2021):
	```
	pip install pip
	```
- [Conda](https://anaconda.org/conda-forge/pip) (📥 29M · ⏱️ 22.10.2021):
	```
	conda install -c conda-forge pip
	```
</details>
<details><summary><b><a href="https://github.com/python-poetry/poetry">poetry</a></b> (🥈39 ·  ⭐ 18K) - Python dependency management and packaging made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-poetry/poetry) (👨‍💻 320 · 🔀 1.5K · 📥 10M · 📋 3.6K - 34% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/python-poetry/poetry
	```
- [PyPi](https://pypi.org/project/poetry) (📥 4M / month · 📦 110 · ⏱️ 28.11.2021):
	```
	pip install poetry
	```
- [Conda](https://anaconda.org/conda-forge/poetry) (📥 350K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge poetry
	```
</details>
<details><summary><b><a href="https://github.com/conda/conda">conda</a></b> (🥈39 ·  ⭐ 4.5K) - OS-agnostic, system-level binary package manager and ecosystem. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/conda) (👨‍💻 380 · 🔀 1.1K · 📋 8.3K - 22% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/conda/conda
	```
- [PyPi](https://pypi.org/project/conda) (📥 71K / month · 📦 1.1K · ⏱️ 22.04.2017):
	```
	pip install conda
	```
- [Conda](https://anaconda.org/conda-forge/conda) (📥 24M · ⏱️ 23.11.2021):
	```
	conda install -c conda-forge conda
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/pip-tools">pip-tools</a></b> (🥈34 ·  ⭐ 5.4K) - A set of tools to keep your pinned Python dependencies fresh. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/pip-tools) (👨‍💻 160 · 🔀 480 · 📋 800 - 16% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/jazzband/pip-tools
	```
- [PyPi](https://pypi.org/project/pip-tools) (📥 3.2M / month · 📦 1.8K · ⏱️ 12.10.2021):
	```
	pip install pip-tools
	```
- [Conda](https://anaconda.org/conda-forge/pip-tools) (📥 22K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge pip-tools
	```
</details>
<details><summary><b><a href="https://github.com/bndr/pipreqs">pipreqs</a></b> (🥉30 ·  ⭐ 4K) - pipreqs - Generate pip requirements.txt file based on imports of any.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bndr/pipreqs) (👨‍💻 51 · 🔀 270 · 📦 8.4K · 📋 190 - 52% open · ⏱️ 23.10.2021):

	```
	git clone https://github.com/bndr/pipreqs
	```
- [PyPi](https://pypi.org/project/pipreqs) (📥 260K / month · 📦 320 · ⏱️ 23.10.2021):
	```
	pip install pipreqs
	```
- [Conda](https://anaconda.org/conda-forge/pipreqs) (📥 23K · ⏱️ 14.11.2019):
	```
	conda install -c conda-forge pipreqs
	```
</details>
<details><summary><b><a href="https://github.com/pypa/pipx">pipx</a></b> (🥉28 ·  ⭐ 4.5K) - Install and Run Python Applications in Isolated Environments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipx) (👨‍💻 71 · 🔀 210 · 📋 450 - 22% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/pypa/pipx
	```
- [PyPi](https://pypi.org/project/pipx) (📥 70K / month · 📦 6 · ⏱️ 04.01.2022):
	```
	pip install pipx
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/mamba">mamba</a></b> (🥉27 ·  ⭐ 2.6K) - The Fast Cross-Platform Package Manager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/mamba) (👨‍💻 66 · 🔀 140 · 📋 680 - 29% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/mamba-org/mamba
	```
- [Conda](https://anaconda.org/conda-forge/mamba) (📥 1.8M · ⏱️ 08.12.2021):
	```
	conda install -c conda-forge mamba
	```
</details>
<details><summary><b><a href="https://github.com/dephell/dephell">dephell</a></b> (🥉25 ·  ⭐ 1.7K · 💤) - Python project management. Manage packages: convert between formats,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dephell/dephell) (👨‍💻 37 · 🔀 110 · 📥 170 · 📦 330 · 📋 270 - 40% open · ⏱️ 11.01.2021):

	```
	git clone https://github.com/dephell/dephell
	```
- [PyPi](https://pypi.org/project/dephell) (📥 4.7K / month · 📦 12 · ⏱️ 28.04.2020):
	```
	pip install dephell
	```
</details>
<details><summary><b><a href="https://github.com/David-OConnor/pyflow">pyflow</a></b> (🥉19 ·  ⭐ 970) - An installation and dependency system for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/David-OConnor/pyflow) (👨‍💻 28 · 🔀 38 · 📥 3.8K · 📋 110 - 38% open · ⏱️ 04.12.2021):

	```
	git clone https://github.com/David-OConnor/pyflow
	```
- [PyPi](https://pypi.org/project/pyflow) (📥 130 / month · 📦 1 · ⏱️ 02.07.2021):
	```
	pip install pyflow
	```
</details>
<details><summary><b><a href="https://github.com/jaraco/pip-run">pip-run</a></b> (🥉18 ·  ⭐ 62) - pip-run - dynamic dependency loader for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/pip-run) (👨‍💻 11 · 🔀 10 · 📋 43 - 6% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/jaraco/pip-run
	```
- [PyPi](https://pypi.org/project/pip-run) (📥 6K / month · 📦 1 · ⏱️ 08.01.2022):
	```
	pip install pip-run
	```
</details>
<br>

## Code Metrics & Complexity

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/prospector">prospector</a></b> (🥇29 ·  ⭐ 1.6K) - Inspects Python source files and provides information about.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/prospector) (👨‍💻 78 · 🔀 140 · 📋 290 - 19% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/PyCQA/prospector
	```
- [PyPi](https://pypi.org/project/prospector) (📥 390K / month · 📦 660 · ⏱️ 08.12.2021):
	```
	pip install prospector
	```
- [Conda](https://anaconda.org/conda-forge/prospector) (📥 27K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge prospector
	```
</details>
<details><summary><b><a href="https://github.com/rubik/radon">radon</a></b> (🥇29 ·  ⭐ 1.3K) - Various code metrics for Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/radon) (👨‍💻 49 · 🔀 97 · 📦 2.2K · 📋 160 - 13% open · ⏱️ 08.08.2021):

	```
	git clone https://github.com/rubik/radon
	```
- [PyPi](https://pypi.org/project/radon) (📥 230K / month · 📦 600 · ⏱️ 15.12.2021):
	```
	pip install radon
	```
- [Conda](https://anaconda.org/conda-forge/radon) (📥 37K · ⏱️ 07.09.2021):
	```
	conda install -c conda-forge radon
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/mccabe">mccabe</a></b> (🥇29 ·  ⭐ 450 · 💤) - McCabe complexity checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/mccabe) (👨‍💻 21 · 🔀 42 · 📦 240K · 📋 40 - 15% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/PyCQA/mccabe
	```
- [PyPi](https://pypi.org/project/mccabe) (📥 15M / month · 📦 16K · ⏱️ 26.01.2017):
	```
	pip install mccabe
	```
- [Conda](https://anaconda.org/conda-forge/mccabe) (📥 3.8M · ⏱️ 08.07.2018):
	```
	conda install -c conda-forge mccabe
	```
</details>
<details><summary><b><a href="https://github.com/tonybaloney/wily">wily</a></b> (🥉21 ·  ⭐ 840) - A Python application for tracking, reporting on timing and complexity in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tonybaloney/wily) (👨‍💻 16 · 🔀 45 · 📋 80 - 35% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/tonybaloney/wily
	```
- [PyPi](https://pypi.org/project/wily) (📥 11K / month · 📦 9 · ⏱️ 01.07.2021):
	```
	pip install wily
	```
</details>
<details><summary><b><a href="https://github.com/rubik/xenon">xenon</a></b> (🥉21 ·  ⭐ 200) - Monitoring tool based on radon. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/xenon) (👨‍💻 8 · 🔀 16 · 📦 280 · 📋 32 - 21% open · ⏱️ 03.09.2021):

	```
	git clone https://github.com/rubik/xenon
	```
- [PyPi](https://pypi.org/project/xenon) (📥 48K / month · 📦 69 · ⏱️ 03.09.2021):
	```
	pip install xenon
	```
- [Conda](https://anaconda.org/conda-forge/xenon) (📥 14K · ⏱️ 12.10.2019):
	```
	conda install -c conda-forge xenon
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/mschwager/cohesion">cohesion</a></b> (🥉12 ·  ⭐ 140 · 💀) - A tool for measuring Python class cohesion. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tqdm/tqdm">tqdm</a></b> (🥇40 ·  ⭐ 21K) - A Fast, Extensible Progress Bar for Python and CLI. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/tqdm/tqdm) (👨‍💻 110 · 🔀 1.1K · 📥 8.1K · 📦 240K · 📋 870 - 37% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tqdm/tqdm
	```
- [PyPi](https://pypi.org/project/tqdm) (📥 27M / month · 📦 21K · ⏱️ 15.12.2021):
	```
	pip install tqdm
	```
- [Conda](https://anaconda.org/conda-forge/tqdm) (📥 9.3M · ⏱️ 20.09.2021):
	```
	conda install -c conda-forge tqdm
	```
- [Docker Hub](https://hub.docker.com/r/tqdm/tqdm) (📥 4K · ⭐ 2 · ⏱️ 30.10.2021):
	```
	docker pull tqdm/tqdm
	```
</details>
<details><summary><b><a href="https://github.com/Textualize/rich">rich</a></b> (🥇39 ·  ⭐ 32K) - Rich is a Python library for rich text and beautiful formatting in the terminal. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Textualize/rich) (👨‍💻 140 · 🔀 1K · 📦 10K · 📋 640 - 3% open · ⏱️ 09.01.2022):

	```
	git clone https://github.com/willmcgugan/rich
	```
- [PyPi](https://pypi.org/project/rich) (📥 2.7M / month · 📦 1.3K · ⏱️ 09.01.2022):
	```
	pip install rich
	```
- [Conda](https://anaconda.org/conda-forge/rich) (📥 570K · ⏱️ 09.01.2022):
	```
	conda install -c conda-forge rich
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/sentry-python">sentry-sdk</a></b> (🥇37 ·  ⭐ 1.1K) - The new Python SDK for Sentry.io. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/getsentry/sentry-python) (👨‍💻 120 · 🔀 260 · 📥 4.5K · 📦 17K · 📋 600 - 12% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/getsentry/sentry-python
	```
- [PyPi](https://pypi.org/project/sentry-sdk) (📥 11M / month · 📦 940 · ⏱️ 10.01.2022):
	```
	pip install sentry-sdk
	```
- [Conda](https://anaconda.org/conda-forge/sentry-sdk) (📥 120K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge sentry-sdk
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈34 ·  ⭐ 1.9K) - Structured Logging for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 84 · 🔀 150 · 📋 210 - 12% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 2.7M / month · 📦 900 · ⏱️ 16.12.2021):
	```
	pip install structlog
	```
- [Conda](https://anaconda.org/conda-forge/structlog) (📥 160K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge structlog
	```
</details>
<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥈33 ·  ⭐ 11K) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 30 · 🔀 470 · 📦 13K · 📋 510 - 18% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 1.9M / month · 📦 1.1K · ⏱️ 20.09.2020):
	```
	pip install loguru
	```
- [Conda](https://anaconda.org/conda-forge/loguru) (📥 340K · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge loguru
	```
</details>
<details><summary><b><a href="https://github.com/WoLpH/python-progressbar">progressbar2</a></b> (🥈33 ·  ⭐ 740) - Progressbar 2 - A progress bar for Python 2 and Python 3 - pip.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/WoLpH/python-progressbar) (👨‍💻 40 · 🔀 100 · 📥 1.6K · 📦 14K · 📋 200 - 5% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/WoLpH/python-progressbar
	```
- [PyPi](https://pypi.org/project/progressbar2) (📥 3.9M / month · 📦 1.5K · ⏱️ 05.01.2022):
	```
	pip install progressbar2
	```
- [Conda](https://anaconda.org/conda-forge/progressbar2) (📥 380K · ⏱️ 09.09.2020):
	```
	conda install -c conda-forge progressbar2
	```
</details>
<details><summary><b><a href="https://github.com/madzak/python-json-logger">python-json-logger</a></b> (🥈32 ·  ⭐ 1.2K) - Json Formatter for the standard python logger. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madzak/python-json-logger) (👨‍💻 46 · 🔀 170 · 📦 20K · 📋 70 - 34% open · ⏱️ 27.07.2021):

	```
	git clone https://github.com/madzak/python-json-logger
	```
- [PyPi](https://pypi.org/project/python-json-logger) (📥 4M / month · 📦 690 · ⏱️ 27.07.2021):
	```
	pip install python-json-logger
	```
- [Conda](https://anaconda.org/conda-forge/python-json-logger) (📥 1M · ⏱️ 12.10.2020):
	```
	conda install -c conda-forge python-json-logger
	```
</details>
<details><summary><b><a href="https://github.com/astanin/python-tabulate">tabulate</a></b> (🥈30 ·  ⭐ 1.1K) - Pretty-print tabular data in Python, a library and a command-line.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/astanin/python-tabulate) (👨‍💻 68 · 🔀 84 · 📦 60K · 📋 110 - 45% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/astanin/python-tabulate
	```
- [PyPi](https://pypi.org/project/tabulate) (📥 33M / month · 📦 6.3K · ⏱️ 22.02.2021):
	```
	pip install tabulate
	```
- [Conda](https://anaconda.org/conda-forge/tabulate) (📥 1.8M · ⏱️ 22.02.2021):
	```
	conda install -c conda-forge tabulate
	```
</details>
<details><summary><b><a href="https://github.com/borntyping/python-colorlog">colorlog</a></b> (🥉29 ·  ⭐ 730) - A colored formatter for the python logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/borntyping/python-colorlog) (👨‍💻 30 · 🔀 76 · 📦 13K · ⏱️ 08.11.2021):

	```
	git clone https://github.com/borntyping/python-colorlog
	```
- [PyPi](https://pypi.org/project/colorlog) (📥 4.8M / month · 📦 2.4K · ⏱️ 08.11.2021):
	```
	pip install colorlog
	```
- [Conda](https://anaconda.org/conda-forge/colorlog) (📥 460K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge colorlog
	```
</details>
<details><summary><b><a href="https://github.com/ines/wasabi">wasabi</a></b> (🥉28 ·  ⭐ 320) - A lightweight console printing and formatting toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ines/wasabi) (👨‍💻 7 · 🔀 20 · 📦 16K · 📋 6 - 50% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/ines/wasabi
	```
- [PyPi](https://pypi.org/project/wasabi) (📥 3.6M / month · 📦 270 · ⏱️ 06.12.2021):
	```
	pip install wasabi
	```
- [Conda](https://anaconda.org/conda-forge/wasabi) (📥 560K · ⏱️ 07.12.2021):
	```
	conda install -c conda-forge wasabi
	```
</details>
<details><summary><b><a href="https://github.com/liiight/notifiers">notifiers</a></b> (🥉27 ·  ⭐ 2.1K) - The easy way to send notifications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/liiight/notifiers) (👨‍💻 16 · 🔀 78 · 📦 200 · 📋 92 - 41% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/liiight/notifiers
	```
- [PyPi](https://pypi.org/project/notifiers) (📥 300K / month · 📦 14 · ⏱️ 05.10.2019):
	```
	pip install notifiers
	```
</details>
<details><summary><b><a href="https://github.com/rsalmei/alive-progress">alive-progress</a></b> (🥉26 ·  ⭐ 3K) - A new kind of Progress Bar, with real-time throughput, ETA, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rsalmei/alive-progress) (👨‍💻 1 · 🔀 130 · 📦 540 · 📋 94 - 26% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/rsalmei/alive-progress
	```
- [PyPi](https://pypi.org/project/alive-progress) (📥 21K / month · 📦 49 · ⏱️ 19.10.2021):
	```
	pip install alive-progress
	```
- [Conda](https://anaconda.org/conda-forge/alive-progress) (📥 12K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge alive-progress
	```
</details>
<details><summary><b><a href="https://github.com/xolox/python-coloredlogs">python-coloredlogs</a></b> (🥉26 ·  ⭐ 450 · 💤) - Colored terminal output for Pythons logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xolox/python-coloredlogs) (👨‍💻 16 · 🔀 37 · 📦 10K · 📋 74 - 33% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/xolox/python-coloredlogs
	```
- [PyPi](https://pypi.org/project/coloredlogs) (📥 1.8M / month · 📦 1.7K · ⏱️ 11.06.2021):
	```
	pip install coloredlogs
	```
</details>
<details><summary><b><a href="https://github.com/shobrook/rebound">rebound</a></b> (🥉24 ·  ⭐ 3.8K · 💤) - Command-line tool that instantly fetches Stack Overflow results when.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/shobrook/rebound) (👨‍💻 16 · 🔀 360 · 📥 180 · 📦 22 · 📋 58 - 34% open · ⏱️ 04.01.2021):

	```
	git clone https://github.com/shobrook/rebound
	```
- [PyPi](https://pypi.org/project/rebound) (📥 1.8K / month · 📦 16 · ⏱️ 12.01.2022):
	```
	pip install rebound
	```
- [Conda](https://anaconda.org/conda-forge/rebound) (📥 170K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge rebound
	```
</details>
<details><summary><b><a href="https://github.com/Qix-/better-exceptions">better-exceptions</a></b> (🥉22 ·  ⭐ 4.1K) - Pretty and useful exceptions in Python, automatically. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Qix-/better-exceptions) (👨‍💻 15 · 🔀 200 · 📋 70 - 41% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/Qix-/better-exceptions
	```
- [PyPi](https://pypi.org/project/better-exceptions) (📥 25K / month · 📦 58 · ⏱️ 29.01.2021):
	```
	pip install better-exceptions
	```
</details>
<details><summary><b><a href="https://github.com/onelivesleft/PrettyErrors">PrettyErrors</a></b> (🥉22 ·  ⭐ 2.4K) - Prettify Python exception output to make it legible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/onelivesleft/PrettyErrors) (👨‍💻 5 · 🔀 71 · 📋 37 - 2% open · ⏱️ 24.11.2021):

	```
	git clone https://github.com/onelivesleft/PrettyErrors
	```
- [PyPi](https://pypi.org/project/pretty_errors) (📥 22K / month · 📦 39 · ⏱️ 24.11.2021):
	```
	pip install pretty_errors
	```
</details>
<details><summary><b><a href="https://github.com/cknd/stackprinter">stackprinter</a></b> (🥉22 ·  ⭐ 1.2K · 💤) - Debugging-friendly exceptions for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cknd/stackprinter) (👨‍💻 6 · 🔀 33 · 📦 86 · 📋 26 - 42% open · ⏱️ 01.01.2021):

	```
	git clone https://github.com/cknd/stackprinter
	```
- [PyPi](https://pypi.org/project/stackprinter) (📥 300K / month · 📦 20 · ⏱️ 31.10.2020):
	```
	pip install stackprinter
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/python-devtools">python-devtools</a></b> (🥉19 ·  ⭐ 450) - Dev tools for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/python-devtools) (👨‍💻 7 · 🔀 16 · 📦 530 · 📋 36 - 5% open · ⏱️ 08.09.2021):

	```
	git clone https://github.com/samuelcolvin/python-devtools
	```
- [PyPi](https://pypi.org/project/python-devtools) (📥 440 / month · 📦 1 · ⏱️ 21.08.2017):
	```
	pip install python-devtools
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/getlogbook/logbook">logbook</a></b> (🥈32 ·  ⭐ 1.4K · 💀) - A cool logging replacement for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jazzband/prettytable">prettytable</a></b> (🥉28 ·  ⭐ 650) - Display tabular data in a visually appealing ASCII table.. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/skorokithakis/tbvaccine">tbvaccine</a></b> (🥉15 ·  ⭐ 360 · 💀) - A small utility to pretty-print Python tracebacks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Documentation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/sphinx-doc/sphinx">sphinx</a></b> (🥇44 ·  ⭐ 4.4K) - Main repository for the Sphinx documentation builder. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sphinx-doc/sphinx) (👨‍💻 700 · 🔀 1.6K · 📦 180K · 📋 5.9K - 16% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/sphinx-doc/sphinx
	```
- [PyPi](https://pypi.org/project/sphinx) (📥 3.8M / month · 📦 59K · ⏱️ 19.12.2021):
	```
	pip install sphinx
	```
- [Conda](https://anaconda.org/conda-forge/sphinx) (📥 4.6M · ⏱️ 19.12.2021):
	```
	conda install -c conda-forge sphinx
	```
</details>
<details><summary><b><a href="https://github.com/mkdocs/mkdocs">mkdocs</a></b> (🥇41 ·  ⭐ 13K) - Project documentation with Markdown. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocs/mkdocs) (👨‍💻 210 · 🔀 1.8K · 📦 18K · 📋 1.6K - 6% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/mkdocs/mkdocs
	```
- [PyPi](https://pypi.org/project/mkdocs) (📥 650K / month · 📦 3.5K · ⏱️ 15.12.2021):
	```
	pip install mkdocs
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs) (📥 160K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge mkdocs
	```
</details>
<details><summary><b><a href="https://github.com/squidfunk/mkdocs-material">mkdocs-material</a></b> (🥇40 ·  ⭐ 8.5K) - Technical documentation that just works. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/squidfunk/mkdocs-material) (👨‍💻 140 · 🔀 2K · 📦 11K · 📋 1.3K - 0% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/squidfunk/mkdocs-material
	```
- [PyPi](https://pypi.org/project/mkdocs-material) (📥 660K / month · 📦 1.1K · ⏱️ 11.01.2022):
	```
	pip install mkdocs-material
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs-material) (📥 78K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge mkdocs-material
	```
</details>
<details><summary><b><a href="https://github.com/numpy/numpydoc">numpydoc</a></b> (🥈34 ·  ⭐ 19K) - Numpys Sphinx extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/numpy/numpydoc) (👨‍💻 70 · 🔀 6.3K · 📦 30K · 📋 160 - 36% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/numpy/numpydoc
	```
- [PyPi](https://pypi.org/project/numpydoc) (📥 210K / month · 📦 4.3K · ⏱️ 01.07.2020):
	```
	pip install numpydoc
	```
- [Conda](https://anaconda.org/conda-forge/numpydoc) (📥 900K · ⏱️ 01.10.2020):
	```
	conda install -c conda-forge numpydoc
	```
</details>
<details><summary><b><a href="https://github.com/readthedocs/sphinx_rtd_theme">sphinx_rtd_theme</a></b> (🥈34 ·  ⭐ 3.9K) - Sphinx theme for readthedocs.org. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/readthedocs/sphinx_rtd_theme) (👨‍💻 110 · 🔀 1.6K · 📦 16 · 📋 740 - 26% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/readthedocs/sphinx_rtd_theme
	```
- [PyPi](https://pypi.org/project/sphinx_rtd_theme) (📥 1.7M / month · 📦 12K · ⏱️ 05.10.2018):
	```
	pip install sphinx_rtd_theme
	```
- [Conda](https://anaconda.org/conda-forge/sphinx_rtd_theme) (📥 2M · ⏱️ 17.09.2021):
	```
	conda install -c conda-forge sphinx_rtd_theme
	```
</details>
<details><summary><b><a href="https://github.com/bitprophet/alabaster">alabaster</a></b> (🥈31 ·  ⭐ 640) - Lightweight, configurable Sphinx theme. Now the Sphinx default!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bitprophet/alabaster) (👨‍💻 28 · 🔀 180 · 📦 57K · 📋 140 - 60% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/bitprophet/alabaster
	```
- [PyPi](https://pypi.org/project/alabaster) (📥 3.5M / month · 📦 7.7K · ⏱️ 03.10.2018):
	```
	pip install alabaster
	```
- [Conda](https://anaconda.org/conda-forge/alabaster) (📥 3.4M · ⏱️ 03.10.2018):
	```
	conda install -c conda-forge alabaster
	```
</details>
<details><summary><b><a href="https://github.com/michaeljones/breathe">breathe</a></b> (🥈31 ·  ⭐ 570) - ReStructuredText and Sphinx bridge to Doxygen. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/michaeljones/breathe) (👨‍💻 99 · 🔀 150 · 📥 180 · 📦 5.7K · 📋 480 - 25% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/michaeljones/breathe
	```
- [PyPi](https://pypi.org/project/breathe) (📥 170K / month · 📦 1K · ⏱️ 14.09.2021):
	```
	pip install breathe
	```
- [Conda](https://anaconda.org/conda-forge/breathe) (📥 250K · ⏱️ 15.09.2021):
	```
	conda install -c conda-forge breathe
	```
</details>
<details><summary><b><a href="https://github.com/mitmproxy/pdoc">pdoc</a></b> (🥈30 ·  ⭐ 1.1K) - API Documentation for Python Projects. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/mitmproxy/pdoc) (👨‍💻 33 · 🔀 120 · 📦 490 · 📋 210 - 4% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/mitmproxy/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc) (📥 93K / month · 📦 180 · ⏱️ 05.01.2022):
	```
	pip install pdoc
	```
</details>
<details><summary><b><a href="https://github.com/tox-dev/sphinx-autodoc-typehints">sphinx-autodoc-typehints</a></b> (🥈28 ·  ⭐ 390) - Type hints support for the Sphinx autodoc extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/sphinx-autodoc-typehints) (👨‍💻 34 · 🔀 76 · 📋 130 - 15% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/agronholm/sphinx-autodoc-typehints
	```
- [PyPi](https://pypi.org/project/sphinx-autodoc-typehints) (📥 320K / month · 📦 1.3K · ⏱️ 11.01.2022):
	```
	pip install sphinx-autodoc-typehints
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autodoc-typehints) (📥 260K · ⏱️ 15.04.2021):
	```
	conda install -c conda-forge sphinx-autodoc-typehints
	```
</details>
<details><summary><b><a href="https://github.com/pdoc3/pdoc">pdoc3</a></b> (🥈27 ·  ⭐ 770) - Auto-generate API documentation for Python projects. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/pdoc3/pdoc) (👨‍💻 56 · 🔀 120 · 📦 1.2K · 📋 270 - 31% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/pdoc3/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc3) (📥 160K / month · 📦 120 · ⏱️ 03.08.2021):
	```
	pip install pdoc3
	```
</details>
<details><summary><b><a href="https://github.com/mkdocstrings/mkdocstrings">mkdocstrings</a></b> (🥈27 ·  ⭐ 580) - Automatic documentation from sources, for MkDocs. <code><a href="http://bit.ly/3hkKRql">ISC</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocstrings/mkdocstrings) (👨‍💻 26 · 🔀 59 · 📋 210 - 24% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/mkdocstrings/mkdocstrings
	```
- [PyPi](https://pypi.org/project/mkdocstrings) (📥 89K / month · 📦 140 · ⏱️ 27.12.2021):
	```
	pip install mkdocstrings
	```
- [Conda](https://anaconda.org/conda-forge/mkdocstrings) (📥 11K · ⏱️ 28.12.2021):
	```
	conda install -c conda-forge mkdocstrings
	```
</details>
<details><summary><b><a href="https://github.com/ryan-roemer/sphinx-bootstrap-theme">sphinx-bootstrap-theme</a></b> (🥈27 ·  ⭐ 580) - Sphinx Bootstrap Theme. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ryan-roemer/sphinx-bootstrap-theme) (👨‍💻 38 · 🔀 210 · 📋 140 - 40% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/ryan-roemer/sphinx-bootstrap-theme
	```
- [PyPi](https://pypi.org/project/sphinx-bootstrap-theme) (📥 280K / month · 📦 590 · ⏱️ 12.09.2021):
	```
	pip install sphinx-bootstrap-theme
	```
</details>
<details><summary><b><a href="https://github.com/econchick/interrogate">interrogate</a></b> (🥉25 ·  ⭐ 330) - Explain yourself! Interrogate a codebase for docstring coverage. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/econchick/interrogate) (👨‍💻 12 · 🔀 26 · 📦 1.2K · 📋 31 - 25% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/econchick/interrogate
	```
- [PyPi](https://pypi.org/project/interrogate) (📥 67K / month · 📦 35 · ⏱️ 10.09.2021):
	```
	pip install interrogate
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/sphinx-autobuild">sphinx-autobuild</a></b> (🥉24 ·  ⭐ 370 · 💤) - Watch a Sphinx directory and rebuild the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/executablebooks/sphinx-autobuild) (👨‍💻 17 · 🔀 51 · 📋 58 - 24% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/executablebooks/sphinx-autobuild
	```
- [PyPi](https://pypi.org/project/sphinx-autobuild) (📥 180K / month · 📦 2.6K · ⏱️ 14.03.2021):
	```
	pip install sphinx-autobuild
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autobuild) (📥 80K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge sphinx-autobuild
	```
</details>
<details><summary><b><a href="https://github.com/zhaoterryy/mkdocs-pdf-export-plugin">mkdocs-pdf-export-plugin</a></b> (🥉23 ·  ⭐ 220) - An MkDocs plugin to export content pages as PDF files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zhaoterryy/mkdocs-pdf-export-plugin) (👨‍💻 11 · 🔀 34 · 📦 190 · 📋 86 - 47% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/zhaoterryy/mkdocs-pdf-export-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-pdf-export-plugin) (📥 12K / month · 📦 4 · ⏱️ 05.10.2021):
	```
	pip install mkdocs-pdf-export-plugin
	```
</details>
<details><summary><b><a href="https://github.com/bitprophet/releases">releases</a></b> (🥉23 ·  ⭐ 160) - A powerful Sphinx changelog-generating extension. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bitprophet/releases) (👨‍💻 10 · 🔀 36 · 📦 410 · 📋 76 - 43% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/bitprophet/releases
	```
- [PyPi](https://pypi.org/project/releases) (📥 12K / month · 📦 360 · ⏱️ 11.01.2020):
	```
	pip install releases
	```
</details>
<details><summary><b><a href="https://github.com/asottile/blacken-docs">blacken-docs</a></b> (🥉22 ·  ⭐ 300) - Run `black` on python code blocks in documentation files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/blacken-docs) (👨‍💻 13 · 🔀 20 · 📋 39 - 7% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/asottile/blacken-docs
	```
- [PyPi](https://pypi.org/project/blacken-docs) (📥 15K / month · 📦 16 · ⏱️ 19.11.2021):
	```
	pip install blacken-docs
	```
- [Conda](https://anaconda.org/conda-forge/blacken-docs) (📥 19K · ⏱️ 19.11.2021):
	```
	conda install -c conda-forge blacken-docs
	```
</details>
<details><summary><b><a href="https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin">mkdocs-awesome-pages-plugin</a></b> (🥉22 ·  ⭐ 210) - An MkDocs plugin that simplifies configuring page.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin) (👨‍💻 3 · 🔀 20 · 📋 46 - 15% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-awesome-pages-plugin) (📥 36K / month · 📦 60 · ⏱️ 22.11.2021):
	```
	pip install mkdocs-awesome-pages-plugin
	```
</details>
<details><summary><b><a href="https://github.com/orzih/mkdocs-with-pdf">mkdocs-with-pdf</a></b> (🥉20 ·  ⭐ 120) - Generate a single PDF file from MkDocs repository. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/orzih/mkdocs-with-pdf) (👨‍💻 6 · 🔀 22 · 📦 87 · 📋 66 - 43% open · ⏱️ 14.10.2021):

	```
	git clone https://github.com/orzih/mkdocs-with-pdf
	```
- [PyPi](https://pypi.org/project/mkdocs-with-pdf) (📥 6.9K / month · ⏱️ 03.07.2021):
	```
	pip install mkdocs-with-pdf
	```
</details>
<details><summary><b><a href="https://github.com/timothycrosley/portray">portray</a></b> (🥉19 ·  ⭐ 770 · 💤) - Your Project with Great Documentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timothycrosley/portray) (👨‍💻 16 · 🔀 58 · 📋 50 - 42% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/timothycrosley/portray
	```
- [PyPi](https://pypi.org/project/portray) (📥 3.8K / month · 📦 17 · ⏱️ 13.06.2021):
	```
	pip install portray
	```
</details>
<details><summary><b><a href="https://github.com/clayrisser/sphinx-markdown-builder">sphinx-markdown-builder</a></b> (🥉19 ·  ⭐ 120 · 📉) - sphinx builder that outputs markdown files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/clayrisser/sphinx-markdown-builder) (👨‍💻 17 · 🔀 32 · 📦 210 · 📋 34 - 52% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/codejamninja/sphinx-markdown-builder
	```
- [PyPi](https://pypi.org/project/sphinx-markdown-builder) (📥 25K / month · 📦 52 · ⏱️ 08.01.2022):
	```
	pip install sphinx-markdown-builder
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazydocs">lazydocs</a></b> (🥉17 ·  ⭐ 60) - Generate markdown API documentation from Google-style Python docstring... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/lazydocs) (👨‍💻 7 · 🔀 16 · 📦 57 · 📋 11 - 63% open · ⏱️ 20.08.2021):

	```
	git clone https://github.com/ml-tooling/lazydocs
	```
- [PyPi](https://pypi.org/project/lazydocs) (📥 1.3K / month · 📦 12 · ⏱️ 27.07.2021):
	```
	pip install lazydocs
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/pycco-docs/pycco">pycco</a></b> (🥉21 ·  ⭐ 760 · 💀) - Literate-style documentation generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/timvink/mkdocs-print-site-plugin">mkdocs-print-site-plugin</a></b> (🥉19 ·  ⭐ 30) - MkDocs Plugin that adds an additional page that.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zhaoterryy/mkdocs-git-revision-date-plugin">mkdocs-git-revision-date-plugin</a></b> (🥉18 ·  ⭐ 39 · 💀) - MkDocs plugin for setting revision date from git per.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zayd62/mkdocs-versioning">mkdocs-versioning</a></b> (🥉14 ·  ⭐ 39) - A tool that allows for versioning sites built with mkdocs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Debugging Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/inducer/pudb">pudb</a></b> (🥇33 ·  ⭐ 2.3K) - Full-screen console debugger for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pudb) (👨‍💻 81 · 🔀 190 · 📦 2.8K · 📋 290 - 48% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/inducer/pudb
	```
- [PyPi](https://pypi.org/project/pudb) (📥 150K / month · 📦 730 · ⏱️ 07.01.2022):
	```
	pip install pudb
	```
- [Conda](https://anaconda.org/conda-forge/pudb) (📥 110K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge pudb
	```
</details>
<details><summary><b><a href="https://github.com/cool-RR/PySnooper">PySnooper</a></b> (🥇30 ·  ⭐ 15K) - Never use print for debugging again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cool-RR/PySnooper) (👨‍💻 26 · 🔀 920 · 📦 540 · 📋 110 - 15% open · ⏱️ 11.09.2021):

	```
	git clone https://github.com/cool-RR/PySnooper
	```
- [PyPi](https://pypi.org/project/pysnooper) (📥 150K / month · 📦 46 · ⏱️ 11.09.2021):
	```
	pip install pysnooper
	```
- [Conda](https://anaconda.org/conda-forge/pysnooper) (📥 43K · ⏱️ 19.05.2021):
	```
	conda install -c conda-forge pysnooper
	```
</details>
<details><summary><b><a href="https://github.com/gotcha/ipdb">ipdb</a></b> (🥇30 ·  ⭐ 1.5K) - Integration of IPython pdb. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gotcha/ipdb) (👨‍💻 49 · 🔀 130 · 📦 30K · 📋 170 - 33% open · ⏱️ 30.12.2021):

	```
	git clone https://github.com/gotcha/ipdb
	```
- [PyPi](https://pypi.org/project/ipdb) (📥 1.7M / month · 📦 8.7K · ⏱️ 02.06.2021):
	```
	pip install ipdb
	```
- [Conda](https://anaconda.org/conda-forge/ipdb) (📥 230K · ⏱️ 24.06.2021):
	```
	conda install -c conda-forge ipdb
	```
</details>
<details><summary><b><a href="https://github.com/eliben/pyelftools">pyelftools</a></b> (🥇30 ·  ⭐ 1.4K) - Parsing ELF and DWARF in Python. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/eliben/pyelftools) (👨‍💻 81 · 🔀 410 · 📦 2.9K · 📋 180 - 32% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/eliben/pyelftools
	```
- [PyPi](https://pypi.org/project/pyelftools) (📥 650K / month · 📦 520 · ⏱️ 27.10.2020):
	```
	pip install pyelftools
	```
- [Conda](https://anaconda.org/conda-forge/pyelftools) (📥 80K · ⏱️ 27.10.2020):
	```
	conda install -c conda-forge pyelftools
	```
</details>
<details><summary><b><a href="https://github.com/cs01/gdbgui">gdbgui</a></b> (🥈28 ·  ⭐ 8.4K) - Browser-based frontend to gdb (gnu debugger). Add breakpoints, view.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cs01/gdbgui) (👨‍💻 39 · 🔀 480 · 📥 6.6K · 📦 130 · 📋 280 - 42% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/cs01/gdbgui
	```
- [PyPi](https://pypi.org/project/gdbgui) (📥 98K / month · 📦 2 · ⏱️ 06.09.2021):
	```
	pip install gdbgui
	```
</details>
<details><summary><b><a href="https://github.com/agronholm/typeguard">typeguard</a></b> (🥈28 ·  ⭐ 780) - Run-time type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/agronholm/typeguard) (👨‍💻 19 · 🔀 69 · 📋 180 - 16% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/agronholm/typeguard
	```
- [PyPi](https://pypi.org/project/typeguard) (📥 8.5M / month · 📦 300 · ⏱️ 10.12.2021):
	```
	pip install typeguard
	```
- [Conda](https://anaconda.org/conda-forge/typeguard) (📥 69K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge typeguard
	```
</details>
<details><summary><b><a href="https://github.com/pdbpp/pdbpp">pdbpp</a></b> (🥉25 ·  ⭐ 840) - pdb++, a drop-in replacement for pdb (the Python debugger). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pdbpp/pdbpp) (👨‍💻 40 · 🔀 46 · 📦 2.5K · 📋 180 - 35% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/pdbpp/pdbpp
	```
- [PyPi](https://pypi.org/project/pdbpp) (📥 180K / month · 📦 590 · ⏱️ 09.07.2021):
	```
	pip install pdbpp
	```
- [Conda](https://anaconda.org/conda-forge/pdbpp) (📥 67K · ⏱️ 11.07.2021):
	```
	conda install -c conda-forge pdbpp
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-hunter">python-hunter</a></b> (🥉25 ·  ⭐ 660) - Hunter is a flexible code tracing toolkit. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-hunter) (👨‍💻 9 · 🔀 36 · 📦 78 · 📋 87 - 42% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/ionelmc/python-hunter
	```
- [PyPi](https://pypi.org/project/hunter) (📥 9.4K / month · 📦 21 · ⏱️ 15.12.2021):
	```
	pip install hunter
	```
</details>
<details><summary><b><a href="https://github.com/gruns/icecream">icecream</a></b> (🥉24 ·  ⭐ 5.6K) - Never use print() to debug again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gruns/icecream) (👨‍💻 16 · 🔀 110 · 📋 86 - 30% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/gruns/icecream
	```
- [PyPi](https://pypi.org/project/icecream) (📥 110K / month · 📦 30 · ⏱️ 22.06.2021):
	```
	pip install icecream
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/snoop">snoop</a></b> (🥉23 ·  ⭐ 680) - A powerful set of Python debugging tools, based on PySnooper. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/snoop) (👨‍💻 21 · 🔀 24 · 📋 38 - 47% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/alexmojaki/snoop
	```
- [PyPi](https://pypi.org/project/snoop) (📥 16K / month · 📦 12 · ⏱️ 11.11.2021):
	```
	pip install snoop
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/birdseye">Birdseye</a></b> (🥉22 ·  ⭐ 1.4K) - Graphical Python debugger which lets you easily view the values of all.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/birdseye) (👨‍💻 10 · 🔀 70 · 📋 50 - 36% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/alexmojaki/birdseye
	```
- [PyPi](https://pypi.org/project/birdseye) (📥 1.4K / month · 📦 3 · ⏱️ 11.11.2021):
	```
	pip install birdseye
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-manhole">python-manhole</a></b> (🥉20 ·  ⭐ 320) - Debugging manhole for python applications. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-manhole) (👨‍💻 11 · 🔀 17 · 📦 83 · 📋 21 - 28% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/ionelmc/python-manhole
	```
- [PyPi](https://pypi.org/project/manhole) (📥 21K / month · 📦 38 · ⏱️ 08.04.2021):
	```
	pip install manhole
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/lmacken/pyrasite">pyrasite</a></b> (🥉21 ·  ⭐ 2.6K · 💀) - Inject code into running Python processes. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Testing Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python">best-of-web-python - Testing</a></b> ( ⭐ 1.4K)  - Testing libraries & tools for python web frameworks.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.html">unittest</a></b>  - Unittest is a test framework included in the Python standard library.

<details><summary><b><a href="https://github.com/pytest-dev/pytest">pytest</a></b> (🥇47 ·  ⭐ 8.1K · 📈) - The pytest framework makes it easy to write small tests, yet.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest) (👨‍💻 760 · 🔀 1.9K · 📦 420K · 📋 4.8K - 15% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/pytest-dev/pytest
	```
- [PyPi](https://pypi.org/project/pytest) (📥 29M / month · 📦 80K · ⏱️ 07.12.2021):
	```
	pip install pytest
	```
- [Conda](https://anaconda.org/conda-forge/pytest) (📥 11M · ⏱️ 07.01.2022):
	```
	conda install -c conda-forge pytest
	```
</details>
<details><summary><b><a href="https://github.com/robotframework/robotframework">robotframework</a></b> (🥇41 ·  ⭐ 6.6K) - Generic automation framework for acceptance testing and RPA. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/robotframework/robotframework) (👨‍💻 150 · 🔀 1.8K · 📥 510 · 📦 4.8K · 📋 3.7K - 5% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/robotframework/robotframework
	```
- [PyPi](https://pypi.org/project/robotframework) (📥 750K / month · 📦 1K · ⏱️ 15.12.2021):
	```
	pip install robotframework
	```
- [Conda](https://anaconda.org/conda-forge/robotframework) (📥 70K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge robotframework
	```
</details>
<details><summary><b><a href="https://github.com/HypothesisWorks/hypothesis">hypothesis</a></b> (🥇39 ·  ⭐ 5.6K) - Hypothesis is a powerful, flexible, and easy to use library for.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/HypothesisWorks/hypothesis) (👨‍💻 260 · 🔀 480 · 📦 11K · 📋 1.2K - 4% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/HypothesisWorks/hypothesis
	```
- [PyPi](https://pypi.org/project/hypothesis) (📥 1.8M / month · 📦 1.9K · ⏱️ 08.01.2022):
	```
	pip install hypothesis
	```
- [Conda](https://anaconda.org/conda-forge/hypothesis) (📥 5.1M · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge hypothesis
	```
</details>
<details><summary><b><a href="https://github.com/tox-dev/tox">tox</a></b> (🥇37 ·  ⭐ 2.6K) - Command line driven CI frontend and development task automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/tox) (👨‍💻 250 · 🔀 390 · 📦 53K · 📋 1.4K - 9% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/tox-dev/tox
	```
- [PyPi](https://pypi.org/project/tox) (📥 3.5M / month · 📦 20K · ⏱️ 04.01.2022):
	```
	pip install tox
	```
- [Conda](https://anaconda.org/conda-forge/tox) (📥 400K · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge tox
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-cov">pytest-cov</a></b> (🥇36 ·  ⭐ 1.2K) - Coverage plugin for pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-cov) (👨‍💻 74 · 🔀 160 · 📦 110K · 📋 310 - 35% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/pytest-dev/pytest-cov
	```
- [PyPi](https://pypi.org/project/pytest-cov) (📥 9.2M / month · 📦 28K · ⏱️ 04.10.2021):
	```
	pip install pytest-cov
	```
- [Conda](https://anaconda.org/conda-forge/pytest-cov) (📥 4.4M · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge pytest-cov
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-xdist">pytest-xdist</a></b> (🥈35 ·  ⭐ 830) - pytest plugin for distributed testing and loop-on-failures.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-xdist) (👨‍💻 77 · 🔀 160 · 📋 460 - 44% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/pytest-dev/pytest-xdist
	```
- [PyPi](https://pypi.org/project/pytest-xdist) (📥 4.2M / month · 📦 4.5K · ⏱️ 10.12.2021):
	```
	pip install pytest-xdist
	```
- [Conda](https://anaconda.org/conda-forge/pytest-xdist) (📥 2.2M · ⏱️ 10.12.2021):
	```
	conda install -c conda-forge pytest-xdist
	```
</details>
<details><summary><b><a href="https://github.com/asweigart/pyautogui">pyautogui</a></b> (🥈33 ·  ⭐ 6.1K) - A cross-platform GUI automation Python module for human beings. Used.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/asweigart/pyautogui) (👨‍💻 51 · 🔀 800 · 📦 12K · 📋 540 - 63% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/asweigart/pyautogui
	```
- [PyPi](https://pypi.org/project/pyautogui) (📥 470K / month · 📦 540 · ⏱️ 07.07.2021):
	```
	pip install pyautogui
	```
- [Conda](https://anaconda.org/conda-forge/pyautogui) (📥 140K · ⏱️ 11.11.2021):
	```
	conda install -c conda-forge pyautogui
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-mock">pytest-mock</a></b> (🥈33 ·  ⭐ 1.3K) - Thin-wrapper around the mock package for easier use with pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-mock) (👨‍💻 54 · 🔀 100 · 📦 22K · 📋 110 - 12% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/pytest-dev/pytest-mock
	```
- [PyPi](https://pypi.org/project/pytest-mock) (📥 4.4M / month · 📦 4.2K · ⏱️ 06.05.2021):
	```
	pip install pytest-mock
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mock) (📥 1.3M · ⏱️ 07.05.2021):
	```
	conda install -c conda-forge pytest-mock
	```
</details>
<details><summary><b><a href="https://github.com/lk-geimfari/mimesis">mimesis</a></b> (🥈32 ·  ⭐ 3.5K) - Mimesis is a high-performance fake data generator for Python, which.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lk-geimfari/mimesis) (👨‍💻 110 · 🔀 280 · 📥 190 · 📋 300 - 0% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/lk-geimfari/mimesis
	```
- [PyPi](https://pypi.org/project/mimesis) (📥 88K / month · 📦 57 · ⏱️ 11.12.2021):
	```
	pip install mimesis
	```
</details>
<details><summary><b><a href="https://github.com/spulec/freezegun">freezegun</a></b> (🥈32 ·  ⭐ 3.1K) - Let your Python tests travel through time. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spulec/freezegun) (👨‍💻 97 · 🔀 220 · 📋 260 - 34% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/spulec/freezegun
	```
- [PyPi](https://pypi.org/project/freezegun) (📥 2.9M / month · 📦 4.4K · ⏱️ 20.01.2021):
	```
	pip install freezegun
	```
- [Conda](https://anaconda.org/conda-forge/freezegun) (📥 300K · ⏱️ 20.01.2021):
	```
	conda install -c conda-forge freezegun
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/playwright-python">playwright-python</a></b> (🥈31 ·  ⭐ 5.7K) - Python version of the Playwright testing and automation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/microsoft/playwright-python) (👨‍💻 22 · 🔀 500 · 📦 680 · 📋 540 - 4% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/microsoft/playwright-python
	```
- [PyPi](https://pypi.org/project/playwright) (📥 180K / month · 📦 35 · ⏱️ 02.12.2021):
	```
	pip install playwright
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-asyncio">pytest-asyncio</a></b> (🥈31 ·  ⭐ 850) - Pytest support for asyncio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-asyncio) (👨‍💻 34 · 🔀 95 · 📋 170 - 24% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/pytest-dev/pytest-asyncio
	```
- [PyPi](https://pypi.org/project/pytest-asyncio) (📥 1.9M / month · 📦 1.8K · ⏱️ 13.01.2022):
	```
	pip install pytest-asyncio
	```
- [Conda](https://anaconda.org/conda-forge/pytest-asyncio) (📥 750K · ⏱️ 18.10.2021):
	```
	conda install -c conda-forge pytest-asyncio
	```
</details>
<details><summary><b><a href="https://github.com/TheKevJames/coveralls-python">coveralls-python</a></b> (🥈31 ·  ⭐ 460) - Show coverage stats online via coveralls.io. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TheKevJames/coveralls-python) (👨‍💻 63 · 🔀 180 · 📦 20K · 📋 150 - 3% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/TheKevJames/coveralls-python
	```
- [PyPi](https://pypi.org/project/coveralls) (📥 420K / month · 📦 9.2K · ⏱️ 11.11.2021):
	```
	pip install coveralls
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥈30 ·  ⭐ 2.7K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 120 · 🔀 330 · 📋 510 - 30% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 1.5M / month · 📦 2.1K · ⏱️ 05.05.2018):
	```
	pip install factory_boy
	```
- [Conda](https://anaconda.org/conda-forge/factory_boy) (📥 89K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/hamcrest/PyHamcrest">PyHamcrest</a></b> (🥈30 ·  ⭐ 600) - Hamcrest matchers for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/hamcrest/PyHamcrest) (👨‍💻 37 · 🔀 91 · 📋 69 - 27% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/hamcrest/PyHamcrest
	```
- [PyPi](https://pypi.org/project/pyhamcrest) (📥 810K / month · 📦 1.8K · ⏱️ 12.12.2021):
	```
	pip install pyhamcrest
	```
- [Conda](https://anaconda.org/conda-forge/pyhamcrest) (📥 380K · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge pyhamcrest
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-html">pytest-html</a></b> (🥈30 ·  ⭐ 460 · 💤) - Plugin for generating HTML reports for pytest results. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-html) (👨‍💻 43 · 🔀 180 · 📦 15K · 📋 280 - 34% open · ⏱️ 23.01.2021):

	```
	git clone https://github.com/pytest-dev/pytest-html
	```
- [PyPi](https://pypi.org/project/pytest-html) (📥 1.4M / month · 📦 660 · ⏱️ 13.12.2020):
	```
	pip install pytest-html
	```
- [Conda](https://anaconda.org/conda-forge/pytest-html) (📥 200K · ⏱️ 13.12.2020):
	```
	conda install -c conda-forge pytest-html
	```
</details>
<details><summary><b><a href="https://github.com/nose-devs/nose2">nose2</a></b> (🥉29 ·  ⭐ 700) - The successor to nose, based on unittest2. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nose-devs/nose2) (👨‍💻 71 · 🔀 130 · 📦 4.4K · 📋 260 - 21% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/nose-devs/nose2
	```
- [PyPi](https://pypi.org/project/nose2) (📥 370K / month · 📦 1.1K · ⏱️ 27.01.2021):
	```
	pip install nose2
	```
- [Conda](https://anaconda.org/conda-forge/nose2) (📥 42K · ⏱️ 02.02.2020):
	```
	conda install -c conda-forge nose2
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-bdd">pytest-bdd</a></b> (🥉28 ·  ⭐ 940) - BDD library for the py.test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-bdd) (👨‍💻 45 · 🔀 160 · 📋 290 - 52% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/pytest-dev/pytest-bdd
	```
- [PyPi](https://pypi.org/project/pytest-bdd) (📥 200K / month · 📦 170 · ⏱️ 25.10.2021):
	```
	pip install pytest-bdd
	```
- [Conda](https://anaconda.org/conda-forge/pytest-bdd) (📥 42K · ⏱️ 03.02.2020):
	```
	conda install -c conda-forge pytest-bdd
	```
</details>
<details><summary><b><a href="https://github.com/theacodes/nox">nox</a></b> (🥉28 ·  ⭐ 690) - Flexible test automation for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/theacodes/nox) (👨‍💻 65 · 🔀 110 · 📋 260 - 11% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/theacodes/nox
	```
- [PyPi](https://pypi.org/project/nox) (📥 630K / month · 📦 140 · ⏱️ 07.01.2022):
	```
	pip install nox
	```
- [Conda](https://anaconda.org/conda-forge/nox) (📥 45K · ⏱️ 03.12.2021):
	```
	conda install -c conda-forge nox
	```
</details>
<details><summary><b><a href="https://github.com/datadriventests/ddt">ddt</a></b> (🥉28 ·  ⭐ 400) - Data-Driven Tests for Python Unittest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datadriventests/ddt) (👨‍💻 36 · 🔀 100 · 📦 3.9K · 📋 53 - 28% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/datadriventests/ddt
	```
- [PyPi](https://pypi.org/project/ddt) (📥 220K / month · 📦 1.3K · ⏱️ 04.10.2021):
	```
	pip install ddt
	```
- [Conda](https://anaconda.org/conda-forge/ddt) (📥 66K · ⏱️ 15.05.2020):
	```
	conda install -c conda-forge ddt
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-testinfra">pytest-testinfra</a></b> (🥉27 ·  ⭐ 2K) - Testinfra test your infrastructures. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-testinfra) (👨‍💻 110 · 🔀 280 · 📋 320 - 36% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/pytest-dev/pytest-testinfra
	```
- [PyPi](https://pypi.org/project/pytest-testinfra) (📥 120K / month · 📦 4 · ⏱️ 07.12.2021):
	```
	pip install pytest-testinfra
	```
</details>
<details><summary><b><a href="https://github.com/CleanCut/green">green</a></b> (🥉27 ·  ⭐ 720) - Green is a clean, colorful, fast python test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CleanCut/green) (👨‍💻 37 · 🔀 74 · 📦 630 · 📋 170 - 1% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/CleanCut/green
	```
- [PyPi](https://pypi.org/project/green) (📥 12K / month · 📦 210 · ⏱️ 12.01.2022):
	```
	pip install green
	```
- [Conda](https://anaconda.org/conda-forge/green) (📥 91K · ⏱️ 12.11.2020):
	```
	conda install -c conda-forge green
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/pytest-benchmark">pytest-benchmark</a></b> (🥉26 ·  ⭐ 840 · 💤) - py.test fixture for benchmarking code. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ionelmc/pytest-benchmark) (👨‍💻 34 · 🔀 92 · 📦 2.5K · 📋 160 - 50% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ionelmc/pytest-benchmark
	```
- [PyPi](https://pypi.org/project/pytest-benchmark) (📥 300K / month · 📦 560 · ⏱️ 17.04.2021):
	```
	pip install pytest-benchmark
	```
- [Conda](https://anaconda.org/conda-forge/pytest-benchmark) (📥 1.1M · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge pytest-benchmark
	```
</details>
<details><summary><b><a href="https://github.com/airspeed-velocity/asv">asv</a></b> (🥉26 ·  ⭐ 620) - Airspeed Velocity: A simple Python benchmarking tool with web-based reporting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/airspeed-velocity/asv) (👨‍💻 55 · 🔀 130 · 📦 220 · 📋 420 - 27% open · ⏱️ 15.08.2021):

	```
	git clone https://github.com/airspeed-velocity/asv
	```
- [PyPi](https://pypi.org/project/asv) (📥 27K / month · 📦 63 · ⏱️ 16.05.2020):
	```
	pip install asv
	```
- [Conda](https://anaconda.org/conda-forge/asv) (📥 560K · ⏱️ 08.11.2021):
	```
	conda install -c conda-forge asv
	```
</details>
<details><summary><b><a href="https://github.com/dbader/pytest-mypy">pytest-mypy</a></b> (🥉26 ·  ⭐ 200 · 💤) - Mypy static type checker plugin for Pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dbader/pytest-mypy) (👨‍💻 15 · 🔀 33 · 📦 1.4K · 📋 47 - 19% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/dbader/pytest-mypy
	```
- [PyPi](https://pypi.org/project/pytest-mypy) (📥 490K / month · 📦 280 · ⏱️ 21.03.2021):
	```
	pip install pytest-mypy
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mypy) (📥 19K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge pytest-mypy
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-randomly">pytest-randomly</a></b> (🥉25 ·  ⭐ 390) - Pytest plugin to randomly order tests and control random.seed. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-randomly) (👨‍💻 16 · 🔀 22 · 📋 48 - 12% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/pytest-dev/pytest-randomly
	```
- [PyPi](https://pypi.org/project/pytest-randomly) (📥 330K / month · 📦 180 · ⏱️ 10.01.2022):
	```
	pip install pytest-randomly
	```
</details>
<details><summary><b><a href="https://github.com/Erotemic/xdoctest">xdoctest</a></b> (🥉22 ·  ⭐ 130) - A rewrite of Pythons builtin doctest module (with pytest plugin.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Erotemic/xdoctest) (👨‍💻 7 · 🔀 7 · 📦 2K · 📋 37 - 45% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/Erotemic/xdoctest
	```
- [PyPi](https://pypi.org/project/xdoctest) (📥 96K / month · 📦 62 · ⏱️ 06.10.2021):
	```
	pip install xdoctest
	```
</details>
<details><summary><b><a href="https://github.com/tarpas/pytest-testmon">pytest-testmon</a></b> (🥉21 ·  ⭐ 500) - Selects tests affected by changed files. Continous.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tarpas/pytest-testmon) (👨‍💻 16 · 🔀 29 · 📋 120 - 24% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/tarpas/pytest-testmon
	```
- [PyPi](https://pypi.org/project/pytest-testmon) (📥 93K / month · 📦 54 · ⏱️ 22.10.2021):
	```
	pip install pytest-testmon
	```
- [Conda](https://anaconda.org/conda-forge/pytest-testmon) (📥 33K · ⏱️ 03.08.2019):
	```
	conda install -c conda-forge pytest-testmon
	```
</details>
<details><summary><b><a href="https://github.com/TvoroG/pytest-lazy-fixture">pytest-lazy-fixture</a></b> (🥉20 ·  ⭐ 230 · 📉) - It helps to use fixtures in pytest.mark.parametrize. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TvoroG/pytest-lazy-fixture) (👨‍💻 8 · 🔀 15 · 📦 520 · 📋 35 - 42% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/tvorog/pytest-lazy-fixture
	```
- [PyPi](https://pypi.org/project/pytest-lazy-fixture) (📥 230K / month · 📦 54 · ⏱️ 01.02.2020):
	```
	pip install pytest-lazy-fixture
	```
- [Conda](https://anaconda.org/conda-forge/pytest-lazy-fixture) (📥 310K · ⏱️ 01.02.2020):
	```
	conda install -c conda-forge pytest-lazy-fixture
	```
</details>
<details><summary><b><a href="https://github.com/avast/pytest-docker">pytest-docker</a></b> (🥉18 ·  ⭐ 260 · 💤) - Docker-based integration tests. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/avast/pytest-docker) (👨‍💻 11 · 🔀 42 · 📥 83 · 📋 33 - 51% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/avast/pytest-docker
	```
- [PyPi](https://pypi.org/project/pytest-docker) (📥 53K / month · 📦 23 · ⏱️ 14.06.2021):
	```
	pip install pytest-docker
	```
</details>
<details><summary><b><a href="https://github.com/man-group/pytest-plugins">pytest-plugins</a></b> (🥉16 ·  ⭐ 400) - A grab-bag of nifty pytest plugins. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/man-group/pytest-plugins) (👨‍💻 57 · 🔀 60 · 📋 100 - 43% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/man-group/pytest-plugins
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/nose-devs/nose">nose</a></b> (🥈33 ·  ⭐ 1.3K · 💀) - nose is nicer testing for python. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1%2B">❗️LGPL-2.1+</a></code>
- <b><a href="https://github.com/Teemu/pytest-sugar">pytest-sugar</a></b> (🥉28 ·  ⭐ 820 · 💀) - a plugin for py.test that changes the default look and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/xiaocong/uiautomator">uiautomator</a></b> (🥉27 ·  ⭐ 1.8K · 💀) - Python wrapper of Android uiautomator test tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/joeyespo/pytest-watch">pytest-watch</a></b> (🥉26 ·  ⭐ 620 · 💀) - Local continuous test runner with pytest and watchdog. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nestorsalceda/mamba">Mamba Test Runner</a></b> (🥉25 ·  ⭐ 480 · 💀) - The definitive testing tool for Python. Born under the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sixpack/sixpack">sixpack</a></b> (🥉22 ·  ⭐ 1.7K · 💀) - Sixpack is a language-agnostic a/b-testing framework. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/gabrielcnr/pytest-datadir">pytest-datadir</a></b> (🥉20 ·  ⭐ 150 · 💀) - pytest plugin for manipulating test data directories and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/emirozer/fake2db">fake2db</a></b> (🥉19 ·  ⭐ 2.1K · 💀) - create custom test databases that are populated with fake data. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/ActivisionGameScience/assertpy">assertpy</a></b> (🥉19 ·  ⭐ 250 · 💀) - Simple assertion library for unit testing in python with a fluent.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pytest-dev/pytest-play">pytest-play</a></b> (🥉16 ·  ⭐ 65 · 💀) - pytest plugin that let you automate actions and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Code Packaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://packaging.python.org/overview/">Python.org Packaging</a></b>  - An Overview of Packaging for Python.

<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">pyinstaller</a></b> (🥇37 ·  ⭐ 8.7K · 📈) - Freeze (package) Python programs into stand-alone.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 420 · 🔀 1.8K · 📥 720K · 📋 4.4K - 7% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
- [PyPi](https://pypi.org/project/pyinstaller) (📥 580K / month · 📦 130 · ⏱️ 12.01.2022):
	```
	pip install pyinstaller
	```
- [Conda](https://anaconda.org/conda-forge/pyinstaller) (📥 290K · ⏱️ 13.01.2022):
	```
	conda install -c conda-forge pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/pypa/packaging">packaging</a></b> (🥇36 ·  ⭐ 360) - Core utilities for Python packages. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pypa/packaging) (👨‍💻 72 · 🔀 180 · 📥 210 · 📦 300K · 📋 230 - 28% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/pypa/packaging
	```
- [PyPi](https://pypi.org/project/packaging) (📥 84M / month · 📦 17K · ⏱️ 18.11.2021):
	```
	pip install packaging
	```
- [Conda](https://anaconda.org/conda-forge/packaging) (📥 12M · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge packaging
	```
</details>
<details><summary><b><a href="https://github.com/Nuitka/Nuitka">Nuitka</a></b> (🥈32 ·  ⭐ 6.3K) - Nuitka is a Python compiler written in Python. Its fully compatible.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Nuitka/Nuitka) (👨‍💻 110 · 🔀 360 · 📋 1.2K - 15% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/Nuitka/Nuitka
	```
- [PyPi](https://pypi.org/project/nuitka) (📥 22K / month · 📦 35 · ⏱️ 11.01.2022):
	```
	pip install nuitka
	```
- [Conda](https://anaconda.org/conda-forge/nuitka) (📥 330K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge nuitka
	```
</details>
<details><summary><b><a href="https://github.com/pantsbuild/pex">pex</a></b> (🥈30 ·  ⭐ 2K) - A library and tool for generating .pex (Python EXecutable) files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pantsbuild/pex) (👨‍💻 100 · 🔀 210 · 📥 560K · 📋 780 - 18% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/pantsbuild/pex
	```
- [PyPi](https://pypi.org/project/pex) (📥 160K / month · 📦 130 · ⏱️ 11.01.2022):
	```
	pip install pex
	```
</details>
<details><summary><b><a href="https://github.com/marcelotduarte/cx_Freeze">cx_Freeze</a></b> (🥈29 ·  ⭐ 850) - Create standalone executables from Python scripts, with the same.. <code><a href="http://bit.ly/35wkF7y">Python-2.0</a></code></summary>

- [GitHub](https://github.com/marcelotduarte/cx_Freeze) (👨‍💻 93 · 🔀 170 · 📋 720 - 8% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/marcelotduarte/cx_Freeze
	```
- [PyPi](https://pypi.org/project/cx_freeze) (📥 48K / month · 📦 150 · ⏱️ 16.12.2017):
	```
	pip install cx_freeze
	```
- [Conda](https://anaconda.org/conda-forge/cx_freeze) (📥 110K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge cx_freeze
	```
</details>
<details><summary><b><a href="https://github.com/beeware/briefcase">briefcase</a></b> (🥈27 ·  ⭐ 1.3K) - Tools to support converting a Python project into a standalone.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/beeware/briefcase) (👨‍💻 88 · 🔀 220 · 📋 370 - 30% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/beeware/briefcase
	```
- [PyPi](https://pypi.org/project/briefcase) (📥 3.3K / month · 📦 16 · ⏱️ 06.03.2021):
	```
	pip install briefcase
	```
</details>
<details><summary><b><a href="https://github.com/py2exe/py2exe">py2exe</a></b> (🥉26 ·  ⭐ 350) - A distutils extension to create standalone Windows programs from Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py2exe/py2exe) (👨‍💻 14 · 🔀 44 · 📥 7.2K · 📦 1.4K · 📋 96 - 5% open · ⏱️ 16.11.2021):

	```
	git clone https://github.com/py2exe/py2exe
	```
- [PyPi](https://pypi.org/project/py2exe) (📥 21K / month · 📦 180 · ⏱️ 15.12.2021):
	```
	pip install py2exe
	```
</details>
<details><summary><b><a href="https://github.com/ronaldoussoren/py2app">py2app</a></b> (🥉26 ·  ⭐ 170) - py2app is a Python setuptools command which will allow you to make.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ronaldoussoren/py2app) (👨‍💻 27 · 🔀 18 · 📦 3.9K · 📋 380 - 28% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/ronaldoussoren/py2app
	```
- [PyPi](https://pypi.org/project/py2app) (📥 13K / month · 📦 830 · ⏱️ 27.09.2021):
	```
	pip install py2app
	```
</details>
<details><summary><b><a href="https://github.com/indygreg/PyOxidizer">PyOxidizer</a></b> (🥉24 ·  ⭐ 3.4K) - A modern Python application packaging and distribution tool. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/indygreg/PyOxidizer) (👨‍💻 37 · 🔀 140 · 📥 1.5K · 📋 420 - 60% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/indygreg/PyOxidizer
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉24 ·  ⭐ 1.3K) - shiv is a command line utility for building fully self contained Python.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 34 · 🔀 75 · 📥 160 · 📋 100 - 32% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/linkedin/shiv
	```
- [PyPi](https://pypi.org/project/shiv) (📥 4.9K / month · 📦 12 · ⏱️ 18.11.2021):
	```
	pip install shiv
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/pynsist">pynsist</a></b> (🥉23 ·  ⭐ 740) - Build Windows installers for Python applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/takluyver/pynsist) (👨‍💻 29 · 🔀 100 · 📋 160 - 15% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/takluyver/pynsist
	```
- [PyPi](https://pypi.org/project/pynsist) (📥 1.6K / month · 📦 47 · ⏱️ 28.03.2021):
	```
	pip install pynsist
	```
</details>
<details><summary><b><a href="https://github.com/conda/constructor">constructor</a></b> (🥉23 ·  ⭐ 340) - tool for creating installers from conda packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/constructor) (👨‍💻 49 · 🔀 130 · 📥 220 · 📦 12 · 📋 260 - 22% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/conda/constructor
	```
- [Conda](https://anaconda.org/anaconda/constructor) (📥 5.1K · ⏱️ 01.04.2021):
	```
	conda install -c anaconda constructor
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/xar">xar</a></b> (🥉20 ·  ⭐ 1.5K) - executable archive format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/facebookincubator/xar) (👨‍💻 29 · 🔀 45 · 📦 17 · 📋 29 - 27% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/facebookincubator/xar
	```
- [PyPi](https://pypi.org/project/xar) (📥 140 / month · ⏱️ 02.12.2020):
	```
	pip install xar
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/google/subpar">subpar</a></b> (🥉14 ·  ⭐ 510 · 💀) - Subpar is a utility for creating self-contained python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jamesabel/pyship">pyship</a></b> (🥉9 ·  ⭐ 15 · 💤) - pyship - ship Python desktop apps to end users. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Build Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/setuptools">setuptools</a></b> (🥇45 ·  ⭐ 1.5K · 📈) - Official project repository for the Setuptools build system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools) (👨‍💻 480 · 🔀 810 · 📥 110 · 📦 130K · 📋 1.9K - 24% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/pypa/setuptools
	```
- [PyPi](https://pypi.org/project/setuptools) (📥 180M / month · 📦 36K · ⏱️ 08.01.2022):
	```
	pip install setuptools
	```
- [Conda](https://anaconda.org/conda-forge/setuptools) (📥 31M · ⏱️ 09.01.2022):
	```
	conda install -c conda-forge setuptools
	```
</details>
<details><summary><b><a href="https://github.com/buildbot/buildbot">buildbot</a></b> (🥇35 ·  ⭐ 4.8K) - Python-based continuous integration testing framework; your pull.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/buildbot/buildbot) (👨‍💻 800 · 🔀 1.6K · 📥 19K · 📦 260 · 📋 1.4K - 45% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/buildbot/buildbot
	```
- [PyPi](https://pypi.org/project/buildbot) (📥 58K / month · 📦 460 · ⏱️ 16.10.2021):
	```
	pip install buildbot
	```
- [Conda](https://anaconda.org/conda-forge/buildbot) (📥 48K · ⏱️ 16.10.2021):
	```
	conda install -c conda-forge buildbot
	```
</details>
<details><summary><b><a href="https://github.com/pypa/twine">twine</a></b> (🥇35 ·  ⭐ 1.2K) - Utilities for interacting with PyPI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pypa/twine) (👨‍💻 100 · 🔀 250 · 📦 52K · 📋 390 - 9% open · ⏱️ 31.12.2021):

	```
	git clone https://github.com/pypa/twine
	```
- [PyPi](https://pypi.org/project/twine) (📥 2.2M / month · 📦 12K · ⏱️ 07.12.2021):
	```
	pip install twine
	```
- [Conda](https://anaconda.org/conda-forge/twine) (📥 390K · ⏱️ 07.12.2021):
	```
	conda install -c conda-forge twine
	```
</details>
<details><summary><b><a href="https://github.com/pypa/wheel">wheel</a></b> (🥇35 ·  ⭐ 290) - The official binary distribution format for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/wheel) (👨‍💻 64 · 🔀 100 · 📋 330 - 8% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/pypa/wheel
	```
- [PyPi](https://pypi.org/project/wheel) (📥 97M / month · 📦 35K · ⏱️ 22.12.2021):
	```
	pip install wheel
	```
- [Conda](https://anaconda.org/conda-forge/wheel) (📥 25M · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge wheel
	```
</details>
<details><summary><b><a href="https://github.com/pyinvoke/invoke">invoke</a></b> (🥈32 ·  ⭐ 3.5K) - Pythonic task management & command execution. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pyinvoke/invoke) (👨‍💻 56 · 🔀 300 · 📦 10K · 📋 700 - 48% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/pyinvoke/invoke
	```
- [PyPi](https://pypi.org/project/invoke) (📥 2.1M / month · 📦 2.6K · ⏱️ 15.12.2021):
	```
	pip install invoke
	```
- [Conda](https://anaconda.org/conda-forge/invoke) (📥 490K · ⏱️ 10.07.2021):
	```
	conda install -c conda-forge invoke
	```
</details>
<details><summary><b><a href="https://github.com/SCons/scons">scons</a></b> (🥈32 ·  ⭐ 1.3K) - SCons - a software construction tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SCons/scons) (👨‍💻 140 · 🔀 250 · 📥 390 · 📋 3.3K - 19% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/SCons/scons
	```
- [PyPi](https://pypi.org/project/scons) (📥 180K / month · 📦 37 · ⏱️ 17.12.2019):
	```
	pip install scons
	```
- [Conda](https://anaconda.org/conda-forge/scons) (📥 250K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge scons
	```
</details>
<details><summary><b><a href="https://github.com/pydoit/doit">doit</a></b> (🥈32 ·  ⭐ 1.3K) - task management & automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydoit/doit) (👨‍💻 62 · 🔀 140 · 📦 850 · 📋 260 - 24% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/pydoit/doit
	```
- [PyPi](https://pypi.org/project/doit) (📥 140K / month · 📦 280 · ⏱️ 12.01.2022):
	```
	pip install doit
	```
- [Conda](https://anaconda.org/conda-forge/doit) (📥 72K · ⏱️ 12.12.2021):
	```
	conda install -c conda-forge doit
	```
</details>
<details><summary><b><a href="https://github.com/pypa/setuptools_scm">setuptools_scm</a></b> (🥈32 ·  ⭐ 530) - the blessed package to manage your versions by scm tags. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools_scm) (👨‍💻 98 · 🔀 150 · 📋 370 - 21% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/pypa/setuptools_scm
	```
- [PyPi](https://pypi.org/project/setuptools_scm) (📥 11M / month · 📦 380 · ⏱️ 09.08.2018):
	```
	pip install setuptools_scm
	```
- [Conda](https://anaconda.org/conda-forge/setuptools_scm) (📥 850K · ⏱️ 11.09.2021):
	```
	conda install -c conda-forge setuptools_scm
	```
</details>
<details><summary><b><a href="https://github.com/pypa/flit">flit</a></b> (🥉31 ·  ⭐ 1.6K) - Simplified packaging of Python modules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pypa/flit) (👨‍💻 50 · 🔀 87 · 📋 290 - 29% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/takluyver/flit
	```
- [PyPi](https://pypi.org/project/flit) (📥 260K / month · 📦 200 · ⏱️ 27.12.2021):
	```
	pip install flit
	```
- [Conda](https://anaconda.org/conda-forge/flit) (📥 100K · ⏱️ 28.12.2021):
	```
	conda install -c conda-forge flit
	```
</details>
<details><summary><b><a href="https://github.com/pybuilder/pybuilder">pybuilder</a></b> (🥉30 ·  ⭐ 1.4K) - Software build automation tool for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pybuilder/pybuilder) (👨‍💻 36 · 🔀 240 · 📋 500 - 18% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/pybuilder/pybuilder
	```
- [PyPi](https://pypi.org/project/pybuilder) (📥 16K / month · 📦 60 · ⏱️ 12.01.2022):
	```
	pip install pybuilder
	```
</details>
<details><summary><b><a href="https://github.com/paver/paver">paver</a></b> (🥉24 ·  ⭐ 450 · 💤) - Python-based project scripting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/paver/paver) (👨‍💻 45 · 🔀 78 · 📋 130 - 28% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/paver/paver
	```
- [PyPi](https://pypi.org/project/paver) (📥 37K / month · 📦 960 · ⏱️ 31.12.2017):
	```
	pip install paver
	```
- [Conda](https://anaconda.org/conda-forge/paver) (📥 24K · ⏱️ 24.07.2018):
	```
	conda install -c conda-forge paver
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/universal-build">universal-build</a></b> (🥉16 ·  ⭐ 14) - Universal build utilities for containerized build pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/universal-build) (👨‍💻 4 · 🔀 5 · 📥 16 · 📦 7 · ⏱️ 17.11.2021):

	```
	git clone https://github.com/ml-tooling/universal-build
	```
- [PyPi](https://pypi.org/project/universal-build) (📥 370 / month · 📦 5 · ⏱️ 12.12.2020):
	```
	pip install universal-build
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/buildout/buildout">buildout</a></b> (🥉31 ·  ⭐ 530) - Buildout is a deployment automation tool written in and extended.. <code><a href="https://tldrlegal.com/search?q=ZPL-2.1">❗️ZPL-2.1</a></code>
- <b><a href="https://github.com/rags/pynt">pynt</a></b> (🥉17 ·  ⭐ 150 · 💀) - A pynt of Python build. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## System Monitoring & Profiling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/giampaolo/psutil">psutil</a></b> (🥇43 ·  ⭐ 8K) - Cross-platform lib for process and system monitoring in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/giampaolo/psutil) (👨‍💻 170 · 🔀 1.2K · 📦 130K · 📋 1.5K - 13% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/giampaolo/psutil
	```
- [PyPi](https://pypi.org/project/psutil) (📥 32M / month · 📦 15K · ⏱️ 29.12.2021):
	```
	pip install psutil
	```
- [Conda](https://anaconda.org/conda-forge/psutil) (📥 9.6M · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge psutil
	```
</details>
<details><summary><b><a href="https://github.com/nicolargo/glances">Glances</a></b> (🥇36 ·  ⭐ 20K) - Glances an Eye on your system. A top/htop alternative for.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/nicolargo/glances) (👨‍💻 150 · 🔀 1.3K · 📥 710 · 📦 370 · 📋 1.4K - 14% open · ⏱️ 02.01.2022):

	```
	git clone https://github.com/nicolargo/glances
	```
- [PyPi](https://pypi.org/project/glances) (📥 140K / month · 📦 50 · ⏱️ 22.11.2021):
	```
	pip install glances
	```
- [Conda](https://anaconda.org/conda-forge/glances) (📥 150K · ⏱️ 20.11.2021):
	```
	conda install -c conda-forge glances
	```
</details>
<details><summary><b><a href="https://github.com/joerick/pyinstrument">pyinstrument</a></b> (🥈31 ·  ⭐ 4.1K) - Call stack profiler for Python. Shows you why your code is slow!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joerick/pyinstrument) (👨‍💻 38 · 🔀 160 · 📦 480 · 📋 95 - 15% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/joerick/pyinstrument
	```
- [PyPi](https://pypi.org/project/pyinstrument) (📥 210K / month · 📦 97 · ⏱️ 14.11.2021):
	```
	pip install pyinstrument
	```
- [Conda](https://anaconda.org/conda-forge/pyinstrument) (📥 93K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge pyinstrument
	```
</details>
<details><summary><b><a href="https://github.com/benfred/py-spy">py-spy</a></b> (🥈30 ·  ⭐ 7.8K) - Sampling profiler for Python programs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/py-spy) (👨‍💻 29 · 🔀 280 · 📥 7.3K · 📋 240 - 29% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/benfred/py-spy
	```
- [PyPi](https://pypi.org/project/py-spy) (📥 480K / month · 📦 35 · ⏱️ 13.11.2021):
	```
	pip install py-spy
	```
- [Cargo](https://crates.io/crates/py-spy) (📥 26K / month · ⏱️ 13.11.2021):
	```
	cargo install py-spy
	```
</details>
<details><summary><b><a href="https://github.com/plasma-umass/scalene">Scalene</a></b> (🥈30 ·  ⭐ 5.1K) - Scalene: a high-performance, high-precision CPU, GPU, and memory.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/plasma-umass/scalene) (👨‍💻 24 · 🔀 170 · 📦 77 · 📋 170 - 22% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/plasma-umass/scalene
	```
- [PyPi](https://pypi.org/project/scalene) (📥 4.3K / month · 📦 3 · ⏱️ 12.01.2022):
	```
	pip install scalene
	```
</details>
<details><summary><b><a href="https://github.com/python-diamond/Diamond">Diamond</a></b> (🥈29 ·  ⭐ 1.6K) - Diamond is a python daemon that collects system metrics and publishes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-diamond/Diamond) (👨‍💻 360 · 🔀 590 · 📦 72 · 📋 360 - 63% open · ⏱️ 31.12.2021):

	```
	git clone https://github.com/python-diamond/Diamond
	```
- [PyPi](https://pypi.org/project/diamond) (📥 47K / month · 📦 32 · ⏱️ 25.11.2016):
	```
	pip install diamond
	```
</details>
<details><summary><b><a href="https://github.com/pyutils/line_profiler">line_profiler</a></b> (🥈28 ·  ⭐ 3.5K) - Line-by-line profiling for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyutils/line_profiler) (👨‍💻 27 · 🔀 250 · 📋 51 - 56% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/pyutils/line_profiler
	```
- [PyPi](https://pypi.org/project/line_profiler) (📥 110K / month · 📦 350 · ⏱️ 20.12.2017):
	```
	pip install line_profiler
	```
- [Conda](https://anaconda.org/conda-forge/line_profiler) (📥 220K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge line_profiler
	```
</details>
<details><summary><b><a href="https://github.com/pythonprofilers/memory_profiler">memory-profiler</a></b> (🥈28 ·  ⭐ 3.3K) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pythonprofilers/memory_profiler) (👨‍💻 91 · 🔀 330 · 📋 220 - 51% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/pythonprofilers/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📥 420K / month · 📦 270 · ⏱️ 16.08.2018):
	```
	pip install memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/pympler/pympler">pympler</a></b> (🥈28 ·  ⭐ 850) - Development tool to measure, monitor and analyze the memory behavior.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pympler/pympler) (👨‍💻 29 · 🔀 75 · 📋 90 - 44% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/pympler/pympler
	```
- [PyPi](https://pypi.org/project/pympler) (📥 990K / month · 📦 290 · ⏱️ 22.12.2021):
	```
	pip install pympler
	```
- [Conda](https://anaconda.org/conda-forge/pympler) (📥 180K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge pympler
	```
</details>
<details><summary><b><a href="https://github.com/aristocratos/bpytop">Bpytop</a></b> (🥉27 ·  ⭐ 8.2K) - Linux/OSX/FreeBSD resource monitor. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aristocratos/bpytop) (👨‍💻 35 · 🔀 320 · 📋 280 - 21% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/aristocratos/bpytop
	```
- [PyPi](https://pypi.org/project/bpytop) (📥 9.9K / month · 📦 1 · ⏱️ 22.12.2021):
	```
	pip install bpytop
	```
</details>
<details><summary><b><a href="https://github.com/sumerc/yappi">Yappi</a></b> (🥉27 ·  ⭐ 790) - Yet Another Python Profiler, but this time thread&coroutine&greenlet aware. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sumerc/yappi) (👨‍💻 27 · 🔀 53 · 📦 510 · 📋 55 - 30% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/sumerc/yappi
	```
- [PyPi](https://pypi.org/project/yappi) (📥 1.1M / month · 📦 340 · ⏱️ 15.12.2021):
	```
	pip install yappi
	```
- [Conda](https://anaconda.org/conda-forge/yappi) (📥 96K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge yappi
	```
</details>
<details><summary><b><a href="https://github.com/nvdv/vprof">vprof</a></b> (🥉23 ·  ⭐ 3.8K · 💤) - Visual profiler for Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/nvdv/vprof) (👨‍💻 17 · 🔀 170 · 📦 87 · 📋 82 - 31% open · ⏱️ 20.02.2021):

	```
	git clone https://github.com/nvdv/vprof
	```
- [PyPi](https://pypi.org/project/vprof) (📥 3.3K / month · 📦 16 · ⏱️ 29.02.2020):
	```
	pip install vprof
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/heartrate">heartrate</a></b> (🥉19 ·  ⭐ 1.4K) - Simple real time visualisation of the execution of a Python program. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/heartrate) (👨‍💻 3 · 🔀 120 · 📦 33 · 📋 7 - 57% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/alexmojaki/heartrate
	```
- [PyPi](https://pypi.org/project/heartrate) (📥 800 / month · 📦 3 · ⏱️ 13.11.2021):
	```
	pip install heartrate
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/pyheat">pyheat</a></b> (🥉17 ·  ⭐ 700) - pprofile + matplotlib = Python program profiled as an awesome heatmap!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/pyheat) (👨‍💻 5 · 🔀 38 · 📦 33 · 📋 13 - 30% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/csurfer/pyheat
	```
- [PyPi](https://pypi.org/project/py-heat) (📥 1.8K / month · 📦 6 · ⏱️ 06.12.2018):
	```
	pip install py-heat
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/what-studio/profiling">Profiling</a></b> (🥉22 ·  ⭐ 3K · 💀) - Was an interactive continuous Python profiler. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/fabianp/memory_profiler">memory_profiler</a></b> (🥉22 ·  ⭐ 67 · 💀) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/agermanidis/livepython">livepython</a></b> (🥉12 ·  ⭐ 2.5K · 💀) - Visually trace Python code in real-time. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## AST Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python/typed_ast">typed_ast</a></b> (🥇30 ·  ⭐ 200) - Modified fork of CPythons ast module that parses `# type:` comments. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python/typed_ast) (👨‍💻 24 · 🔀 51 · 📋 89 - 6% open · ⏱️ 01.01.2022):

	```
	git clone https://github.com/python/typed_ast
	```
- [PyPi](https://pypi.org/project/typed_ast) (📥 10M / month · 📦 5.5K · ⏱️ 03.12.2021):
	```
	pip install typed_ast
	```
</details>
<details><summary><b><a href="https://github.com/berkerpeksag/astor">astor</a></b> (🥈28 ·  ⭐ 630) - Python AST read/write. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/berkerpeksag/astor) (👨‍💻 31 · 🔀 84 · 📋 110 - 31% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/berkerpeksag/astor
	```
- [PyPi](https://pypi.org/project/astor) (📥 5M / month · 📦 2.1K · ⏱️ 10.12.2019):
	```
	pip install astor
	```
- [Conda](https://anaconda.org/conda-forge/astor) (📥 1.4M · ⏱️ 01.07.2020):
	```
	conda install -c conda-forge astor
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/gast">gast</a></b> (🥉27 ·  ⭐ 120 · 📉) - Python AST that abstracts the underlying Python version. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/gast) (👨‍💻 10 · 🔀 25 · 📦 74K · 📋 26 - 3% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/serge-sans-paille/gast
	```
- [PyPi](https://pypi.org/project/gast) (📥 10M / month · 📦 1.9K · ⏱️ 13.11.2021):
	```
	pip install gast
	```
- [Conda](https://anaconda.org/conda-forge/gast) (📥 1.4M · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge gast
	```
</details>
<details><summary><b><a href="https://github.com/newville/asteval">asteval</a></b> (🥉24 ·  ⭐ 130) - minimalistic evaluator of python expression using ast module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/newville/asteval) (👨‍💻 19 · 🔀 32 · 📦 710 · 📋 53 - 13% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/newville/asteval
	```
- [PyPi](https://pypi.org/project/asteval) (📥 110K / month · 📦 160 · ⏱️ 22.06.2021):
	```
	pip install asteval
	```
- [Conda](https://anaconda.org/conda-forge/asteval) (📥 150K · ⏱️ 27.02.2021):
	```
	conda install -c conda-forge asteval
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/simonpercivall/astunparse">astunparse</a></b> (🥈28 ·  ⭐ 180 · 💀) - An AST unparser for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pre-commit/pre-commit">pre-commit</a></b> (🥇36 ·  ⭐ 7.2K) - A framework for managing and maintaining multi-language pre-commit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pre-commit/pre-commit) (👨‍💻 130 · 🔀 520 · 📥 25K · 📋 1.3K - 1% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/pre-commit/pre-commit
	```
- [PyPi](https://pypi.org/project/pre-commit) (📥 3.2M / month · 📦 2.7K · ⏱️ 30.11.2021):
	```
	pip install pre-commit
	```
- [Conda](https://anaconda.org/conda-forge/pre-commit) (📥 930K · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge pre-commit
	```
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-python-dev/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-python-dev/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-python-dev/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-python-dev/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-python-dev/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
