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

This curated list contains 250 awesome open-source projects with a total of 600K stars grouped into 15 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-python-dev/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-python-dev/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-python-dev/edit/main/projects.yaml). Contributions are very welcome!

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

<details><summary><b><a href="https://github.com/python/mypy">mypy</a></b> (🥇36 ·  ⭐ 11K) - Optional static typing for Python 3 and 2 (PEP 484). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python/mypy) (👨‍💻 480 · 🔀 1.8K · 📦 37K · 📋 6.5K - 27% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/python/mypy
	```
- [PyPi](https://pypi.org/project/mypy) (📥 7.4M / month · 📦 6.1K · ⏱️ 22.06.2021):
	```
	pip install mypy
	```
- [Conda](https://anaconda.org/conda-forge/mypy) (📥 1M · ⏱️ 23.06.2021):
	```
	conda install -c conda-forge mypy
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8">flake8</a></b> (🥇36 ·  ⭐ 1.3K) - Flake8 is a wrapper around these tools: PyFlakes; pycodestyle; Ned.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/flake8) (👨‍💻 160 · 🔀 180 · 📦 180K · 📋 1.3K - 2% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/PyCQA/flake8
	```
- [PyPi](https://pypi.org/project/flake8) (📥 12M / month · 📦 71K · ⏱️ 08.05.2021):
	```
	pip install flake8
	```
- [Conda](https://anaconda.org/conda-forge/flake8) (📥 2.6M · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge flake8
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pycodestyle">pycodestyle</a></b> (🥇34 ·  ⭐ 4.3K) - Simple Python style checker in one Python file. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/pycodestyle) (👨‍💻 120 · 🔀 600 · 📦 150K · 📋 650 - 17% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/PyCQA/pycodestyle
	```
- [PyPi](https://pypi.org/project/pycodestyle) (📥 17M / month · 📦 21K · ⏱️ 14.03.2021):
	```
	pip install pycodestyle
	```
- [Conda](https://anaconda.org/conda-forge/pycodestyle) (📥 2.8M · ⏱️ 15.03.2021):
	```
	conda install -c conda-forge pycodestyle
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pyflakes">pyflakes</a></b> (🥇32 ·  ⭐ 1K) - A simple program which checks Python source files for errors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pyflakes) (👨‍💻 77 · 🔀 140 · 📦 92K · 📋 420 - 18% open · ⏱️ 28.05.2021):

	```
	git clone https://github.com/PyCQA/pyflakes
	```
- [PyPi](https://pypi.org/project/pyflakes) (📥 13M / month · 📦 26K · ⏱️ 24.03.2021):
	```
	pip install pyflakes
	```
- [Conda](https://anaconda.org/conda-forge/pyflakes) (📥 2.6M · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge pyflakes
	```
</details>
<details><summary><b><a href="https://github.com/davidhalter/parso">parso</a></b> (🥇32 ·  ⭐ 420) - A Python Parser. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/parso) (👨‍💻 40 · 🔀 68 · 📦 130K · 📋 100 - 8% open · ⏱️ 30.05.2021):

	```
	git clone https://github.com/davidhalter/parso
	```
- [PyPi](https://pypi.org/project/parso) (📥 14M / month · 📦 11K · ⏱️ 30.03.2021):
	```
	pip install parso
	```
- [Conda](https://anaconda.org/conda-forge/parso) (📥 4.3M · ⏱️ 31.03.2021):
	```
	conda install -c conda-forge parso
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint">pylint</a></b> (🥈31 ·  ⭐ 3.4K · 📉) - It's not just a linter that annoys you!. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/pylint) (👨‍💻 390 · 🔀 720 · 📋 3.5K - 20% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/PyCQA/pylint
	```
- [PyPi](https://pypi.org/project/pylint) (📥 13M / month · 📦 38K · ⏱️ 01.07.2021):
	```
	pip install pylint
	```
- [Conda](https://anaconda.org/conda-forge/pylint) (📥 2M · ⏱️ 01.07.2021):
	```
	conda install -c conda-forge pylint
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pydocstyle">pydocstyle</a></b> (🥈30 ·  ⭐ 780) - docstring style checker. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pydocstyle) (👨‍💻 72 · 🔀 150 · 📥 51 · 📦 17K · 📋 270 - 27% open · ⏱️ 17.05.2021):

	```
	git clone https://github.com/PyCQA/pydocstyle
	```
- [PyPi](https://pypi.org/project/pydocstyle) (📥 2.1M / month · 📦 3.9K · ⏱️ 17.05.2021):
	```
	pip install pydocstyle
	```
- [Conda](https://anaconda.org/conda-forge/pydocstyle) (📥 380K · ⏱️ 18.05.2021):
	```
	conda install -c conda-forge pydocstyle
	```
</details>
<details><summary><b><a href="https://github.com/facebook/pyre-check">pyre-check</a></b> (🥈29 ·  ⭐ 5.4K) - Performant type-checking for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/pyre-check) (👨‍💻 160 · 🔀 320 · 📋 260 - 24% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/facebook/pyre-check
	```
- [PyPi](https://pypi.org/project/pyre-check) (📥 21K / month · 📦 46 · ⏱️ 14.05.2021):
	```
	pip install pyre-check
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/wemake-python-styleguide">wemake-python-styleguide</a></b> (🥈29 ·  ⭐ 1.5K) - The strictest and most opinionated python linter ever!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-python-styleguide) (👨‍💻 140 · 🔀 280 · 📦 410 · 📋 950 - 8% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/wemake-services/wemake-python-styleguide
	```
- [PyPi](https://pypi.org/project/wemake-python-styleguide) (📥 75K / month · 📦 14 · ⏱️ 21.06.2021):
	```
	pip install wemake-python-styleguide
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-bugbear">flake8-bugbear</a></b> (🥈29 ·  ⭐ 560) - A plugin for Flake8 finding likely bugs and design problems.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-bugbear) (👨‍💻 37 · 🔀 42 · 📦 4K · 📋 92 - 42% open · ⏱️ 01.04.2021):

	```
	git clone https://github.com/PyCQA/flake8-bugbear
	```
- [PyPi](https://pypi.org/project/flake8-bugbear) (📥 810K / month · 📦 1K · ⏱️ 01.04.2021):
	```
	pip install flake8-bugbear
	```
- [Conda](https://anaconda.org/conda-forge/flake8-bugbear) (📥 330K · ⏱️ 02.04.2021):
	```
	conda install -c conda-forge flake8-bugbear
	```
</details>
<details><summary><b><a href="https://github.com/openstack/hacking">hacking</a></b> (🥈29 ·  ⭐ 220) - OpenStack Hacking Style Checks. Mirror of code maintained at.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/openstack/hacking) (👨‍💻 180 · 🔀 66 · ⏱️ 05.06.2021):

	```
	git clone https://github.com/openstack/hacking
	```
- [PyPi](https://pypi.org/project/hacking) (📥 170K / month · 📦 8.7K · ⏱️ 21.04.2021):
	```
	pip install hacking
	```
</details>
<details><summary><b><a href="https://github.com/google/pytype">pytype</a></b> (🥈28 ·  ⭐ 3.3K) - A static type analyzer for Python code. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/pytype) (👨‍💻 63 · 🔀 190 · 📋 430 - 23% open · ⏱️ 24.06.2021):

	```
	git clone https://github.com/google/pytype
	```
- [PyPi](https://pypi.org/project/pytype) (📥 110K / month · 📦 88 · ⏱️ 17.06.2021):
	```
	pip install pytype
	```
- [Conda](https://anaconda.org/conda-forge/pytype) (📥 51K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge pytype
	```
</details>
<details><summary><b><a href="https://github.com/coala/coala">coala</a></b> (🥈27 ·  ⭐ 3.2K) - coala provides a unified command-line interface for linting and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/coala/coala) (👨‍💻 480 · 🔀 1.4K · 📥 140 · 📦 10 · 📋 3.2K - 26% open · ⏱️ 16.05.2021):

	```
	git clone https://github.com/coala/coala
	```
- [PyPi](https://pypi.org/project/coala-bears) (📥 4.1K / month · 📦 210 · ⏱️ 10.11.2017):
	```
	pip install coala-bears
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint-django">pylint-django</a></b> (🥈27 ·  ⭐ 470) - Pylint plugin for improving code analysis for when.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/pylint-django) (👨‍💻 58 · 🔀 100 · 📥 180 · 📦 14K · 📋 180 - 15% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/PyCQA/pylint-django
	```
- [PyPi](https://pypi.org/project/pylint-django) (📥 620K / month · 📦 2.2K · ⏱️ 09.04.2021):
	```
	pip install pylint-django
	```
- [Conda](https://anaconda.org/conda-forge/pylint-django) (📥 81K · ⏱️ 12.01.2021):
	```
	conda install -c conda-forge pylint-django
	```
</details>
<details><summary><b><a href="https://github.com/terrencepreilly/darglint">darglint</a></b> (🥈26 ·  ⭐ 320) - A python documentation linter which checks that the docstring description.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/terrencepreilly/darglint) (👨‍💻 21 · 🔀 26 · 📦 560 · 📋 130 - 28% open · ⏱️ 04.04.2021):

	```
	git clone https://github.com/terrencepreilly/darglint
	```
- [PyPi](https://pypi.org/project/darglint) (📥 180K / month · 📦 20 · ⏱️ 22.02.2021):
	```
	pip install darglint
	```
- [Conda](https://anaconda.org/conda-forge/darglint) (📥 14K · ⏱️ 05.04.2021):
	```
	conda install -c conda-forge darglint
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/pyright">pyright</a></b> (🥈25 ·  ⭐ 6.9K) - Static type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/pyright) (👨‍💻 57 · 🔀 340 · 📦 90 · 📋 1.7K - 0% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/Microsoft/pyright
	```
- [NPM](https://www.npmjs.com/package/pyright) (📥 93K / month · 📦 4 · ⏱️ 01.07.2021):
	```
	npm install pyright
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/mypy-protobuf">mypy-protobuf</a></b> (🥈25 ·  ⭐ 360 · 📈) - open source tools to generate mypy stubs from protobufs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/mypy-protobuf) (👨‍💻 27 · 🔀 56 · 📦 250 · 📋 73 - 19% open · ⏱️ 24.06.2021):

	```
	git clone https://github.com/dropbox/mypy-protobuf
	```
- [PyPi](https://pypi.org/project/mypy-protobuf) (📥 460K / month · 📦 24 · ⏱️ 24.06.2021):
	```
	pip install mypy-protobuf
	```
</details>
<details><summary><b><a href="https://github.com/mgedmin/check-manifest">check-manifest</a></b> (🥈25 ·  ⭐ 230) - Tool to check the completeness of MANIFEST.in for Python packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mgedmin/check-manifest) (👨‍💻 19 · 🔀 30 · 📦 5.7K · 📋 86 - 17% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/mgedmin/check-manifest
	```
- [PyPi](https://pypi.org/project/check-manifest) (📥 190K / month · 📦 1.8K · ⏱️ 04.01.2021):
	```
	pip install check-manifest
	```
- [Conda](https://anaconda.org/conda-forge/check-manifest) (📥 29K · ⏱️ 04.01.2021):
	```
	conda install -c conda-forge check-manifest
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-isort">flake8-isort</a></b> (🥈25 ·  ⭐ 110 · 💤) - flake8 plugin that integrates isort. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-isort) (👨‍💻 28 · 🔀 35 · 📦 3K · 📋 46 - 19% open · ⏱️ 11.08.2020):

	```
	git clone https://github.com/gforcada/flake8-isort
	```
- [PyPi](https://pypi.org/project/flake8-isort) (📥 420K / month · 📦 930 · ⏱️ 11.08.2020):
	```
	pip install flake8-isort
	```
- [Conda](https://anaconda.org/conda-forge/flake8-isort) (📥 12K · ⏱️ 09.06.2021):
	```
	conda install -c conda-forge flake8-isort
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-import-order">flake8-import-order</a></b> (🥉24 ·  ⭐ 240 · 💤) - Flake8 plugin that checks import order against.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-import-order) (👨‍💻 40 · 🔀 61 · 📋 96 - 11% open · ⏱️ 04.08.2020):

	```
	git clone https://github.com/PyCQA/flake8-import-order
	```
- [PyPi](https://pypi.org/project/flake8-import-order) (📥 360K / month · 📦 1.9K · ⏱️ 04.03.2019):
	```
	pip install flake8-import-order
	```
- [Conda](https://anaconda.org/conda-forge/flake8-import-order) (📥 190K · ⏱️ 06.03.2019):
	```
	conda install -c conda-forge flake8-import-order
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/flake8-comprehensions">flake8-comprehensions</a></b> (🥉23 ·  ⭐ 280) - A flake8 plugin to help you write better.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adamchainz/flake8-comprehensions) (👨‍💻 10 · 🔀 13 · 📋 37 - 18% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/adamchainz/flake8-comprehensions
	```
- [PyPi](https://pypi.org/project/flake8-comprehensions) (📥 530K / month · 📦 710 · ⏱️ 10.05.2021):
	```
	pip install flake8-comprehensions
	```
- [Conda](https://anaconda.org/conda-forge/flake8-comprehensions) (📥 360K · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge flake8-comprehensions
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/flake8-eradicate">flake8-eradicate</a></b> (🥉23 ·  ⭐ 190) - Flake8 plugin to find commented out or dead code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/wemake-services/flake8-eradicate) (👨‍💻 11 · 🔀 7 · 📋 26 - 3% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/wemake-services/flake8-eradicate
	```
- [PyPi](https://pypi.org/project/flake8-eradicate) (📥 200K / month · 📦 72 · ⏱️ 22.06.2021):
	```
	pip install flake8-eradicate
	```
</details>
<details><summary><b><a href="https://github.com/predictive-analytics-lab/data-science-types">data-science-types</a></b> (🥉23 ·  ⭐ 180) - Mypy stubs, i.e., type information, for numpy, pandas.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/predictive-analytics-lab/data-science-types) (👨‍💻 44 · 🔀 57 · 📦 87 · 📋 62 - 62% open · ⏱️ 16.02.2021):

	```
	git clone https://github.com/predictive-analytics-lab/data-science-types
	```
- [PyPi](https://pypi.org/project/data-science-types) (📥 23K / month · ⏱️ 16.02.2021):
	```
	pip install data-science-types
	```
</details>
<details><summary><b><a href="https://github.com/peterjc/flake8-black">flake8-black</a></b> (🥉22 ·  ⭐ 90) - flake8 plugin to run black for checking Python coding style. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/peterjc/flake8-black) (👨‍💻 4 · 🔀 7 · 📦 880 · 📋 18 - 22% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/peterjc/flake8-black
	```
- [PyPi](https://pypi.org/project/flake8-black) (📥 190K / month · 📦 36 · ⏱️ 25.07.2020):
	```
	pip install flake8-black
	```
- [Conda](https://anaconda.org/conda-forge/flake8-black) (📥 110K · ⏱️ 25.07.2020):
	```
	conda install -c conda-forge flake8-black
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-builtins">flake8-builtins</a></b> (🥉21 ·  ⭐ 67) - Check for python builtins being used as variables or.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-builtins) (👨‍💻 14 · 🔀 16 · 📦 2.2K · 📋 33 - 6% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/gforcada/flake8-builtins
	```
- [PyPi](https://pypi.org/project/flake8-builtins) (📥 340K / month · 📦 510 · ⏱️ 14.05.2020):
	```
	pip install flake8-builtins
	```
- [Conda](https://anaconda.org/conda-forge/flake8-builtins) (📥 120K · ⏱️ 18.05.2020):
	```
	conda install -c conda-forge flake8-builtins
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/Fixit">Fixit</a></b> (🥉20 ·  ⭐ 240) - Fixit is a Python Lint Framework based on LibCST. It comes with useful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Instagram/Fixit) (👨‍💻 25 · 🔀 37 · 📦 7 · 📋 59 - 57% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/Instagram/Fixit
	```
- [PyPi](https://pypi.org/project/fixit) (📥 2.2K / month · ⏱️ 11.12.2020):
	```
	pip install fixit
	```
</details>
<details><summary><b><a href="https://github.com/jschaf/pylint-flask">pylint-flask</a></b> (🥉20 ·  ⭐ 58) - A Pylint plugin to analyze Flask applications. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jschaf/pylint-flask) (👨‍💻 7 · 🔀 9 · 📦 5.1K · 📋 9 - 44% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/jschaf/pylint-flask
	```
- [PyPi](https://pypi.org/project/pylint-flask) (📥 180K / month · 📦 710 · ⏱️ 30.01.2019):
	```
	pip install pylint-flask
	```
- [Conda](https://anaconda.org/conda-forge/pylint-flask) (📥 50K · ⏱️ 02.02.2019):
	```
	conda install -c conda-forge pylint-flask
	```
</details>
<details><summary><b><a href="https://github.com/andreoliwa/nitpick">nitpick</a></b> (🥉19 ·  ⭐ 160) - Enforce the same settings on multiple projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andreoliwa/nitpick) (👨‍💻 10 · 🔀 9 · 📥 3 · 📋 84 - 36% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/andreoliwa/nitpick
	```
- [PyPi](https://pypi.org/project/nitpick) (📥 9.6K / month · ⏱️ 16.03.2021):
	```
	pip install nitpick
	```
</details>
<details><summary><b><a href="https://github.com/tylerwince/flake8-bandit">flake8-bandit</a></b> (🥉19 ·  ⭐ 62 · 💤) - Automated security testing using bandit and flake8. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tylerwince/flake8-bandit) (👨‍💻 5 · 🔀 15 · 📋 11 - 27% open · ⏱️ 29.08.2020):

	```
	git clone https://github.com/tylerwince/flake8-bandit
	```
- [PyPi](https://pypi.org/project/flake8-bandit) (📥 210K / month · 📦 160 · ⏱️ 08.10.2019):
	```
	pip install flake8-bandit
	```
</details>
<details><summary><b><a href="https://github.com/life4/flakehell">flakehell</a></b> (🥉18 ·  ⭐ 220) - Flake8 wrapper to make it nice, legacy-friendly, configurable. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/life4/flakehell) (👨‍💻 15 · 🔀 33 · 📥 50 · ⏱️ 11.01.2021):

	```
	git clone https://github.com/life4/flakehell
	```
- [PyPi](https://pypi.org/project/flakehell) (📥 42K / month · ⏱️ 11.01.2021):
	```
	pip install flakehell
	```
</details>
<details><summary><b><a href="https://github.com/deppen8/pandas-vet">pandas-vet</a></b> (🥉18 ·  ⭐ 93) - A plugin for Flake8 that checks pandas code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deppen8/pandas-vet) (👨‍💻 10 · 🔀 14 · 📥 33 · 📦 44 · 📋 49 - 42% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/deppen8/pandas-vet
	```
- [PyPi](https://pypi.org/project/pandas-vet) (📥 4.9K / month · ⏱️ 01.02.2020):
	```
	pip install pandas-vet
	```
- [Conda](https://anaconda.org/conda-forge/pandas-vet) (📥 6.7K · ⏱️ 01.02.2020):
	```
	conda install -c conda-forge pandas-vet
	```
</details>
<details><summary><b><a href="https://github.com/beartype/beartype">beartype</a></b> (🥉17 ·  ⭐ 300) - Unbearably fast O(1) runtime type-checking in pure Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beartype/beartype) (👨‍💻 5 · 🔀 7 · 📋 28 - 14% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/beartype/beartype
	```
- [PyPi](https://pypi.org/project/beartype) (📥 9.4K / month · ⏱️ 30.06.2021):
	```
	pip install beartype
	```
- [Conda](https://anaconda.org/conda-forge/beartype) (📥 4.7K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge beartype
	```
</details>
<details><summary><b><a href="https://github.com/hchasestevens/bellybutton">bellybutton</a></b> (🥉16 ·  ⭐ 220 · 💤) - Custom Python linting through AST expressions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hchasestevens/bellybutton) (👨‍💻 4 · 🔀 8 · 📦 4 · 📋 13 - 53% open · ⏱️ 27.11.2020):

	```
	git clone https://github.com/hchasestevens/bellybutton
	```
- [PyPi](https://pypi.org/project/bellybutton) (📥 5.5K / month · ⏱️ 27.11.2020):
	```
	pip install bellybutton
	```
</details>
<details><summary><b><a href="https://github.com/lyft/linty_fresh">linty_fresh</a></b> (🥉14 ·  ⭐ 180 · 💤) - Surface lint errors during code review. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code>mypy</code></summary>

- [GitHub](https://github.com/lyft/linty_fresh) (👨‍💻 17 · 🔀 21 · 📋 9 - 88% open · ⏱️ 30.11.2020):

	```
	git clone https://github.com/lyft/linty_fresh
	```
- [PyPi](https://pypi.org/project/linty-fresh) (📥 54 / month · ⏱️ 12.12.2018):
	```
	pip install linty-fresh
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/pep8-naming">pep8-naming</a></b> (🥈27 ·  ⭐ 310) - Naming Convention checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/zheller/flake8-quotes">flake8-quotes</a></b> (🥈25 ·  ⭐ 130 · 💀) - Flake8 extension for checking quotes in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/klen/pylama">pylama</a></b> (🥉24 ·  ⭐ 780 · 💀) - Code audit tool for python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/PyCQA/flake8-commas">flake8-commas</a></b> (🥉22 ·  ⭐ 120 · 💀) - Flake8 extension for enforcing trailing commas in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ambv/flake8-mypy">flake8-mypy</a></b> (🥉20 ·  ⭐ 100 · 💀) - A plugin for flake8 integrating Mypy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/justinabrahms/imhotep">imhotep</a></b> (🥉18 ·  ⭐ 220 · 💀) - A static-analysis bot for Github. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bndr/pycycle">pycycle</a></b> (🥉17 ·  ⭐ 290 · 💀) - Tool for pinpointing circular imports in Python. Find cyclic imports.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/cemsbr/yala">yala</a></b> (🥉17 ·  ⭐ 11) - Yet Another Linter Aggregator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Code Formatters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/psf/black">black</a></b> (🥇33 ·  ⭐ 21K) - The uncompromising Python code formatter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/black) (👨‍💻 260 · 🔀 1.4K · 📥 14K · 📦 65K · 📋 1.6K - 18% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/psf/black
	```
- [PyPi](https://pypi.org/project/black) (📥 7.8M / month · 📦 6.2K · ⏱️ 10.06.2021):
	```
	pip install black
	```
- [Conda](https://anaconda.org/conda-forge/black) (📥 1.7M · ⏱️ 01.06.2021):
	```
	conda install -c conda-forge black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/isort">isort</a></b> (🥇33 ·  ⭐ 4K) - A Python utility / library to sort imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/isort) (👨‍💻 240 · 🔀 410 · 📦 180K · 📋 970 - 2% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/PyCQA/isort
	```
- [PyPi](https://pypi.org/project/isort) (📥 18M / month · 📦 24K · ⏱️ 21.06.2021):
	```
	pip install isort
	```
- [Conda](https://anaconda.org/conda-forge/isort) (📥 2M · ⏱️ 21.06.2021):
	```
	conda install -c conda-forge isort
	```
</details>
<details><summary><b><a href="https://github.com/hhatto/autopep8">autopep8</a></b> (🥇33 ·  ⭐ 3.8K · 📉) - A tool that automatically formats Python code to conform to the PEP.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/autopep8) (👨‍💻 50 · 🔀 240 · 📦 81K · 📋 420 - 20% open · ⏱️ 30.04.2021):

	```
	git clone https://github.com/hhatto/autopep8
	```
- [PyPi](https://pypi.org/project/autopep8) (📥 2.2M / month · 📦 10K · ⏱️ 30.04.2021):
	```
	pip install autopep8
	```
- [Conda](https://anaconda.org/conda-forge/autopep8) (📥 480K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge autopep8
	```
</details>
<details><summary><b><a href="https://github.com/google/yapf">yapf</a></b> (🥉30 ·  ⭐ 12K) - A formatter for Python files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/yapf) (👨‍💻 130 · 🔀 790 · 📦 21K · 📋 690 - 45% open · ⏱️ 30.05.2021):

	```
	git clone https://github.com/google/yapf
	```
- [PyPi](https://pypi.org/project/yapf) (📥 1.8M / month · 📦 3.4K · ⏱️ 23.04.2020):
	```
	pip install yapf
	```
- [Conda](https://anaconda.org/conda-forge/yapf) (📥 690K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge yapf
	```
</details>
<details><summary><b><a href="https://github.com/myint/docformatter">docformatter</a></b> (🥉24 ·  ⭐ 220 · 💤) - Formats docstrings to follow PEP 257. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/myint/docformatter) (👨‍💻 15 · 🔀 31 · 📦 640 · 📋 49 - 55% open · ⏱️ 27.12.2020):

	```
	git clone https://github.com/myint/docformatter
	```
- [PyPi](https://pypi.org/project/docformatter) (📥 63K / month · 📦 110 · ⏱️ 27.12.2020):
	```
	pip install docformatter
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/myint/pyformat">pyformat</a></b> (🥉18 ·  ⭐ 83 · 💀) - Formats Python code to follow a consistent style. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
</details>
<br>

## Code Refactoring

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/davidhalter/jedi">jedi</a></b> (🥇35 ·  ⭐ 4.9K) - Awesome autocompletion, static analysis and refactoring library for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/jedi) (👨‍💻 140 · 🔀 440 · 📦 140K · 📋 1.2K - 2% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/davidhalter/jedi
	```
- [PyPi](https://pypi.org/project/jedi) (📥 14M / month · 📦 16K · ⏱️ 25.12.2020):
	```
	pip install jedi
	```
- [Conda](https://anaconda.org/conda-forge/jedi) (📥 5.3M · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge jedi
	```
</details>
<details><summary><b><a href="https://github.com/python-rope/rope">rope</a></b> (🥇30 ·  ⭐ 1.1K) - a python refactoring library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-rope/rope) (👨‍💻 63 · 🔀 140 · 📦 30K · 📋 190 - 37% open · ⏱️ 20.05.2021):

	```
	git clone https://github.com/python-rope/rope
	```
- [PyPi](https://pypi.org/project/rope) (📥 450K / month · 📦 2.9K · ⏱️ 07.10.2020):
	```
	pip install rope
	```
- [Conda](https://anaconda.org/conda-forge/rope) (📥 540K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge rope
	```
</details>
<details><summary><b><a href="https://github.com/jendrikseipp/vulture">vulture</a></b> (🥈26 ·  ⭐ 1.8K) - Find dead Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jendrikseipp/vulture) (👨‍💻 28 · 🔀 81 · 📦 990 · 📋 150 - 8% open · ⏱️ 04.06.2021):

	```
	git clone https://github.com/jendrikseipp/vulture
	```
- [PyPi](https://pypi.org/project/vulture) (📥 150K / month · 📦 360 · ⏱️ 16.01.2021):
	```
	pip install vulture
	```
- [Conda](https://anaconda.org/conda-forge/vulture) (📥 45K · ⏱️ 11.08.2020):
	```
	conda install -c conda-forge vulture
	```
</details>
<details><summary><b><a href="https://github.com/myint/autoflake">autoflake</a></b> (🥈26 ·  ⭐ 400 · 💤) - Removes unused imports and unused variables as reported by pyflakes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/myint/autoflake) (👨‍💻 17 · 🔀 45 · 📦 2.4K · 📋 66 - 50% open · ⏱️ 27.12.2020):

	```
	git clone https://github.com/myint/autoflake
	```
- [PyPi](https://pypi.org/project/autoflake) (📥 740K / month · 📦 580 · ⏱️ 04.08.2019):
	```
	pip install autoflake
	```
- [Conda](https://anaconda.org/conda-forge/autoflake) (📥 130K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge autoflake
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/MonkeyType">MonkeyType</a></b> (🥈23 ·  ⭐ 3.4K) - A system for Python that generates static type annotations by.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Instagram/MonkeyType) (👨‍💻 37 · 🔀 130 · 📦 120 · 📋 150 - 25% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/Instagram/MonkeyType
	```
- [PyPi](https://pypi.org/project/monkeytype) (📥 41K / month · 📦 34 · ⏱️ 21.05.2021):
	```
	pip install monkeytype
	```
- [Conda](https://anaconda.org/conda-forge/monkeytype) (📥 33K · ⏱️ 22.05.2021):
	```
	conda install -c conda-forge monkeytype
	```
</details>
<details><summary><b><a href="https://github.com/asottile/pyupgrade">pyupgrade</a></b> (🥈23 ·  ⭐ 1K) - A tool (and pre-commit hook) to automatically upgrade syntax for newer.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/pyupgrade) (👨‍💻 18 · 🔀 68 · 📋 200 - 7% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/asottile/pyupgrade
	```
- [PyPi](https://pypi.org/project/pyupgrade) (📥 140K / month · 📦 10 · ⏱️ 11.06.2021):
	```
	pip install pyupgrade
	```
- [Conda](https://anaconda.org/conda-forge/pyupgrade) (📥 230K · ⏱️ 11.06.2021):
	```
	conda install -c conda-forge pyupgrade
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/Bowler">Bowler</a></b> (🥉22 ·  ⭐ 1.3K) - Safe code refactoring for modern Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/Bowler) (👨‍💻 26 · 🔀 85 · 📋 80 - 57% open · ⏱️ 21.02.2021):

	```
	git clone https://github.com/facebookincubator/Bowler
	```
- [PyPi](https://pypi.org/project/bowler) (📥 32K / month · 📦 10 · ⏱️ 17.09.2020):
	```
	pip install bowler
	```
- [Conda](https://anaconda.org/conda-forge/bowler) (📥 9.9K · ⏱️ 12.06.2019):
	```
	conda install -c conda-forge bowler
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/pyannotate">pyannotate</a></b> (🥉20 ·  ⭐ 1.2K) - Auto-generate PEP-484 annotations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/pyannotate) (👨‍💻 16 · 🔀 46 · 📦 62 · 📋 59 - 44% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/dropbox/pyannotate
	```
- [PyPi](https://pypi.org/project/pyannotate) (📥 3.7K / month · 📦 26 · ⏱️ 16.09.2019):
	```
	pip install pyannotate
	```
</details>
<details><summary><b><a href="https://github.com/asottile/add-trailing-comma">add-trailing-comma</a></b> (🥉20 ·  ⭐ 180) - A tool (and pre-commit hook) to automatically add trailing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/add-trailing-comma) (👨‍💻 9 · 🔀 13 · 📋 35 - 2% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/asottile/add-trailing-comma
	```
- [PyPi](https://pypi.org/project/add-trailing-comma) (📥 9.1K / month · 📦 14 · ⏱️ 24.01.2021):
	```
	pip install add-trailing-comma
	```
</details>
<details><summary><b><a href="https://github.com/hakancelik96/unimport">unimport</a></b> (🥉18 ·  ⭐ 100) - A linter, formatter for finding and removing unused import statements. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hakancelik96/unimport) (👨‍💻 11 · 🔀 14 · 📦 8 · 📋 71 - 12% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/hakancelik96/unimport
	```
- [PyPi](https://pypi.org/project/unimport) (📥 4.2K / month · ⏱️ 26.06.2021):
	```
	pip install unimport
	```
</details>
<details><summary><b><a href="https://github.com/ambv/retype">retype</a></b> (🥉17 ·  ⭐ 100) - Re-apply type annotations from .pyi stubs to your codebase. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ambv/retype) (👨‍💻 8 · 🔀 16 · 📋 15 - 60% open · ⏱️ 15.05.2021):

	```
	git clone https://github.com/ambv/retype
	```
- [PyPi](https://pypi.org/project/retype) (📥 1.1K / month · 📦 34 · ⏱️ 15.05.2021):
	```
	pip install retype
	```
- [Conda](https://anaconda.org/conda-forge/retype) (📥 14K · ⏱️ 16.05.2021):
	```
	conda install -c conda-forge retype
	```
</details>
<details><summary><b><a href="https://github.com/elmotec/massedit">massedit</a></b> (🥉16 ·  ⭐ 91 · 💤) - Programmatically edit text files with Python. Useful for source to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/elmotec/massedit) (👨‍💻 6 · 🔀 14 · 📥 15 · 📋 8 - 37% open · ⏱️ 23.12.2020):

	```
	git clone https://github.com/elmotec/massedit
	```
- [PyPi](https://pypi.org/project/massedit) (📥 910 / month · 📦 10 · ⏱️ 23.12.2020):
	```
	pip install massedit
	```
</details>
<details><summary><b><a href="https://github.com/ilevkivskyi/com2ann">com2ann</a></b> (🥉13 ·  ⭐ 90) - Tool for translation type comments to type annotations in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ilevkivskyi/com2ann) (👨‍💻 3 · 🔀 5 · 📦 2 · 📋 18 - 22% open · ⏱️ 07.03.2021):

	```
	git clone https://github.com/ilevkivskyi/com2ann
	```
- [PyPi](https://pypi.org/project/com2ann) (📥 370 / month · ⏱️ 17.06.2019):
	```
	pip install com2ann
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/redbaron">redbaron</a></b> (🥈23 ·  ⭐ 600 · 💀) - Bottom-up approach to refactoring in python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/PyCQA/baron">baron</a></b> (🥉22 ·  ⭐ 260 · 💀) - IDE allow you to refactor code, Baron allows you to write.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/myint/eradicate">eradicate</a></b> (🥉19 ·  ⭐ 110 · 💤) - Removes commented-out code from Python files. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/myint/unify">unify</a></b> (🥉19 ·  ⭐ 55 · 💀) - Modifies strings to all use the same quote where possible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/spulec/pep8ify">pep8ify</a></b> (🥉16 ·  ⭐ 110 · 💀) - A library that modifies python source code to conform to pep8. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Code Security

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/bandit">bandit</a></b> (🥇31 ·  ⭐ 3.3K) - Bandit is a tool designed to find common security issues in Python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PyCQA/bandit) (👨‍💻 130 · 🔀 330 · 📥 54 · 📦 7.1K · 📋 530 - 31% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/PyCQA/bandit
	```
- [PyPi](https://pypi.org/project/bandit) (📥 1.6M / month · 📦 2.4K · ⏱️ 13.12.2020):
	```
	pip install bandit
	```
- [Conda](https://anaconda.org/conda-forge/bandit) (📥 75K · ⏱️ 10.03.2021):
	```
	conda install -c conda-forge bandit
	```
</details>
<details><summary><b><a href="https://github.com/sqlmapproject/sqlmap">sqlmap</a></b> (🥈27 ·  ⭐ 20K) - Automatic SQL injection and database takeover tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sqlmapproject/sqlmap) (👨‍💻 110 · 🔀 4.4K · 📋 4.4K - 1% open · ⏱️ 24.06.2021):

	```
	git clone https://github.com/sqlmapproject/sqlmap
	```
- [PyPi](https://pypi.org/project/sqlmap) (📥 12K / month · 📦 8 · ⏱️ 08.06.2021):
	```
	pip install sqlmap
	```
</details>
<details><summary><b><a href="https://github.com/pyupio/safety">safety</a></b> (🥈27 ·  ⭐ 1K) - Safety checks your installed dependencies for known security vulnerabilities. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyupio/safety) (👨‍💻 35 · 🔀 87 · 📥 54K · 📦 2.1K · 📋 110 - 39% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pyupio/safety
	```
- [PyPi](https://pypi.org/project/safety) (📥 590K / month · 📦 540 · ⏱️ 15.01.2021):
	```
	pip install safety
	```
- [Conda](https://anaconda.org/conda-forge/safety) (📥 19K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge safety
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/detect-secrets">detect-secrets</a></b> (🥉26 ·  ⭐ 1.9K · ➕) - An enterprise friendly way of detecting and preventing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Yelp/detect-secrets) (👨‍💻 49 · 🔀 220 · 📋 220 - 34% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/Yelp/detect-secrets
	```
- [PyPi](https://pypi.org/project/detect-secrets) (📥 160K / month · 📦 34 · ⏱️ 14.04.2021):
	```
	pip install detect-secrets
	```
</details>
<details><summary><b><a href="https://github.com/landscapeio/dodgy">dodgy</a></b> (🥉21 ·  ⭐ 90) - Looks at Python code to search for things which look dodgy such as passwords.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/landscapeio/dodgy) (👨‍💻 14 · 🔀 18 · 📦 1.3K · 📋 11 - 72% open · ⏱️ 21.03.2021):

	```
	git clone https://github.com/landscapeio/dodgy
	```
- [PyPi](https://pypi.org/project/dodgy) (📥 150K / month · 📦 520 · ⏱️ 31.12.2019):
	```
	pip install dodgy
	```
- [Conda](https://anaconda.org/conda-forge/dodgy) (📥 24K · ⏱️ 10.06.2020):
	```
	conda install -c conda-forge dodgy
	```
</details>
<details><summary><b><a href="https://github.com/dlint-py/dlint">dlint</a></b> (🥉19 ·  ⭐ 320 · 💤) - Dlint is a tool for encouraging best coding practices and helping.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dlint-py/dlint) (👨‍💻 7 · 🔀 13 · 📋 32 - 62% open · ⏱️ 08.12.2020):

	```
	git clone https://github.com/dlint-py/dlint
	```
- [PyPi](https://pypi.org/project/dlint) (📥 27K / month · 📦 18 · ⏱️ 30.10.2020):
	```
	pip install dlint
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/dashingsoft/pyarmor">pyarmor</a></b> (🥉24 ·  ⭐ 990) - A tool used to obfuscate python scripts, bind obfuscated scripts.. <code><a href="https://tldrlegal.com/search?q=SGI-B-2.0">❗️SGI-B-2.0</a></code>
- <b><a href="https://github.com/python-security/pyt">pyt</a></b> (🥉22 ·  ⭐ 2K · 💀) - A Static Analysis Tool for Detecting Security Vulnerabilities in.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
</details>
<br>

## Virtual Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pipenv">pipenv</a></b> (🥇37 ·  ⭐ 22K) - Python Development Workflow for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipenv) (👨‍💻 380 · 🔀 1.6K · 📦 20K · 📋 3.4K - 15% open · ⏱️ 29.05.2021):

	```
	git clone https://github.com/pypa/pipenv
	```
- [PyPi](https://pypi.org/project/pipenv) (📥 3.6M / month · 📦 2.3K · ⏱️ 29.05.2021):
	```
	pip install pipenv
	```
- [Conda](https://anaconda.org/conda-forge/pipenv) (📥 40K · ⏱️ 15.11.2020):
	```
	conda install -c conda-forge pipenv
	```
</details>
<details><summary><b><a href="https://github.com/pypa/virtualenv">virtualenv</a></b> (🥈32 ·  ⭐ 3.9K) - Virtual Python Environment builder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/virtualenv) (👨‍💻 170 · 🔀 890 · 📋 1.1K - 5% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/pypa/virtualenv
	```
- [PyPi](https://pypi.org/project/virtualenv) (📥 19M / month · 📦 34K · ⏱️ 24.05.2021):
	```
	pip install virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/virtualenv) (📥 970K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv">pyenv</a></b> (🥈26 ·  ⭐ 24K) - Simple Python version management. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv) (👨‍💻 330 · 🔀 2.1K · 📋 1.3K - 2% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/pyenv/pyenv
	```
- [PyPi](https://pypi.org/project/pyenv) (📥 6.6K / month · 📦 1 · ⏱️ 12.01.2019):
	```
	pip install pyenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-virtualenv">pyenv-virtualenv</a></b> (🥉18 ·  ⭐ 4.3K) - a pyenv plugin to manage virtualenv (a.k.a. python-virtualenv). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-virtualenv) (👨‍💻 44 · 🔀 290 · 📋 310 - 43% open · ⏱️ 17.06.2021):

	```
	git clone https://github.com/pyenv/pyenv-virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-installer">pyenv-installer</a></b> (🥉15 ·  ⭐ 2.7K) - This tool is used to install `pyenv` and friends. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-installer) (👨‍💻 32 · 🔀 300 · 📋 66 - 7% open · ⏱️ 08.06.2021):

	```
	git clone https://github.com/pyenv/pyenv-installer
	```
</details>
<details><summary><b><a href="https://github.com/spotify/dh-virtualenv">dh-virtualenv</a></b> (🥉14 ·  ⭐ 1.5K) - Python virtualenvs in Debian packages. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/spotify/dh-virtualenv) (👨‍💻 56 · 🔀 160 · 📋 180 - 14% open · ⏱️ 12.04.2021):

	```
	git clone https://github.com/spotify/dh-virtualenv
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/sashahart/vex">vex</a></b> (🥉19 ·  ⭐ 370 · 💀) - Run a command in the named virtualenv. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gtalarico/pipenv-pipes">pipenv-pipes</a></b> (🥉14 ·  ⭐ 130 · 💀) - A PipEnv Environment Switcher. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Dependency & Package Mangers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pip">pip</a></b> (🥇34 ·  ⭐ 7.2K) - The Python package installer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pip) (👨‍💻 620 · 🔀 2.4K · 📦 53K · 📋 5.8K - 17% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/pypa/pip
	```
- [PyPi](https://pypi.org/project/pip) (📥 88M / month · 📦 19K · ⏱️ 26.06.2021):
	```
	pip install pip
	```
- [Conda](https://anaconda.org/conda-forge/pip) (📥 21M · ⏱️ 26.06.2021):
	```
	conda install -c conda-forge pip
	```
</details>
<details><summary><b><a href="https://github.com/python-poetry/poetry">poetry</a></b> (🥈32 ·  ⭐ 16K) - Python dependency management and packaging made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-poetry/poetry) (👨‍💻 280 · 🔀 1.2K · 📥 7M · 📋 3.1K - 37% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/python-poetry/poetry
	```
- [PyPi](https://pypi.org/project/poetry) (📥 2.6M / month · 📦 64 · ⏱️ 25.06.2021):
	```
	pip install poetry
	```
- [Conda](https://anaconda.org/conda-forge/poetry) (📥 230K · ⏱️ 25.06.2021):
	```
	conda install -c conda-forge poetry
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/pip-tools">pip-tools</a></b> (🥈32 ·  ⭐ 5.1K) - A set of tools to keep your pinned Python dependencies fresh. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/pip-tools) (👨‍💻 150 · 🔀 440 · 📋 730 - 15% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/jazzband/pip-tools
	```
- [PyPi](https://pypi.org/project/pip-tools) (📥 2.6M / month · 📦 3.3K · ⏱️ 22.06.2021):
	```
	pip install pip-tools
	```
- [Conda](https://anaconda.org/conda-forge/pip-tools) (📥 12K · ⏱️ 22.06.2021):
	```
	conda install -c conda-forge pip-tools
	```
</details>
<details><summary><b><a href="https://github.com/conda/conda">conda</a></b> (🥈32 ·  ⭐ 4.2K) - OS-agnostic, system-level binary package manager and ecosystem. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/conda) (👨‍💻 360 · 🔀 1K · 📋 8K - 24% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/conda/conda
	```
- [PyPi](https://pypi.org/project/conda) (📥 57K / month · 📦 2.1K · ⏱️ 22.04.2017):
	```
	pip install conda
	```
- [Conda](https://anaconda.org/conda-forge/conda) (📥 19M · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge conda
	```
</details>
<details><summary><b><a href="https://github.com/bndr/pipreqs">pipreqs</a></b> (🥉29 ·  ⭐ 3.5K) - pipreqs - Generate pip requirements.txt file based on imports of any.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bndr/pipreqs) (👨‍💻 50 · 🔀 220 · 📦 5.7K · 📋 170 - 48% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/bndr/pipreqs
	```
- [PyPi](https://pypi.org/project/pipreqs) (📥 120K / month · 📦 530 · ⏱️ 14.11.2019):
	```
	pip install pipreqs
	```
- [Conda](https://anaconda.org/conda-forge/pipreqs) (📥 21K · ⏱️ 14.11.2019):
	```
	conda install -c conda-forge pipreqs
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/mamba">mamba</a></b> (🥉25 ·  ⭐ 1.8K) - The Fast Cross-Platform Package Manager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/mamba) (👨‍💻 51 · 🔀 94 · 📦 330 · 📋 520 - 30% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/mamba-org/mamba
	```
- [Conda](https://anaconda.org/conda-forge/mamba) (📥 970K · ⏱️ 25.06.2021):
	```
	conda install -c conda-forge mamba
	```
</details>
<details><summary><b><a href="https://github.com/pypa/pipx">pipx</a></b> (🥉24 ·  ⭐ 3.8K) - Install and Run Python Applications in Isolated Environments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipx) (👨‍💻 57 · 🔀 160 · 📋 400 - 18% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/pypa/pipx
	```
- [PyPi](https://pypi.org/project/pipx) (📥 58K / month · 📦 4 · ⏱️ 28.05.2021):
	```
	pip install pipx
	```
</details>
<details><summary><b><a href="https://github.com/dephell/dephell">dephell</a></b> (🥉24 ·  ⭐ 1.7K) - Python project management. Manage packages: convert between formats,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dephell/dephell) (👨‍💻 37 · 🔀 99 · 📥 130 · 📦 230 · 📋 260 - 38% open · ⏱️ 11.01.2021):

	```
	git clone https://github.com/dephell/dephell
	```
- [PyPi](https://pypi.org/project/dephell) (📥 19K / month · 📦 8 · ⏱️ 28.04.2020):
	```
	pip install dephell
	```
</details>
<details><summary><b><a href="https://github.com/David-OConnor/pyflow">pyflow</a></b> (🥉18 ·  ⭐ 820) - An installation and dependency system for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/David-OConnor/pyflow) (👨‍💻 24 · 🔀 30 · 📥 3.2K · 📋 95 - 47% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/David-OConnor/pyflow
	```
- [PyPi](https://pypi.org/project/pyflow) (📥 220 / month · ⏱️ 29.05.2021):
	```
	pip install pyflow
	```
</details>
<details><summary><b><a href="https://github.com/jaraco/pip-run">pip-run</a></b> (🥉15 ·  ⭐ 60) - pip-run - dynamic dependency loader for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/pip-run) (👨‍💻 10 · 🔀 10 · 📋 39 - 5% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/jaraco/pip-run
	```
- [PyPi](https://pypi.org/project/pip-run) (📥 3.8K / month · ⏱️ 26.06.2021):
	```
	pip install pip-run
	```
</details>
<br>

## Code Metrics & Complexity

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/rubik/radon">radon</a></b> (🥇28 ·  ⭐ 1.2K) - Various code metrics for Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/radon) (👨‍💻 47 · 🔀 94 · 📦 1.8K · 📋 150 - 12% open · ⏱️ 08.06.2021):

	```
	git clone https://github.com/rubik/radon
	```
- [PyPi](https://pypi.org/project/radon) (📥 390K / month · 📦 1.1K · ⏱️ 08.06.2021):
	```
	pip install radon
	```
- [Conda](https://anaconda.org/conda-forge/radon) (📥 31K · ⏱️ 18.09.2020):
	```
	conda install -c conda-forge radon
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/mccabe">mccabe</a></b> (🥇28 ·  ⭐ 400) - McCabe complexity checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/mccabe) (👨‍💻 21 · 🔀 40 · 📦 200K · 📋 41 - 17% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/PyCQA/mccabe
	```
- [PyPi](https://pypi.org/project/mccabe) (📥 21M / month · 📦 31K · ⏱️ 26.01.2017):
	```
	pip install mccabe
	```
- [Conda](https://anaconda.org/conda-forge/mccabe) (📥 2.8M · ⏱️ 08.07.2018):
	```
	conda install -c conda-forge mccabe
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/prospector">prospector</a></b> (🥈27 ·  ⭐ 1.4K · 💤) - Inspects Python source files and provides information about.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/prospector) (👨‍💻 67 · 🔀 130 · 📦 2.3K · 📋 270 - 20% open · ⏱️ 21.10.2020):

	```
	git clone https://github.com/PyCQA/prospector
	```
- [PyPi](https://pypi.org/project/prospector) (📥 450K / month · 📦 1.1K · ⏱️ 21.10.2020):
	```
	pip install prospector
	```
- [Conda](https://anaconda.org/conda-forge/prospector) (📥 25K · ⏱️ 18.11.2020):
	```
	conda install -c conda-forge prospector
	```
</details>
<details><summary><b><a href="https://github.com/rubik/xenon">xenon</a></b> (🥉23 ·  ⭐ 190) - Monitoring tool based on radon. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/xenon) (👨‍💻 7 · 🔀 13 · 📦 220 · 📋 30 - 20% open · ⏱️ 26.05.2021):

	```
	git clone https://github.com/rubik/xenon
	```
- [PyPi](https://pypi.org/project/xenon) (📥 63K / month · 📦 120 · ⏱️ 26.05.2021):
	```
	pip install xenon
	```
- [Conda](https://anaconda.org/conda-forge/xenon) (📥 12K · ⏱️ 12.10.2019):
	```
	conda install -c conda-forge xenon
	```
</details>
<details><summary><b><a href="https://github.com/tonybaloney/wily">wily</a></b> (🥉20 ·  ⭐ 770) - A Python application for tracking, reporting on timing and complexity in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tonybaloney/wily) (👨‍💻 16 · 🔀 45 · 📋 80 - 35% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/tonybaloney/wily
	```
- [PyPi](https://pypi.org/project/wily) (📥 7.4K / month · 📦 16 · ⏱️ 01.07.2021):
	```
	pip install wily
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/mschwager/cohesion">cohesion</a></b> (🥉12 ·  ⭐ 140 · 💀) - A tool for measuring Python class cohesion. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tqdm/tqdm">tqdm</a></b> (🥇37 ·  ⭐ 19K) - A Fast, Extensible Progress Bar for Python and CLI. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/tqdm/tqdm) (👨‍💻 100 · 🔀 950 · 📥 7.9K · 📦 190K · 📋 800 - 35% open · ⏱️ 12.06.2021):

	```
	git clone https://github.com/tqdm/tqdm
	```
- [PyPi](https://pypi.org/project/tqdm) (📥 27M / month · 📦 26K · ⏱️ 12.06.2021):
	```
	pip install tqdm
	```
- [Conda](https://anaconda.org/conda-forge/tqdm) (📥 6.7M · ⏱️ 12.06.2021):
	```
	conda install -c conda-forge tqdm
	```
- [Docker Hub](https://hub.docker.com/r/tqdm/tqdm) (📥 3.7K · ⭐ 1 · ⏱️ 29.06.2021):
	```
	docker pull tqdm/tqdm
	```
</details>
<details><summary><b><a href="https://github.com/willmcgugan/rich">rich</a></b> (🥇33 ·  ⭐ 27K) - Rich is a Python library for rich text and beautiful formatting in the terminal. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/willmcgugan/rich) (👨‍💻 95 · 🔀 820 · 📦 5K · 📋 470 - 1% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/willmcgugan/rich
	```
- [PyPi](https://pypi.org/project/rich) (📥 1.8M / month · ⏱️ 18.06.2021):
	```
	pip install rich
	```
- [Conda](https://anaconda.org/conda-forge/rich) (📥 280K · ⏱️ 18.06.2021):
	```
	conda install -c conda-forge rich
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/sentry-python">sentry-sdk</a></b> (🥇32 ·  ⭐ 950) - The new Python SDK for Sentry.io. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/getsentry/sentry-python) (👨‍💻 99 · 🔀 210 · 📥 4.5K · 📦 12K · 📋 550 - 31% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/getsentry/sentry-python
	```
- [PyPi](https://pypi.org/project/sentry-sdk) (📥 9.9M / month · 📦 990 · ⏱️ 06.05.2021):
	```
	pip install sentry-sdk
	```
- [Conda](https://anaconda.org/conda-forge/sentry-sdk) (📥 89K · ⏱️ 11.05.2021):
	```
	conda install -c conda-forge sentry-sdk
	```
</details>
<details><summary><b><a href="https://github.com/astanin/python-tabulate">tabulate</a></b> (🥈31 ·  ⭐ 870) - Pretty-print tabular data in Python, a library and a command-line.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/astanin/python-tabulate) (👨‍💻 67 · 🔀 66 · 📦 46K · 📋 84 - 32% open · ⏱️ 04.03.2021):

	```
	git clone https://github.com/astanin/python-tabulate
	```
- [PyPi](https://pypi.org/project/tabulate) (📥 20M / month · 📦 8.1K · ⏱️ 22.02.2021):
	```
	pip install tabulate
	```
- [Conda](https://anaconda.org/conda-forge/tabulate) (📥 1.2M · ⏱️ 22.02.2021):
	```
	conda install -c conda-forge tabulate
	```
</details>
<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥈30 ·  ⭐ 9.2K · 📉) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 29 · 🔀 410 · 📦 8K · 📋 420 - 11% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 1.5M / month · 📦 340 · ⏱️ 20.09.2020):
	```
	pip install loguru
	```
- [Conda](https://anaconda.org/conda-forge/loguru) (📥 200K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge loguru
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈28 ·  ⭐ 1.5K) - Structured Logging for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 73 · 🔀 140 · 📦 3.4K · 📋 180 - 18% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 2.3M / month · 📦 1.2K · ⏱️ 18.02.2021):
	```
	pip install structlog
	```
- [Conda](https://anaconda.org/conda-forge/structlog) (📥 120K · ⏱️ 22.02.2021):
	```
	conda install -c conda-forge structlog
	```
</details>
<details><summary><b><a href="https://github.com/madzak/python-json-logger">python-json-logger</a></b> (🥈28 ·  ⭐ 990 · 💤) - Json Formatter for the standard python logger. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madzak/python-json-logger) (👨‍💻 43 · 🔀 150 · 📦 16K · 📋 64 - 29% open · ⏱️ 12.10.2020):

	```
	git clone https://github.com/madzak/python-json-logger
	```
- [PyPi](https://pypi.org/project/python-json-logger) (📥 3.5M / month · 📦 920 · ⏱️ 12.10.2020):
	```
	pip install python-json-logger
	```
- [Conda](https://anaconda.org/conda-forge/python-json-logger) (📥 720K · ⏱️ 12.10.2020):
	```
	conda install -c conda-forge python-json-logger
	```
</details>
<details><summary><b><a href="https://github.com/borntyping/python-colorlog">colorlog</a></b> (🥈28 ·  ⭐ 700) - A colored formatter for the python logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/borntyping/python-colorlog) (👨‍💻 30 · 🔀 75 · 📦 10K · 📋 66 - 3% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/borntyping/python-colorlog
	```
- [PyPi](https://pypi.org/project/colorlog) (📥 5.6M / month · 📦 3.7K · ⏱️ 14.06.2021):
	```
	pip install colorlog
	```
- [Conda](https://anaconda.org/conda-forge/colorlog) (📥 380K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge colorlog
	```
</details>
<details><summary><b><a href="https://github.com/xolox/python-coloredlogs">python-coloredlogs</a></b> (🥈28 ·  ⭐ 420) - Colored terminal output for Python's logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xolox/python-coloredlogs) (👨‍💻 16 · 🔀 36 · 📦 8.1K · 📋 74 - 33% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/xolox/python-coloredlogs
	```
- [PyPi](https://pypi.org/project/coloredlogs) (📥 1.8M / month · 📦 2.1K · ⏱️ 11.06.2021):
	```
	pip install coloredlogs
	```
</details>
<details><summary><b><a href="https://github.com/WoLpH/python-progressbar">progressbar2</a></b> (🥉27 ·  ⭐ 700) - Progressbar 2 - A progress bar for Python 2 and Python 3 - pip.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/WoLpH/python-progressbar) (👨‍💻 38 · 🔀 91 · 📥 1.6K · 📦 9.9K · 📋 190 - 4% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/WoLpH/python-progressbar
	```
- [PyPi](https://pypi.org/project/progressbar2) (📥 1.2M / month · 📦 2.2K · ⏱️ 09.09.2020):
	```
	pip install progressbar2
	```
- [Conda](https://anaconda.org/conda-forge/progressbar2) (📥 300K · ⏱️ 09.09.2020):
	```
	conda install -c conda-forge progressbar2
	```
</details>
<details><summary><b><a href="https://github.com/ines/wasabi">wasabi</a></b> (🥉25 ·  ⭐ 290 · ➕) - A lightweight console printing and formatting toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ines/wasabi) (👨‍💻 4 · 🔀 16 · 📦 12K · 📋 6 - 50% open · ⏱️ 31.01.2021):

	```
	git clone https://github.com/ines/wasabi
	```
- [PyPi](https://pypi.org/project/wasabi) (📥 2.3M / month · 📦 410 · ⏱️ 31.01.2021):
	```
	pip install wasabi
	```
- [Conda](https://anaconda.org/conda-forge/wasabi) (📥 380K · ⏱️ 01.02.2021):
	```
	conda install -c conda-forge wasabi
	```
</details>
<details><summary><b><a href="https://github.com/liiight/notifiers">notifiers</a></b> (🥉24 ·  ⭐ 1.9K · 💤) - The easy way to send notifications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/liiight/notifiers) (👨‍💻 14 · 🔀 72 · 📦 140 · 📋 91 - 41% open · ⏱️ 30.12.2020):

	```
	git clone https://github.com/liiight/notifiers
	```
- [PyPi](https://pypi.org/project/notifiers) (📥 310K / month · 📦 6 · ⏱️ 05.10.2019):
	```
	pip install notifiers
	```
</details>
<details><summary><b><a href="https://github.com/shobrook/rebound">rebound</a></b> (🥉23 ·  ⭐ 3.7K) - Command-line tool that instantly fetches Stack Overflow results when an.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/shobrook/rebound) (👨‍💻 16 · 🔀 340 · 📥 170 · 📦 19 · 📋 58 - 34% open · ⏱️ 04.01.2021):

	```
	git clone https://github.com/shobrook/rebound
	```
- [PyPi](https://pypi.org/project/rebound) (📥 2.1K / month · 📦 14 · ⏱️ 20.06.2021):
	```
	pip install rebound
	```
- [Conda](https://anaconda.org/conda-forge/rebound) (📥 130K · ⏱️ 21.06.2021):
	```
	conda install -c conda-forge rebound
	```
</details>
<details><summary><b><a href="https://github.com/rsalmei/alive-progress">alive-progress</a></b> (🥉23 ·  ⭐ 2.5K) - A new kind of Progress Bar, with real time throughput, eta and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rsalmei/alive-progress) (👨‍💻 1 · 🔀 100 · 📦 330 · 📋 70 - 30% open · ⏱️ 08.01.2021):

	```
	git clone https://github.com/rsalmei/alive-progress
	```
- [PyPi](https://pypi.org/project/alive-progress) (📥 16K / month · ⏱️ 08.01.2021):
	```
	pip install alive-progress
	```
- [Conda](https://anaconda.org/conda-forge/alive-progress) (📥 7.9K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge alive-progress
	```
</details>
<details><summary><b><a href="https://github.com/Qix-/better-exceptions">better-exceptions</a></b> (🥉22 ·  ⭐ 4K) - Pretty and useful exceptions in Python, automatically. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Qix-/better-exceptions) (👨‍💻 14 · 🔀 200 · 📋 70 - 41% open · ⏱️ 29.01.2021):

	```
	git clone https://github.com/Qix-/better-exceptions
	```
- [PyPi](https://pypi.org/project/better-exceptions) (📥 31K / month · 📦 74 · ⏱️ 29.01.2021):
	```
	pip install better-exceptions
	```
</details>
<details><summary><b><a href="https://github.com/cknd/stackprinter">stackprinter</a></b> (🥉22 ·  ⭐ 1.1K) - Debugging-friendly exceptions for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cknd/stackprinter) (👨‍💻 6 · 🔀 31 · 📦 58 · 📋 23 - 39% open · ⏱️ 01.01.2021):

	```
	git clone https://github.com/cknd/stackprinter
	```
- [PyPi](https://pypi.org/project/stackprinter) (📥 20K / month · 📦 4 · ⏱️ 31.10.2020):
	```
	pip install stackprinter
	```
</details>
<details><summary><b><a href="https://github.com/onelivesleft/PrettyErrors">PrettyErrors</a></b> (🥉20 ·  ⭐ 2.1K) - Prettify Python exception output to make it legible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/onelivesleft/PrettyErrors) (👨‍💻 4 · 🔀 64 · 📋 30 - 3% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/onelivesleft/PrettyErrors
	```
- [PyPi](https://pypi.org/project/pretty_errors) (📥 15K / month · ⏱️ 22.06.2021):
	```
	pip install pretty_errors
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/python-devtools">python-devtools</a></b> (🥉19 ·  ⭐ 350 · ➕) - Dev tools for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/python-devtools) (👨‍💻 5 · 🔀 12 · 📦 370 · 📋 34 - 35% open · ⏱️ 30.03.2021):

	```
	git clone https://github.com/samuelcolvin/python-devtools
	```
- [PyPi](https://pypi.org/project/python-devtools) (📥 450 / month · 📦 1 · ⏱️ 21.08.2017):
	```
	pip install python-devtools
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/getlogbook/logbook">logbook</a></b> (🥈31 ·  ⭐ 1.4K · 💀) - A cool logging replacement for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jazzband/prettytable">prettytable</a></b> (🥉23 ·  ⭐ 500) - Display tabular data in a visually appealing ASCII table.. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/skorokithakis/tbvaccine">tbvaccine</a></b> (🥉15 ·  ⭐ 360 · 💀) - A small utility to pretty-print Python tracebacks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Documentation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/sphinx-doc/sphinx">sphinx</a></b> (🥇38 ·  ⭐ 4K) - Main repository for the Sphinx documentation builder. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sphinx-doc/sphinx) (👨‍💻 650 · 🔀 1.5K · 📦 150K · 📋 5.4K - 14% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/sphinx-doc/sphinx
	```
- [PyPi](https://pypi.org/project/sphinx) (📥 4M / month · 📦 100K · ⏱️ 20.05.2021):
	```
	pip install sphinx
	```
- [Conda](https://anaconda.org/conda-forge/sphinx) (📥 3.5M · ⏱️ 25.05.2021):
	```
	conda install -c conda-forge sphinx
	```
</details>
<details><summary><b><a href="https://github.com/mkdocs/mkdocs">mkdocs</a></b> (🥇35 ·  ⭐ 12K) - Project documentation with Markdown. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocs/mkdocs) (👨‍💻 190 · 🔀 1.8K · 📦 13K · 📋 1.5K - 8% open · ⏱️ 09.06.2021):

	```
	git clone https://github.com/mkdocs/mkdocs
	```
- [PyPi](https://pypi.org/project/mkdocs) (📥 640K / month · 📦 5.9K · ⏱️ 09.06.2021):
	```
	pip install mkdocs
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs) (📥 140K · ⏱️ 25.06.2021):
	```
	conda install -c conda-forge mkdocs
	```
</details>
<details><summary><b><a href="https://github.com/squidfunk/mkdocs-material">mkdocs-material</a></b> (🥇33 ·  ⭐ 6.9K) - A Material Design theme for MkDocs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/squidfunk/mkdocs-material) (👨‍💻 120 · 🔀 1.6K · 📦 7.2K · 📋 1.1K - 1% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/squidfunk/mkdocs-material
	```
- [PyPi](https://pypi.org/project/mkdocs-material) (📥 490K / month · 📦 1.5K · ⏱️ 25.06.2021):
	```
	pip install mkdocs-material
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs-material) (📥 48K · ⏱️ 12.06.2021):
	```
	conda install -c conda-forge mkdocs-material
	```
</details>
<details><summary><b><a href="https://github.com/readthedocs/sphinx_rtd_theme">sphinx_rtd_theme</a></b> (🥇33 ·  ⭐ 3.7K) - Sphinx theme for readthedocs.org. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/readthedocs/sphinx_rtd_theme) (👨‍💻 110 · 🔀 1.6K · 📦 16 · 📋 700 - 27% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/readthedocs/sphinx_rtd_theme
	```
- [PyPi](https://pypi.org/project/sphinx_rtd_theme) (📥 1.9M / month · 📦 23K · ⏱️ 05.10.2018):
	```
	pip install sphinx_rtd_theme
	```
- [Conda](https://anaconda.org/conda-forge/sphinx_rtd_theme) (📥 1.4M · ⏱️ 06.04.2021):
	```
	conda install -c conda-forge sphinx_rtd_theme
	```
</details>
<details><summary><b><a href="https://github.com/numpy/numpydoc">numpydoc</a></b> (🥈30 ·  ⭐ 17K) - Numpy's Sphinx extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/numpy/numpydoc) (👨‍💻 65 · 🔀 5.6K · 📦 26K · 📋 140 - 35% open · ⏱️ 19.05.2021):

	```
	git clone https://github.com/numpy/numpydoc
	```
- [PyPi](https://pypi.org/project/numpydoc) (📥 230K / month · 📦 7.3K · ⏱️ 01.07.2020):
	```
	pip install numpydoc
	```
- [Conda](https://anaconda.org/conda-forge/numpydoc) (📥 790K · ⏱️ 01.10.2020):
	```
	conda install -c conda-forge numpydoc
	```
</details>
<details><summary><b><a href="https://github.com/michaeljones/breathe">breathe</a></b> (🥈29 ·  ⭐ 540) - ReStructuredText and Sphinx bridge to Doxygen. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/michaeljones/breathe) (👨‍💻 94 · 🔀 140 · 📥 79 · 📦 4.7K · 📋 440 - 23% open · ⏱️ 18.05.2021):

	```
	git clone https://github.com/michaeljones/breathe
	```
- [PyPi](https://pypi.org/project/breathe) (📥 96K / month · 📦 2K · ⏱️ 06.05.2021):
	```
	pip install breathe
	```
- [Conda](https://anaconda.org/conda-forge/breathe) (📥 200K · ⏱️ 08.05.2021):
	```
	conda install -c conda-forge breathe
	```
</details>
<details><summary><b><a href="https://github.com/agronholm/sphinx-autodoc-typehints">sphinx-autodoc-typehints</a></b> (🥈26 ·  ⭐ 350) - Type hints support for the Sphinx autodoc extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/agronholm/sphinx-autodoc-typehints) (👨‍💻 29 · 🔀 65 · 📋 120 - 39% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/agronholm/sphinx-autodoc-typehints
	```
- [PyPi](https://pypi.org/project/sphinx-autodoc-typehints) (📥 290K / month · 📦 1.4K · ⏱️ 12.10.2020):
	```
	pip install sphinx-autodoc-typehints
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autodoc-typehints) (📥 190K · ⏱️ 15.04.2021):
	```
	conda install -c conda-forge sphinx-autodoc-typehints
	```
</details>
<details><summary><b><a href="https://github.com/pdoc3/pdoc">pdoc3</a></b> (🥈25 ·  ⭐ 660 · ➕) - Auto-generate API documentation for Python projects. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/pdoc3/pdoc) (👨‍💻 55 · 🔀 110 · 📦 900 · 📋 260 - 32% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/pdoc3/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc3) (📥 94K / month · 📦 90 · ⏱️ 27.11.2020):
	```
	pip install pdoc3
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/sphinx-autobuild">sphinx-autobuild</a></b> (🥈25 ·  ⭐ 340) - Watch a Sphinx directory and rebuild the documentation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/executablebooks/sphinx-autobuild) (👨‍💻 17 · 🔀 49 · 📋 56 - 21% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/executablebooks/sphinx-autobuild
	```
- [PyPi](https://pypi.org/project/sphinx-autobuild) (📥 170K / month · 📦 4.7K · ⏱️ 14.03.2021):
	```
	pip install sphinx-autobuild
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autobuild) (📥 63K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge sphinx-autobuild
	```
</details>
<details><summary><b><a href="https://github.com/mitmproxy/pdoc">pdoc</a></b> (🥉24 ·  ⭐ 950) - API Documentation for Python Projects. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/mitmproxy/pdoc) (👨‍💻 30 · 🔀 110 · 📦 340 · 📋 170 - 2% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/mitmproxy/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc) (📥 62K / month · 📦 290 · ⏱️ 11.06.2021):
	```
	pip install pdoc
	```
</details>
<details><summary><b><a href="https://github.com/econchick/interrogate">interrogate</a></b> (🥉24 ·  ⭐ 280) - Explain yourself! Interrogate a codebase for docstring coverage. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/econchick/interrogate) (👨‍💻 9 · 🔀 21 · 📦 670 · 📋 30 - 36% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/econchick/interrogate
	```
- [PyPi](https://pypi.org/project/interrogate) (📥 61K / month · ⏱️ 15.05.2021):
	```
	pip install interrogate
	```
</details>
<details><summary><b><a href="https://github.com/asottile/blacken-docs">blacken-docs</a></b> (🥉21 ·  ⭐ 220) - Run `black` on python code blocks in documentation files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/blacken-docs) (👨‍💻 12 · 🔀 17 · 📋 31 - 6% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/asottile/blacken-docs
	```
- [PyPi](https://pypi.org/project/blacken-docs) (📥 7.3K / month · 📦 22 · ⏱️ 02.03.2021):
	```
	pip install blacken-docs
	```
- [Conda](https://anaconda.org/conda-forge/blacken-docs) (📥 17K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge blacken-docs
	```
</details>
<details><summary><b><a href="https://github.com/zhaoterryy/mkdocs-pdf-export-plugin">mkdocs-pdf-export-plugin</a></b> (🥉21 ·  ⭐ 190 · 💤) - An MkDocs plugin to export content pages as PDF files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zhaoterryy/mkdocs-pdf-export-plugin) (👨‍💻 9 · 🔀 29 · 📦 130 · 📋 80 - 45% open · ⏱️ 23.07.2020):

	```
	git clone https://github.com/zhaoterryy/mkdocs-pdf-export-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-pdf-export-plugin) (📥 12K / month · 📦 4 · ⏱️ 23.07.2020):
	```
	pip install mkdocs-pdf-export-plugin
	```
</details>
<details><summary><b><a href="https://github.com/mkdocstrings/mkdocstrings">mkdocstrings</a></b> (🥉20 ·  ⭐ 380) - Automatic documentation from sources, for MkDocs. <code><a href="http://bit.ly/3hkKRql">ISC</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocstrings/mkdocstrings) (👨‍💻 19 · 🔀 47 · 📋 180 - 23% open · ⏱️ 09.06.2021):

	```
	git clone https://github.com/mkdocstrings/mkdocstrings
	```
- [PyPi](https://pypi.org/project/mkdocstrings) (📥 52K / month · ⏱️ 09.06.2021):
	```
	pip install mkdocstrings
	```
- [Conda](https://anaconda.org/conda-forge/mkdocstrings) (📥 5.1K · ⏱️ 10.06.2021):
	```
	conda install -c conda-forge mkdocstrings
	```
</details>
<details><summary><b><a href="https://github.com/clayrisser/sphinx-markdown-builder">sphinx-markdown-builder</a></b> (🥉20 ·  ⭐ 100 · 💤) - sphinx builder that outputs markdown files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/clayrisser/sphinx-markdown-builder) (👨‍💻 16 · 🔀 28 · 📦 150 · 📋 34 - 52% open · ⏱️ 07.10.2020):

	```
	git clone https://github.com/codejamninja/sphinx-markdown-builder
	```
- [PyPi](https://pypi.org/project/sphinx-markdown-builder) (📥 13K / month · 📦 42 · ⏱️ 23.12.2019):
	```
	pip install sphinx-markdown-builder
	```
</details>
<details><summary><b><a href="https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin">mkdocs-awesome-pages-plugin</a></b> (🥉19 ·  ⭐ 160 · 💤) - An MkDocs plugin that simplifies configuring page.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin) (👨‍💻 2 · 🔀 17 · 📦 390 · 📋 38 - 15% open · ⏱️ 22.12.2020):

	```
	git clone https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-awesome-pages-plugin) (📥 39K / month · 📦 90 · ⏱️ 22.12.2020):
	```
	pip install mkdocs-awesome-pages-plugin
	```
</details>
<details><summary><b><a href="https://github.com/orzih/mkdocs-with-pdf">mkdocs-with-pdf</a></b> (🥉19 ·  ⭐ 67) - Generate a single PDF file from MkDocs repository. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/orzih/mkdocs-with-pdf) (👨‍💻 6 · 🔀 10 · 📦 33 · 📋 47 - 31% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/orzih/mkdocs-with-pdf
	```
- [PyPi](https://pypi.org/project/mkdocs-with-pdf) (📥 6.5K / month · ⏱️ 15.06.2021):
	```
	pip install mkdocs-with-pdf
	```
</details>
<details><summary><b><a href="https://github.com/timothycrosley/portray">portray</a></b> (🥉18 ·  ⭐ 740) - Your Project with Great Documentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timothycrosley/portray) (👨‍💻 16 · 🔀 57 · 📋 49 - 40% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/timothycrosley/portray
	```
- [PyPi](https://pypi.org/project/portray) (📥 7.9K / month · 📦 8 · ⏱️ 13.06.2021):
	```
	pip install portray
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazydocs">lazydocs</a></b> (🥉16 ·  ⭐ 27) - Generate markdown API documentation from Google-style Python docstring... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/lazydocs) (👨‍💻 4 · 🔀 6 · 📦 27 · 📋 4 - 50% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/ml-tooling/lazydocs
	```
- [PyPi](https://pypi.org/project/lazydocs) (📥 390 / month · ⏱️ 30.06.2021):
	```
	pip install lazydocs
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/bitprophet/alabaster">alabaster</a></b> (🥈31 ·  ⭐ 610 · 💀) - Lightweight, configurable Sphinx theme. Now the Sphinx.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ryan-roemer/sphinx-bootstrap-theme">sphinx-bootstrap-theme</a></b> (🥈25 ·  ⭐ 580 · 💀) - Sphinx Bootstrap Theme. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bitprophet/releases">releases</a></b> (🥉23 ·  ⭐ 160 · 💀) - A powerful Sphinx changelog-generating extension. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pycco-docs/pycco">pycco</a></b> (🥉22 ·  ⭐ 750 · 💀) - Literate-style documentation generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zhaoterryy/mkdocs-git-revision-date-plugin">mkdocs-git-revision-date-plugin</a></b> (🥉19 ·  ⭐ 34 · 💤) - MkDocs plugin for setting revision date from git per.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zayd62/mkdocs-versioning">mkdocs-versioning</a></b> (🥉18 ·  ⭐ 40) - A tool that allows for versioning sites built with mkdocs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/timvink/mkdocs-print-site-plugin">mkdocs-print-site-plugin</a></b> (🥉17 ·  ⭐ 19) - MkDocs Plugin allowing your visitors to *File Print.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Debugging Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/gotcha/ipdb">ipdb</a></b> (🥇31 ·  ⭐ 1.4K) - Integration of IPython pdb. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gotcha/ipdb) (👨‍💻 48 · 🔀 130 · 📦 27K · 📋 160 - 31% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/gotcha/ipdb
	```
- [PyPi](https://pypi.org/project/ipdb) (📥 1.7M / month · 📦 17K · ⏱️ 02.06.2021):
	```
	pip install ipdb
	```
- [Conda](https://anaconda.org/conda-forge/ipdb) (📥 180K · ⏱️ 24.06.2021):
	```
	conda install -c conda-forge ipdb
	```
</details>
<details><summary><b><a href="https://github.com/cool-RR/PySnooper">PySnooper</a></b> (🥇29 ·  ⭐ 14K) - Never use print for debugging again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cool-RR/PySnooper) (👨‍💻 26 · 🔀 900 · 📦 430 · 📋 110 - 16% open · ⏱️ 19.05.2021):

	```
	git clone https://github.com/cool-RR/PySnooper
	```
- [PyPi](https://pypi.org/project/pysnooper) (📥 80K / month · 📦 46 · ⏱️ 19.05.2021):
	```
	pip install pysnooper
	```
- [Conda](https://anaconda.org/conda-forge/pysnooper) (📥 37K · ⏱️ 19.05.2021):
	```
	conda install -c conda-forge pysnooper
	```
</details>
<details><summary><b><a href="https://github.com/eliben/pyelftools">pyelftools</a></b> (🥈28 ·  ⭐ 1.2K) - Parsing ELF and DWARF in Python. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/eliben/pyelftools) (👨‍💻 75 · 🔀 400 · 📦 2.3K · 📋 170 - 32% open · ⏱️ 27.05.2021):

	```
	git clone https://github.com/eliben/pyelftools
	```
- [PyPi](https://pypi.org/project/pyelftools) (📥 630K / month · 📦 880 · ⏱️ 27.10.2020):
	```
	pip install pyelftools
	```
- [Conda](https://anaconda.org/conda-forge/pyelftools) (📥 67K · ⏱️ 27.10.2020):
	```
	conda install -c conda-forge pyelftools
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pudb">pudb</a></b> (🥈27 ·  ⭐ 2.1K · 📈) - Full-screen console debugger for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pudb) (👨‍💻 77 · 🔀 180 · 📦 2.4K · 📋 270 - 50% open · ⏱️ 25.06.2021):

	```
	git clone https://github.com/inducer/pudb
	```
- [PyPi](https://pypi.org/project/pudb) (📥 230K / month · 📦 1.4K · ⏱️ 08.05.2021):
	```
	pip install pudb
	```
- [Conda](https://anaconda.org/conda-forge/pudb) (📥 100K · ⏱️ 15.04.2020):
	```
	conda install -c conda-forge pudb
	```
</details>
<details><summary><b><a href="https://github.com/pdbpp/pdbpp">pdbpp</a></b> (🥈26 ·  ⭐ 750) - pdb++, a drop-in replacement for pdb (the Python debugger). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pdbpp/pdbpp) (👨‍💻 39 · 🔀 42 · 📦 2.1K · 📋 170 - 33% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/pdbpp/pdbpp
	```
- [PyPi](https://pypi.org/project/pdbpp) (📥 320K / month · 📦 1K · ⏱️ 04.10.2019):
	```
	pip install pdbpp
	```
- [Conda](https://anaconda.org/conda-forge/pdbpp) (📥 59K · ⏱️ 07.05.2019):
	```
	conda install -c conda-forge pdbpp
	```
</details>
<details><summary><b><a href="https://github.com/agronholm/typeguard">typeguard</a></b> (🥈26 ·  ⭐ 660) - Run-time type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/agronholm/typeguard) (👨‍💻 18 · 🔀 61 · 📋 160 - 25% open · ⏱️ 04.06.2021):

	```
	git clone https://github.com/agronholm/typeguard
	```
- [PyPi](https://pypi.org/project/typeguard) (📥 4.3M / month · 📦 160 · ⏱️ 04.06.2021):
	```
	pip install typeguard
	```
- [Conda](https://anaconda.org/conda-forge/typeguard) (📥 44K · ⏱️ 04.06.2021):
	```
	conda install -c conda-forge typeguard
	```
</details>
<details><summary><b><a href="https://github.com/cs01/gdbgui">gdbgui</a></b> (🥉25 ·  ⭐ 8K) - Browser-based frontend to gdb (gnu debugger). Add breakpoints, view.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cs01/gdbgui) (👨‍💻 36 · 🔀 470 · 📥 4.1K · 📦 90 · 📋 270 - 41% open · ⏱️ 01.06.2021):

	```
	git clone https://github.com/cs01/gdbgui
	```
- [PyPi](https://pypi.org/project/gdbgui) (📥 110K / month · 📦 2 · ⏱️ 20.05.2021):
	```
	pip install gdbgui
	```
</details>
<details><summary><b><a href="https://github.com/gruns/icecream">icecream</a></b> (🥉23 ·  ⭐ 5K) - Never use print() to debug again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gruns/icecream) (👨‍💻 14 · 🔀 99 · 📋 68 - 23% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/gruns/icecream
	```
- [PyPi](https://pypi.org/project/icecream) (📥 68K / month · 📦 6 · ⏱️ 22.06.2021):
	```
	pip install icecream
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-hunter">python-hunter</a></b> (🥉22 ·  ⭐ 620) - Hunter is a flexible code tracing toolkit. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-hunter) (👨‍💻 8 · 🔀 32 · 📦 63 · 📋 83 - 44% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/ionelmc/python-hunter
	```
- [PyPi](https://pypi.org/project/hunter) (📥 6K / month · 📦 34 · ⏱️ 23.06.2021):
	```
	pip install hunter
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/snoop">snoop</a></b> (🥉22 ·  ⭐ 600) - A powerful set of Python debugging tools, based on PySnooper. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/snoop) (👨‍💻 20 · 🔀 20 · 📦 55 · 📋 29 - 44% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/alexmojaki/snoop
	```
- [PyPi](https://pypi.org/project/snoop) (📥 32K / month · 📦 8 · ⏱️ 26.03.2021):
	```
	pip install snoop
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-manhole">python-manhole</a></b> (🥉21 ·  ⭐ 310) - Debugging manhole for python applications. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-manhole) (👨‍💻 10 · 🔀 15 · 📦 70 · 📋 20 - 25% open · ⏱️ 08.04.2021):

	```
	git clone https://github.com/ionelmc/python-manhole
	```
- [PyPi](https://pypi.org/project/manhole) (📥 8.4K / month · 📦 66 · ⏱️ 08.04.2021):
	```
	pip install manhole
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/birdseye">Birdseye</a></b> (🥉19 ·  ⭐ 1.4K) - Graphical Python debugger which lets you easily view the values of all.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/birdseye) (👨‍💻 9 · 🔀 70 · 📋 48 - 35% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/alexmojaki/birdseye
	```
- [PyPi](https://pypi.org/project/birdseye) (📥 1.1K / month · ⏱️ 25.08.2020):
	```
	pip install birdseye
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/lmacken/pyrasite">pyrasite</a></b> (🥉21 ·  ⭐ 2.5K · 💀) - Inject code into running Python processes. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Testing Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python">best-of-web-python - Testing</a></b> ( ⭐ 1.3K · 🐣)  - Testing libraries & tools for python web frameworks.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.html">unittest</a></b>  - Unittest is a test framework included in the Python standard library.

<details><summary><b><a href="https://github.com/pytest-dev/pytest">pytest</a></b> (🥇36 ·  ⭐ 7.5K) - The pytest framework makes it easy to write small tests, yet scales.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest) (👨‍💻 730 · 🔀 1.7K · 📦 340K · 📋 4.5K - 14% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/pytest-dev/pytest
	```
- [PyPi](https://pypi.org/project/pytest) (📥 29M / month · 📦 130K · ⏱️ 04.05.2021):
	```
	pip install pytest
	```
- [Conda](https://anaconda.org/conda-forge/pytest) (📥 8.3M · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge pytest
	```
</details>
<details><summary><b><a href="https://github.com/tox-dev/tox">tox</a></b> (🥇36 ·  ⭐ 2.3K) - Command line driven CI frontend and development task automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/tox) (👨‍💻 240 · 🔀 370 · 📦 46K · 📋 1.2K - 11% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/tox-dev/tox
	```
- [PyPi](https://pypi.org/project/tox) (📥 4.3M / month · 📦 36K · ⏱️ 05.05.2021):
	```
	pip install tox
	```
- [Conda](https://anaconda.org/conda-forge/tox) (📥 300K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge tox
	```
</details>
<details><summary><b><a href="https://github.com/robotframework/robotframework">robotframework</a></b> (🥇34 ·  ⭐ 6.1K) - Generic automation framework for acceptance testing and RPA. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/robotframework/robotframework) (👨‍💻 140 · 🔀 1.7K · 📥 510 · 📦 3.9K · 📋 3.6K - 5% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/robotframework/robotframework
	```
- [PyPi](https://pypi.org/project/robotframework) (📥 710K / month · 📦 1.4K · ⏱️ 25.05.2021):
	```
	pip install robotframework
	```
- [Conda](https://anaconda.org/conda-forge/robotframework) (📥 53K · ⏱️ 25.05.2021):
	```
	conda install -c conda-forge robotframework
	```
</details>
<details><summary><b><a href="https://github.com/HypothesisWorks/hypothesis">hypothesis</a></b> (🥇33 ·  ⭐ 5.3K) - Hypothesis is a powerful, flexible, and easy to use library for.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/HypothesisWorks/hypothesis) (👨‍💻 250 · 🔀 460 · 📦 9.1K · 📋 1.1K - 5% open · ⏱️ 15.06.2021):

	```
	git clone https://github.com/HypothesisWorks/hypothesis
	```
- [PyPi](https://pypi.org/project/hypothesis) (📥 2M / month · 📦 2.6K · ⏱️ 09.06.2021):
	```
	pip install hypothesis
	```
- [Conda](https://anaconda.org/conda-forge/hypothesis) (📥 4.3M · ⏱️ 09.06.2021):
	```
	conda install -c conda-forge hypothesis
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-cov">pytest-cov</a></b> (🥇32 ·  ⭐ 1.1K) - Coverage plugin for pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-cov) (👨‍💻 66 · 🔀 150 · 📦 90K · 📋 290 - 34% open · ⏱️ 01.06.2021):

	```
	git clone https://github.com/pytest-dev/pytest-cov
	```
- [PyPi](https://pypi.org/project/pytest-cov) (📥 13M / month · 📦 43K · ⏱️ 01.06.2021):
	```
	pip install pytest-cov
	```
- [Conda](https://anaconda.org/conda-forge/pytest-cov) (📥 3.1M · ⏱️ 02.06.2021):
	```
	conda install -c conda-forge pytest-cov
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-xdist">pytest-xdist</a></b> (🥇32 ·  ⭐ 720) - pytest plugin for distributed testing and loop-on-failures.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-xdist) (👨‍💻 74 · 🔀 150 · 📦 19K · 📋 430 - 45% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/pytest-dev/pytest-xdist
	```
- [PyPi](https://pypi.org/project/pytest-xdist) (📥 4.7M / month · 📦 7.3K · ⏱️ 16.06.2021):
	```
	pip install pytest-xdist
	```
- [Conda](https://anaconda.org/conda-forge/pytest-xdist) (📥 1.5M · ⏱️ 17.06.2021):
	```
	conda install -c conda-forge pytest-xdist
	```
</details>
<details><summary><b><a href="https://github.com/spulec/freezegun">freezegun</a></b> (🥈31 ·  ⭐ 2.9K · 📉) - Let your Python tests travel through time. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spulec/freezegun) (👨‍💻 94 · 🔀 200 · 📦 8.3K · 📋 230 - 28% open · ⏱️ 18.06.2021):

	```
	git clone https://github.com/spulec/freezegun
	```
- [PyPi](https://pypi.org/project/freezegun) (📥 4.4M / month · 📦 8.4K · ⏱️ 20.01.2021):
	```
	pip install freezegun
	```
- [Conda](https://anaconda.org/conda-forge/freezegun) (📥 230K · ⏱️ 20.01.2021):
	```
	conda install -c conda-forge freezegun
	```
</details>
<details><summary><b><a href="https://github.com/TheKevJames/coveralls-python">coveralls-python</a></b> (🥈31 ·  ⭐ 460) - Show coverage stats online via coveralls.io. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TheKevJames/coveralls-python) (👨‍💻 57 · 🔀 170 · 📦 18K · 📋 140 - 5% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/TheKevJames/coveralls-python
	```
- [PyPi](https://pypi.org/project/coveralls) (📥 540K / month · 📦 17K · ⏱️ 24.05.2021):
	```
	pip install coveralls
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥈30 ·  ⭐ 2.5K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 120 · 🔀 320 · 📋 480 - 28% open · ⏱️ 25.06.2021):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 1.7M / month · 📦 4.3K · ⏱️ 05.05.2018):
	```
	pip install factory_boy
	```
- [Conda](https://anaconda.org/conda-forge/factory_boy) (📥 73K · ⏱️ 04.04.2021):
	```
	conda install -c conda-forge factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-mock">pytest-mock</a></b> (🥈30 ·  ⭐ 1.1K · 📈) - Thin-wrapper around the mock package for easier use with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-mock) (👨‍💻 54 · 🔀 95 · 📦 17K · 📋 99 - 10% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/pytest-dev/pytest-mock
	```
- [PyPi](https://pypi.org/project/pytest-mock) (📥 4.2M / month · 📦 6.2K · ⏱️ 06.05.2021):
	```
	pip install pytest-mock
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mock) (📥 990K · ⏱️ 07.05.2021):
	```
	conda install -c conda-forge pytest-mock
	```
</details>
<details><summary><b><a href="https://github.com/asweigart/pyautogui">pyautogui</a></b> (🥈29 ·  ⭐ 5.2K) - A cross-platform GUI automation Python module for human beings. Used.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/asweigart/pyautogui) (👨‍💻 50 · 🔀 720 · 📦 8.6K · 📋 480 - 64% open · ⏱️ 18.04.2021):

	```
	git clone https://github.com/asweigart/pyautogui
	```
- [PyPi](https://pypi.org/project/pyautogui) (📥 410K / month · 📦 610 · ⏱️ 06.10.2020):
	```
	pip install pyautogui
	```
- [Conda](https://anaconda.org/conda-forge/pyautogui) (📥 130K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge pyautogui
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-asyncio">pytest-asyncio</a></b> (🥈29 ·  ⭐ 740) - Pytest support for asyncio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-asyncio) (👨‍💻 26 · 🔀 80 · 📦 13K · 📋 160 - 40% open · ⏱️ 30.05.2021):

	```
	git clone https://github.com/pytest-dev/pytest-asyncio
	```
- [PyPi](https://pypi.org/project/pytest-asyncio) (📥 1.7M / month · 📦 2K · ⏱️ 21.04.2021):
	```
	pip install pytest-asyncio
	```
- [Conda](https://anaconda.org/conda-forge/pytest-asyncio) (📥 470K · ⏱️ 21.05.2021):
	```
	conda install -c conda-forge pytest-asyncio
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-html">pytest-html</a></b> (🥈29 ·  ⭐ 430) - Plugin for generating HTML reports for pytest results. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-html) (👨‍💻 43 · 🔀 170 · 📦 11K · 📋 260 - 31% open · ⏱️ 23.01.2021):

	```
	git clone https://github.com/pytest-dev/pytest-html
	```
- [PyPi](https://pypi.org/project/pytest-html) (📥 1.5M / month · 📦 980 · ⏱️ 13.12.2020):
	```
	pip install pytest-html
	```
- [Conda](https://anaconda.org/conda-forge/pytest-html) (📥 140K · ⏱️ 13.12.2020):
	```
	conda install -c conda-forge pytest-html
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/playwright-python">playwright-python</a></b> (🥈28 ·  ⭐ 4.8K) - Python version of the Playwright testing and automation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/microsoft/playwright-python) (👨‍💻 21 · 🔀 410 · 📦 270 · 📋 370 - 4% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/microsoft/playwright-python
	```
- [PyPi](https://pypi.org/project/playwright) (📥 100K / month · ⏱️ 11.06.2021):
	```
	pip install playwright
	```
</details>
<details><summary><b><a href="https://github.com/lk-geimfari/mimesis">mimesis</a></b> (🥈28 ·  ⭐ 3.3K) - Mimesis is a high-performance fake data generator for Python, which.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lk-geimfari/mimesis) (👨‍💻 110 · 🔀 270 · 📥 160 · 📋 290 - 1% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/lk-geimfari/mimesis
	```
- [PyPi](https://pypi.org/project/mimesis) (📥 82K / month · 📦 84 · ⏱️ 21.12.2020):
	```
	pip install mimesis
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/pytest-benchmark">pytest-benchmark</a></b> (🥈27 ·  ⭐ 780) - py.test fixture for benchmarking code. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ionelmc/pytest-benchmark) (👨‍💻 33 · 🔀 83 · 📦 1.9K · 📋 150 - 49% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ionelmc/pytest-benchmark
	```
- [PyPi](https://pypi.org/project/pytest-benchmark) (📥 320K / month · 📦 730 · ⏱️ 17.04.2021):
	```
	pip install pytest-benchmark
	```
- [Conda](https://anaconda.org/conda-forge/pytest-benchmark) (📥 650K · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge pytest-benchmark
	```
</details>
<details><summary><b><a href="https://github.com/Teemu/pytest-sugar">pytest-sugar</a></b> (🥈27 ·  ⭐ 710 · 💤) - a plugin for py.test that changes the default look and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Teemu/pytest-sugar) (👨‍💻 36 · 🔀 52 · 📦 7.5K · 📋 100 - 33% open · ⏱️ 24.10.2020):

	```
	git clone https://github.com/Teemu/pytest-sugar
	```
- [PyPi](https://pypi.org/project/pytest-sugar) (📥 520K / month · 📦 4.6K · ⏱️ 06.07.2020):
	```
	pip install pytest-sugar
	```
- [Conda](https://anaconda.org/conda-forge/pytest-sugar) (📥 100K · ⏱️ 18.09.2020):
	```
	conda install -c conda-forge pytest-sugar
	```
</details>
<details><summary><b><a href="https://github.com/datadriventests/ddt">ddt</a></b> (🥈27 ·  ⭐ 390) - Data-Driven Tests for Python Unittest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datadriventests/ddt) (👨‍💻 34 · 🔀 96 · 📦 3.6K · 📋 47 - 36% open · ⏱️ 12.03.2021):

	```
	git clone https://github.com/datadriventests/ddt
	```
- [PyPi](https://pypi.org/project/ddt) (📥 300K / month · 📦 2.5K · ⏱️ 15.05.2020):
	```
	pip install ddt
	```
- [Conda](https://anaconda.org/conda-forge/ddt) (📥 60K · ⏱️ 15.05.2020):
	```
	conda install -c conda-forge ddt
	```
</details>
<details><summary><b><a href="https://github.com/CleanCut/green">green</a></b> (🥉26 ·  ⭐ 700) - Green is a clean, colorful, fast python test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CleanCut/green) (👨‍💻 37 · 🔀 74 · 📦 580 · 📋 170 - 3% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/CleanCut/green
	```
- [PyPi](https://pypi.org/project/green) (📥 17K / month · 📦 360 · ⏱️ 28.04.2021):
	```
	pip install green
	```
- [Conda](https://anaconda.org/conda-forge/green) (📥 81K · ⏱️ 12.11.2020):
	```
	conda install -c conda-forge green
	```
</details>
<details><summary><b><a href="https://github.com/nose-devs/nose2">nose2</a></b> (🥉26 ·  ⭐ 680) - The successor to nose, based on unittest2. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nose-devs/nose2) (👨‍💻 71 · 🔀 130 · 📦 3.8K · 📋 250 - 21% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/nose-devs/nose2
	```
- [PyPi](https://pypi.org/project/nose2) (📥 430K / month · 📦 1.9K · ⏱️ 27.01.2021):
	```
	pip install nose2
	```
- [Conda](https://anaconda.org/conda-forge/nose2) (📥 32K · ⏱️ 02.02.2020):
	```
	conda install -c conda-forge nose2
	```
</details>
<details><summary><b><a href="https://github.com/dbader/pytest-mypy">pytest-mypy</a></b> (🥉26 ·  ⭐ 190) - Mypy static type checker plugin for Pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dbader/pytest-mypy) (👨‍💻 15 · 🔀 31 · 📦 1.1K · 📋 43 - 20% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/dbader/pytest-mypy
	```
- [PyPi](https://pypi.org/project/pytest-mypy) (📥 260K / month · 📦 270 · ⏱️ 21.03.2021):
	```
	pip install pytest-mypy
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mypy) (📥 11K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge pytest-mypy
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-bdd">pytest-bdd</a></b> (🥉25 ·  ⭐ 840) - BDD library for the py.test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-bdd) (👨‍💻 40 · 🔀 140 · 📋 230 - 43% open · ⏱️ 29.04.2021):

	```
	git clone https://github.com/pytest-dev/pytest-bdd
	```
- [PyPi](https://pypi.org/project/pytest-bdd) (📥 190K / month · 📦 270 · ⏱️ 07.12.2020):
	```
	pip install pytest-bdd
	```
- [Conda](https://anaconda.org/conda-forge/pytest-bdd) (📥 32K · ⏱️ 03.02.2020):
	```
	conda install -c conda-forge pytest-bdd
	```
</details>
<details><summary><b><a href="https://github.com/airspeed-velocity/asv">asv</a></b> (🥉25 ·  ⭐ 600) - Airspeed Velocity: A simple Python benchmarking tool with web-based reporting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/airspeed-velocity/asv) (👨‍💻 54 · 🔀 130 · 📦 170 · 📋 410 - 26% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/airspeed-velocity/asv
	```
- [PyPi](https://pypi.org/project/asv) (📥 21K / month · 📦 88 · ⏱️ 16.05.2020):
	```
	pip install asv
	```
- [Conda](https://anaconda.org/conda-forge/asv) (📥 490K · ⏱️ 05.06.2021):
	```
	conda install -c conda-forge asv
	```
</details>
<details><summary><b><a href="https://github.com/hamcrest/PyHamcrest">PyHamcrest</a></b> (🥉25 ·  ⭐ 560) - Hamcrest matchers for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/hamcrest/PyHamcrest) (👨‍💻 34 · 🔀 84 · 📋 60 - 20% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/hamcrest/PyHamcrest
	```
- [PyPi](https://pypi.org/project/pyhamcrest) (📥 950K / month · 📦 3.4K · ⏱️ 02.03.2020):
	```
	pip install pyhamcrest
	```
- [Conda](https://anaconda.org/conda-forge/pyhamcrest) (📥 370K · ⏱️ 02.03.2020):
	```
	conda install -c conda-forge pyhamcrest
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-testinfra">pytest-testinfra</a></b> (🥉24 ·  ⭐ 1.9K) - Testinfra test your infrastructures. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-testinfra) (👨‍💻 100 · 🔀 270 · 📋 310 - 36% open · ⏱️ 20.06.2021):

	```
	git clone https://github.com/pytest-dev/pytest-testinfra
	```
- [PyPi](https://pypi.org/project/pytest-testinfra) (📥 84K / month · ⏱️ 20.06.2021):
	```
	pip install pytest-testinfra
	```
</details>
<details><summary><b><a href="https://github.com/xiaocong/uiautomator">uiautomator</a></b> (🥉24 ·  ⭐ 1.7K · 💤) - Python wrapper of Android uiautomator test tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xiaocong/uiautomator) (👨‍💻 13 · 🔀 590 · 📦 190 · 📋 290 - 59% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/xiaocong/uiautomator
	```
- [PyPi](https://pypi.org/project/uiautomator) (📥 16K / month · 📦 120 · ⏱️ 16.11.2020):
	```
	pip install uiautomator
	```
</details>
<details><summary><b><a href="https://github.com/nestorsalceda/mamba">Mamba Test Runner</a></b> (🥉24 ·  ⭐ 470 · 💤) - The definitive testing tool for Python. Born under the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nestorsalceda/mamba) (👨‍💻 22 · 🔀 64 · 📋 97 - 46% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/nestorsalceda/mamba
	```
- [PyPi](https://pypi.org/project/mamba) (📥 24K / month · 📦 220 · ⏱️ 16.11.2020):
	```
	pip install mamba
	```
</details>
<details><summary><b><a href="https://github.com/Erotemic/xdoctest">xdoctest</a></b> (🥉24 ·  ⭐ 96) - A rewrite of Python's builtin doctest module (with pytest plugin.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Erotemic/xdoctest) (👨‍💻 5 · 🔀 5 · 📦 1.1K · 📋 33 - 48% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/Erotemic/xdoctest
	```
- [PyPi](https://pypi.org/project/xdoctest) (📥 80K / month · 📦 52 · ⏱️ 28.06.2021):
	```
	pip install xdoctest
	```
</details>
<details><summary><b><a href="https://github.com/theacodes/nox">nox</a></b> (🥉23 ·  ⭐ 580) - Flexible test automation for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/theacodes/nox) (👨‍💻 59 · 🔀 95 · 📋 220 - 15% open · ⏱️ 20.06.2021):

	```
	git clone https://github.com/theacodes/nox
	```
- [PyPi](https://pypi.org/project/nox) (📥 370K / month · 📦 56 · ⏱️ 13.06.2021):
	```
	pip install nox
	```
- [Conda](https://anaconda.org/conda-forge/nox) (📥 32K · ⏱️ 20.06.2021):
	```
	conda install -c conda-forge nox
	```
</details>
<details><summary><b><a href="https://github.com/tarpas/pytest-testmon">pytest-testmon</a></b> (🥉23 ·  ⭐ 480) - Selects tests affected by changed files. Continous.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tarpas/pytest-testmon) (👨‍💻 16 · 🔀 28 · 📦 310 · 📋 110 - 25% open · ⏱️ 30.04.2021):

	```
	git clone https://github.com/tarpas/pytest-testmon
	```
- [PyPi](https://pypi.org/project/pytest-testmon) (📥 75K / month · 📦 98 · ⏱️ 28.04.2021):
	```
	pip install pytest-testmon
	```
- [Conda](https://anaconda.org/conda-forge/pytest-testmon) (📥 31K · ⏱️ 03.08.2019):
	```
	conda install -c conda-forge pytest-testmon
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-randomly">pytest-randomly</a></b> (🥉23 ·  ⭐ 330) - Pytest plugin to randomly order tests and control random.seed. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-randomly) (👨‍💻 15 · 🔀 22 · 📋 43 - 16% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/pytest-dev/pytest-randomly
	```
- [PyPi](https://pypi.org/project/pytest-randomly) (📥 340K / month · 📦 210 · ⏱️ 10.05.2021):
	```
	pip install pytest-randomly
	```
</details>
<details><summary><b><a href="https://github.com/sixpack/sixpack">sixpack</a></b> (🥉22 ·  ⭐ 1.7K · 💤) - Sixpack is a language-agnostic a/b-testing framework. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/sixpack/sixpack) (👨‍💻 56 · 🔀 180 · 📦 8 · 📋 210 - 41% open · ⏱️ 26.08.2020):

	```
	git clone https://github.com/sixpack/sixpack
	```
- [PyPi](https://pypi.org/project/sixpack) (📥 280 / month · 📦 4 · ⏱️ 22.11.2017):
	```
	pip install sixpack
	```
</details>
<details><summary><b><a href="https://github.com/avast/pytest-docker">pytest-docker</a></b> (🥉21 ·  ⭐ 210) - Docker-based integration tests. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/avast/pytest-docker) (👨‍💻 11 · 🔀 40 · 📥 66 · 📋 31 - 54% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/avast/pytest-docker
	```
- [PyPi](https://pypi.org/project/pytest-docker) (📥 32K / month · 📦 28 · ⏱️ 14.06.2021):
	```
	pip install pytest-docker
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/nose-devs/nose">nose</a></b> (🥈31 ·  ⭐ 1.3K · 💀) - nose is nicer testing for python. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1%2B">❗️LGPL-2.1+</a></code>
- <b><a href="https://github.com/joeyespo/pytest-watch">pytest-watch</a></b> (🥉24 ·  ⭐ 570 · 💀) - Local continuous test runner with pytest and watchdog. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ActivisionGameScience/assertpy">assertpy</a></b> (🥉21 ·  ⭐ 250 · 💀) - Simple assertion library for unit testing in python with a fluent.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/TvoroG/pytest-lazy-fixture">pytest-lazy-fixture</a></b> (🥉21 ·  ⭐ 190 · 💀) - It helps to use fixtures in pytest.mark.parametrize. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/gabrielcnr/pytest-datadir">pytest-datadir</a></b> (🥉20 ·  ⭐ 140 · 💀) - pytest plugin for manipulating test data directories and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/emirozer/fake2db">fake2db</a></b> (🥉18 ·  ⭐ 2.1K · 💀) - create custom test databases that are populated with fake data. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/pytest-dev/pytest-play">pytest-play</a></b> (🥉16 ·  ⭐ 63 · 💀) - pytest plugin that let you automate actions and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/man-group/pytest-plugins">pytest-plugins</a></b> (🥉13 ·  ⭐ 380 · 💀) - A grab-bag of nifty pytest plugins. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Code Packaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://packaging.python.org/overview/">Python.org Packaging</a></b>  - An Overview of Packaging for Python.

<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">pyinstaller</a></b> (🥇34 ·  ⭐ 8.2K) - Freeze (package) Python programs into stand-alone executables. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 400 · 🔀 1.7K · 📥 710K · 📦 18K · 📋 4.2K - 8% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
- [PyPi](https://pypi.org/project/pyinstaller) (📥 570K / month · ⏱️ 17.04.2021):
	```
	pip install pyinstaller
	```
- [Conda](https://anaconda.org/conda-forge/pyinstaller) (📥 240K · ⏱️ 21.04.2021):
	```
	conda install -c conda-forge pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/pypa/packaging">packaging</a></b> (🥇30 ·  ⭐ 310) - Core utilities for Python packages. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pypa/packaging) (👨‍💻 70 · 🔀 150 · 📥 100 · 📦 220K · 📋 200 - 26% open · ⏱️ 19.06.2021):

	```
	git clone https://github.com/pypa/packaging
	```
- [PyPi](https://pypi.org/project/packaging) (📥 59M / month · 📦 29K · ⏱️ 29.01.2021):
	```
	pip install packaging
	```
- [Conda](https://anaconda.org/conda-forge/packaging) (📥 8M · ⏱️ 04.02.2021):
	```
	conda install -c conda-forge packaging
	```
</details>
<details><summary><b><a href="https://github.com/Nuitka/Nuitka">Nuitka</a></b> (🥈27 ·  ⭐ 5.4K) - Nuitka is a Python compiler written in Python. It's fully compatible.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Nuitka/Nuitka) (👨‍💻 98 · 🔀 310 · 📋 940 - 21% open · ⏱️ 25.06.2021):

	```
	git clone https://github.com/Nuitka/Nuitka
	```
- [PyPi](https://pypi.org/project/nuitka) (📥 27K / month · 📦 54 · ⏱️ 01.07.2021):
	```
	pip install nuitka
	```
- [Conda](https://anaconda.org/conda-forge/nuitka) (📥 290K · ⏱️ 25.06.2021):
	```
	conda install -c conda-forge nuitka
	```
</details>
<details><summary><b><a href="https://github.com/pantsbuild/pex">pex</a></b> (🥈26 ·  ⭐ 1.9K) - A library and tool for generating .pex (Python EXecutable) files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pantsbuild/pex) (👨‍💻 99 · 🔀 200 · 📥 330K · 📋 690 - 19% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/pantsbuild/pex
	```
- [PyPi](https://pypi.org/project/pex) (📥 130K / month · 📦 230 · ⏱️ 29.04.2021):
	```
	pip install pex
	```
</details>
<details><summary><b><a href="https://github.com/beeware/briefcase">briefcase</a></b> (🥈25 ·  ⭐ 1.2K · ➕) - Tools to support converting a Python project into a standalone.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/beeware/briefcase) (👨‍💻 82 · 🔀 190 · 📋 330 - 31% open · ⏱️ 07.06.2021):

	```
	git clone https://github.com/beeware/briefcase
	```
- [PyPi](https://pypi.org/project/briefcase) (📥 2.5K / month · 📦 24 · ⏱️ 06.03.2021):
	```
	pip install briefcase
	```
</details>
<details><summary><b><a href="https://github.com/py2exe/py2exe">py2exe</a></b> (🥈24 ·  ⭐ 240) - A distutils extension to create standalone Windows programs from Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py2exe/py2exe) (👨‍💻 14 · 🔀 37 · 📥 9.7K · 📦 1.2K · 📋 73 - 6% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/py2exe/py2exe
	```
- [PyPi](https://pypi.org/project/py2exe) (📥 22K / month · 📦 350 · ⏱️ 24.04.2021):
	```
	pip install py2exe
	```
</details>
<details><summary><b><a href="https://github.com/ronaldoussoren/py2app">py2app</a></b> (🥈24 ·  ⭐ 140) - py2app is a Python setuptools command which will allow you to make.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ronaldoussoren/py2app) (👨‍💻 24 · 🔀 9 · 📦 3.7K · 📋 350 - 43% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/ronaldoussoren/py2app
	```
- [PyPi](https://pypi.org/project/py2app) (📥 12K / month · 📦 1.6K · ⏱️ 06.04.2021):
	```
	pip install py2app
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉22 ·  ⭐ 1.2K) - shiv is a command line utility for building fully self contained Python.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 33 · 🔀 69 · 📥 140 · 📋 87 - 31% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/linkedin/shiv
	```
- [PyPi](https://pypi.org/project/shiv) (📥 8.2K / month · 📦 10 · ⏱️ 30.04.2021):
	```
	pip install shiv
	```
</details>
<details><summary><b><a href="https://github.com/marcelotduarte/cx_Freeze">cx_Freeze</a></b> (🥉22 ·  ⭐ 730) - Create standalone executables from Python scripts, with the same.. <code><a href="http://bit.ly/35wkF7y">Python-2.0</a></code></summary>

- [GitHub](https://github.com/marcelotduarte/cx_Freeze) (👨‍💻 90 · 🔀 160 · 📋 660 - 9% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/marcelotduarte/cx_Freeze
	```
- [PyPi](https://pypi.org/project/cx_freeze) (📥 43K / month · 📦 150 · ⏱️ 16.12.2017):
	```
	pip install cx_freeze
	```
- [Conda](https://anaconda.org/conda-forge/cx_freeze) (📥 79K · ⏱️ 17.04.2021):
	```
	conda install -c conda-forge cx_freeze
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/pynsist">pynsist</a></b> (🥉22 ·  ⭐ 710) - Build Windows installers for Python applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/takluyver/pynsist) (👨‍💻 28 · 🔀 100 · 📋 160 - 16% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/takluyver/pynsist
	```
- [PyPi](https://pypi.org/project/pynsist) (📥 6.7K / month · 📦 88 · ⏱️ 28.03.2021):
	```
	pip install pynsist
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/xar">xar</a></b> (🥉20 ·  ⭐ 1.5K) - executable archive format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/facebookincubator/xar) (👨‍💻 22 · 🔀 45 · 📦 15 · 📋 29 - 27% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/facebookincubator/xar
	```
- [PyPi](https://pypi.org/project/xar) (📥 200 / month · ⏱️ 02.12.2020):
	```
	pip install xar
	```
</details>
<details><summary><b><a href="https://github.com/conda/constructor">constructor</a></b> (🥉19 ·  ⭐ 310) - tool for creating installers from conda packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/constructor) (👨‍💻 46 · 🔀 120 · 📥 220 · 📦 9 · 📋 240 - 17% open · ⏱️ 24.05.2021):

	```
	git clone https://github.com/conda/constructor
	```
- [Conda](https://anaconda.org/anaconda/constructor) (📥 4.2K · ⏱️ 01.04.2021):
	```
	conda install -c anaconda constructor
	```
</details>
<details><summary><b><a href="https://github.com/indygreg/PyOxidizer">PyOxidizer</a></b> (🥉15 ·  ⭐ 3.1K) - A modern Python application packaging and distribution tool. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/indygreg/PyOxidizer) (👨‍💻 34 · 🔀 110 · 📥 360 · 📋 340 - 58% open · ⏱️ 06.06.2021):

	```
	git clone https://github.com/indygreg/PyOxidizer
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/google/subpar">subpar</a></b> (🥉13 ·  ⭐ 480 · 💀) - Subpar is a utility for creating self-contained python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jamesabel/pyship">pyship</a></b> (🥉11 ·  ⭐ 12) - pyship - ship Python desktop apps to end users. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Build Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/setuptools">setuptools</a></b> (🥇34 ·  ⭐ 1.4K) - Official project repository for the Setuptools build system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools) (👨‍💻 440 · 🔀 730 · 📥 110 · 📦 110K · 📋 1.8K - 30% open · ⏱️ 29.05.2021):

	```
	git clone https://github.com/pypa/setuptools
	```
- [PyPi](https://pypi.org/project/setuptools) (📥 97M / month · 📦 58K · ⏱️ 23.05.2021):
	```
	pip install setuptools
	```
- [Conda](https://anaconda.org/conda-forge/setuptools) (📥 23M · ⏱️ 28.06.2021):
	```
	conda install -c conda-forge setuptools
	```
</details>
<details><summary><b><a href="https://github.com/buildbot/buildbot">buildbot</a></b> (🥇31 ·  ⭐ 4.6K) - Python-based continuous integration testing framework; your pull.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/buildbot/buildbot) (👨‍💻 790 · 🔀 1.5K · 📥 15K · 📦 250 · 📋 1.3K - 48% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/buildbot/buildbot
	```
- [PyPi](https://pypi.org/project/buildbot) (📥 57K / month · 📦 890 · ⏱️ 19.06.2021):
	```
	pip install buildbot
	```
- [Conda](https://anaconda.org/conda-forge/buildbot) (📥 36K · ⏱️ 19.06.2021):
	```
	conda install -c conda-forge buildbot
	```
</details>
<details><summary><b><a href="https://github.com/pyinvoke/invoke">invoke</a></b> (🥇31 ·  ⭐ 3.3K) - Pythonic task management & command execution. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pyinvoke/invoke) (👨‍💻 56 · 🔀 280 · 📦 8.1K · 📋 660 - 45% open · ⏱️ 06.06.2021):

	```
	git clone https://github.com/pyinvoke/invoke
	```
- [PyPi](https://pypi.org/project/invoke) (📥 1.6M / month · 📦 4.6K · ⏱️ 31.12.2020):
	```
	pip install invoke
	```
- [Conda](https://anaconda.org/conda-forge/invoke) (📥 340K · ⏱️ 06.01.2021):
	```
	conda install -c conda-forge invoke
	```
</details>
<details><summary><b><a href="https://github.com/pypa/wheel">wheel</a></b> (🥇31 ·  ⭐ 250) - The official binary distribution format for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/wheel) (👨‍💻 61 · 🔀 89 · 📋 320 - 7% open · ⏱️ 23.05.2021):

	```
	git clone https://github.com/pypa/wheel
	```
- [PyPi](https://pypi.org/project/wheel) (📥 77M / month · 📦 63K · ⏱️ 13.12.2020):
	```
	pip install wheel
	```
- [Conda](https://anaconda.org/conda-forge/wheel) (📥 18M · ⏱️ 13.12.2020):
	```
	conda install -c conda-forge wheel
	```
</details>
<details><summary><b><a href="https://github.com/pypa/twine">twine</a></b> (🥈30 ·  ⭐ 1.1K) - Utilities for interacting with PyPI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pypa/twine) (👨‍💻 100 · 🔀 240 · 📦 42K · 📋 360 - 12% open · ⏱️ 19.06.2021):

	```
	git clone https://github.com/pypa/twine
	```
- [PyPi](https://pypi.org/project/twine) (📥 1.8M / month · 📦 18K · ⏱️ 15.03.2021):
	```
	pip install twine
	```
- [Conda](https://anaconda.org/conda-forge/twine) (📥 290K · ⏱️ 17.03.2021):
	```
	conda install -c conda-forge twine
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/flit">flit</a></b> (🥉27 ·  ⭐ 1.4K) - Simplified packaging of Python modules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/flit) (👨‍💻 42 · 🔀 74 · 📋 240 - 34% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/takluyver/flit
	```
- [PyPi](https://pypi.org/project/flit) (📥 80K / month · 📦 230 · ⏱️ 01.03.2021):
	```
	pip install flit
	```
- [Conda](https://anaconda.org/conda-forge/flit) (📥 86K · ⏱️ 22.03.2021):
	```
	conda install -c conda-forge flit
	```
</details>
<details><summary><b><a href="https://github.com/SCons/scons">scons</a></b> (🥉27 ·  ⭐ 1.2K) - SCons - a software construction tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SCons/scons) (👨‍💻 130 · 🔀 210 · 📥 360 · 📋 3.3K - 20% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/SCons/scons
	```
- [PyPi](https://pypi.org/project/scons) (📥 170K / month · 📦 50 · ⏱️ 17.12.2019):
	```
	pip install scons
	```
- [Conda](https://anaconda.org/conda-forge/scons) (📥 200K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge scons
	```
</details>
<details><summary><b><a href="https://github.com/pydoit/doit">doit</a></b> (🥉27 ·  ⭐ 1K) - task management & automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydoit/doit) (👨‍💻 56 · 🔀 120 · 📦 720 · 📋 260 - 25% open · ⏱️ 14.05.2021):

	```
	git clone https://github.com/pydoit/doit
	```
- [PyPi](https://pypi.org/project/doit) (📥 220K / month · 📦 470 · ⏱️ 04.09.2020):
	```
	pip install doit
	```
- [Conda](https://anaconda.org/conda-forge/doit) (📥 59K · ⏱️ 11.10.2020):
	```
	conda install -c conda-forge doit
	```
</details>
<details><summary><b><a href="https://github.com/pybuilder/pybuilder">pybuilder</a></b> (🥉26 ·  ⭐ 1.3K · 💤) - Software build automation tool for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pybuilder/pybuilder) (👨‍💻 35 · 🔀 230 · 📋 480 - 18% open · ⏱️ 18.10.2020):

	```
	git clone https://github.com/pybuilder/pybuilder
	```
- [PyPi](https://pypi.org/project/pybuilder) (📥 19K / month · 📦 110 · ⏱️ 07.05.2021):
	```
	pip install pybuilder
	```
</details>
<details><summary><b><a href="https://github.com/pypa/setuptools_scm">setuptools_scm</a></b> (🥉25 ·  ⭐ 470) - the blessed package to manage your versions by scm tags. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools_scm) (👨‍💻 87 · 🔀 140 · 📋 340 - 21% open · ⏱️ 25.06.2021):

	```
	git clone https://github.com/pypa/setuptools_scm
	```
- [PyPi](https://pypi.org/project/setuptools_scm) (📥 12M / month · 📦 690 · ⏱️ 09.08.2018):
	```
	pip install setuptools_scm
	```
- [Conda](https://anaconda.org/conda-forge/setuptools_scm) (📥 680K · ⏱️ 17.03.2021):
	```
	conda install -c conda-forge setuptools_scm
	```
</details>
<details><summary><b><a href="https://github.com/paver/paver">paver</a></b> (🥉25 ·  ⭐ 440) - Python-based project scripting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/paver/paver) (👨‍💻 45 · 🔀 78 · 📋 130 - 28% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/paver/paver
	```
- [PyPi](https://pypi.org/project/paver) (📥 31K / month · 📦 1.9K · ⏱️ 31.12.2017):
	```
	pip install paver
	```
- [Conda](https://anaconda.org/conda-forge/paver) (📥 22K · ⏱️ 24.07.2018):
	```
	conda install -c conda-forge paver
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/universal-build">universal-build</a></b> (🥉12 ·  ⭐ 12) - Universal build utilities for containerized build pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/universal-build) (👨‍💻 4 · 🔀 3 · 📥 15 · ⏱️ 19.04.2021):

	```
	git clone https://github.com/ml-tooling/universal-build
	```
- [PyPi](https://pypi.org/project/universal-build) (📥 310 / month · ⏱️ 12.12.2020):
	```
	pip install universal-build
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/buildout/buildout">buildout</a></b> (🥈28 ·  ⭐ 510) - Buildout is a deployment automation tool written in and extended.. <code><a href="https://tldrlegal.com/search?q=ZPL-2.1">❗️ZPL-2.1</a></code>
- <b><a href="https://github.com/rags/pynt">pynt</a></b> (🥉18 ·  ⭐ 150 · 💀) - A pynt of Python build. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## System Monitoring & Profiling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/giampaolo/psutil">psutil</a></b> (🥇35 ·  ⭐ 7.4K) - Cross-platform lib for process and system monitoring in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/giampaolo/psutil) (👨‍💻 160 · 🔀 1.1K · 📦 92K · 📋 1.5K - 12% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/giampaolo/psutil
	```
- [PyPi](https://pypi.org/project/psutil) (📥 24M / month · 📦 25K · ⏱️ 19.12.2020):
	```
	pip install psutil
	```
- [Conda](https://anaconda.org/conda-forge/psutil) (📥 7.2M · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge psutil
	```
</details>
<details><summary><b><a href="https://github.com/nicolargo/glances">Glances</a></b> (🥇30 ·  ⭐ 19K) - Glances an Eye on your system. A top/htop alternative for.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/nicolargo/glances) (👨‍💻 140 · 🔀 1.2K · 📥 430 · 📦 310 · 📋 1.4K - 14% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/nicolargo/glances
	```
- [PyPi](https://pypi.org/project/glances) (📥 120K / month · 📦 50 · ⏱️ 02.05.2021):
	```
	pip install glances
	```
- [Conda](https://anaconda.org/conda-forge/glances) (📥 140K · ⏱️ 07.06.2021):
	```
	conda install -c conda-forge glances
	```
</details>
<details><summary><b><a href="https://github.com/benfred/py-spy">py-spy</a></b> (🥇30 ·  ⭐ 7.1K) - Sampling profiler for Python programs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/py-spy) (👨‍💻 26 · 🔀 250 · 📥 5.5K · 📦 910 · 📋 210 - 28% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/benfred/py-spy
	```
- [PyPi](https://pypi.org/project/py-spy) (📥 710K / month · 📦 50 · ⏱️ 16.05.2021):
	```
	pip install py-spy
	```
</details>
<details><summary><b><a href="https://github.com/pyutils/line_profiler">line_profiler</a></b> (🥈28 ·  ⭐ 3.5K) - Line-by-line profiling for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyutils/line_profiler) (👨‍💻 25 · 🔀 250 · 📋 45 - 73% open · ⏱️ 25.06.2021):

	```
	git clone https://github.com/pyutils/line_profiler
	```
- [PyPi](https://pypi.org/project/line_profiler) (📥 320K / month · 📦 690 · ⏱️ 20.12.2017):
	```
	pip install line_profiler
	```
- [Conda](https://anaconda.org/conda-forge/line_profiler) (📥 190K · ⏱️ 05.06.2021):
	```
	conda install -c conda-forge line_profiler
	```
</details>
<details><summary><b><a href="https://github.com/pythonprofilers/memory_profiler">memory-profiler</a></b> (🥈28 ·  ⭐ 3K) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pythonprofilers/memory_profiler) (👨‍💻 88 · 🔀 310 · 📋 190 - 47% open · ⏱️ 12.06.2021):

	```
	git clone https://github.com/pythonprofilers/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📥 470K / month · 📦 530 · ⏱️ 16.08.2018):
	```
	pip install memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/joerick/pyinstrument">pyinstrument</a></b> (🥈27 ·  ⭐ 2.8K) - Call stack profiler for Python. Shows you why your code is slow!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joerick/pyinstrument) (👨‍💻 29 · 🔀 110 · 📦 280 · 📋 83 - 27% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/joerick/pyinstrument
	```
- [PyPi](https://pypi.org/project/pyinstrument) (📥 160K / month · 📦 140 · ⏱️ 03.05.2021):
	```
	pip install pyinstrument
	```
- [Conda](https://anaconda.org/conda-forge/pyinstrument) (📥 74K · ⏱️ 03.05.2021):
	```
	conda install -c conda-forge pyinstrument
	```
</details>
<details><summary><b><a href="https://github.com/sumerc/yappi">Yappi</a></b> (🥈26 ·  ⭐ 660) - Yet Another Python Profiler, but this time thread&coroutine&greenlet aware. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sumerc/yappi) (👨‍💻 24 · 🔀 47 · 📦 430 · 📋 46 - 30% open · ⏱️ 01.06.2021):

	```
	git clone https://github.com/sumerc/yappi
	```
- [PyPi](https://pypi.org/project/yappi) (📥 150K / month · 📦 640 · ⏱️ 27.11.2020):
	```
	pip install yappi
	```
- [Conda](https://anaconda.org/conda-forge/yappi) (📥 82K · ⏱️ 28.11.2020):
	```
	conda install -c conda-forge yappi
	```
</details>
<details><summary><b><a href="https://github.com/pympler/pympler">pympler</a></b> (🥉25 ·  ⭐ 790 · 💤) - Development tool to measure, monitor and analyze the memory.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pympler/pympler) (👨‍💻 26 · 🔀 67 · 📋 78 - 41% open · ⏱️ 15.10.2020):

	```
	git clone https://github.com/pympler/pympler
	```
- [PyPi](https://pypi.org/project/pympler) (📥 220K / month · 📦 480 · ⏱️ 14.10.2020):
	```
	pip install pympler
	```
- [Conda](https://anaconda.org/conda-forge/pympler) (📥 170K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge pympler
	```
</details>
<details><summary><b><a href="https://github.com/plasma-umass/scalene">Scalene</a></b> (🥉24 ·  ⭐ 4.1K) - Scalene: a high-performance, high-precision CPU, GPU, and memory.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/plasma-umass/scalene) (👨‍💻 19 · 🔀 140 · 📦 46 · 📋 120 - 21% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/plasma-umass/scalene
	```
- [PyPi](https://pypi.org/project/scalene) (📥 5.8K / month · ⏱️ 29.06.2021):
	```
	pip install scalene
	```
</details>
<details><summary><b><a href="https://github.com/aristocratos/bpytop">Bpytop</a></b> (🥉23 ·  ⭐ 6.7K) - Linux/OSX/FreeBSD resource monitor. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aristocratos/bpytop) (👨‍💻 30 · 🔀 260 · 📋 240 - 16% open · ⏱️ 07.06.2021):

	```
	git clone https://github.com/aristocratos/bpytop
	```
- [PyPi](https://pypi.org/project/bpytop) (📥 11K / month · ⏱️ 07.06.2021):
	```
	pip install bpytop
	```
</details>
<details><summary><b><a href="https://github.com/nvdv/vprof">vprof</a></b> (🥉22 ·  ⭐ 3.7K) - Visual profiler for Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/nvdv/vprof) (👨‍💻 17 · 🔀 160 · 📦 73 · 📋 80 - 30% open · ⏱️ 20.02.2021):

	```
	git clone https://github.com/nvdv/vprof
	```
- [PyPi](https://pypi.org/project/vprof) (📥 3.1K / month · 📦 18 · ⏱️ 29.02.2020):
	```
	pip install vprof
	```
</details>
<details><summary><b><a href="https://github.com/what-studio/profiling">Profiling</a></b> (🥉20 ·  ⭐ 3K · 💤) - Was an interactive continuous Python profiler. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/what-studio/profiling) (👨‍💻 18 · 🔀 110 · 📦 35 · 📋 35 - 42% open · ⏱️ 24.08.2020):

	```
	git clone https://github.com/what-studio/profiling
	```
- [PyPi](https://pypi.org/project/profiling) (📥 3.7K / month · 📦 5 · ⏱️ 28.06.2017):
	```
	pip install profiling
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/python-diamond/Diamond">Diamond</a></b> (🥈26 ·  ⭐ 1.6K · 💀) - Diamond is a python daemon that collects system metrics and publishes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/fabianp/memory_profiler">memory_profiler</a></b> (🥉23 ·  ⭐ 63 · 💀) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/csurfer/pyheat">pyheat</a></b> (🥉18 ·  ⭐ 510 · 💀) - pprofile + matplotlib = Python program profiled as an awesome heatmap!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/alexmojaki/heartrate">heartrate</a></b> (🥉17 ·  ⭐ 1.3K · 💀) - Simple real time visualisation of the execution of a Python program. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/agermanidis/livepython">livepython</a></b> (🥉12 ·  ⭐ 2.5K · 💀) - Visually trace Python code in real-time. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## AST Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python/typed_ast">typed_ast</a></b> (🥇29 ·  ⭐ 180) - Modified fork of CPython's ast module that parses `# type:`.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python/typed_ast) (👨‍💻 21 · 🔀 48 · 📋 80 - 6% open · ⏱️ 12.04.2021):

	```
	git clone https://github.com/python/typed_ast
	```
- [PyPi](https://pypi.org/project/typed_ast) (📥 19M / month · 📦 10K · ⏱️ 11.04.2021):
	```
	pip install typed_ast
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/gast">gast</a></b> (🥈28 ·  ⭐ 110 · 📈) - Python AST that abstracts the underlying Python version. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/gast) (👨‍💻 10 · 🔀 22 · 📦 60K · 📋 23 - 8% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/serge-sans-paille/gast
	```
- [PyPi](https://pypi.org/project/gast) (📥 8.4M / month · 📦 3.4K · ⏱️ 28.06.2021):
	```
	pip install gast
	```
- [Conda](https://anaconda.org/conda-forge/gast) (📥 1.1M · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge gast
	```
</details>
<details><summary><b><a href="https://github.com/berkerpeksag/astor">astor</a></b> (🥉27 ·  ⭐ 590) - Python AST read/write. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/berkerpeksag/astor) (👨‍💻 31 · 🔀 81 · 📋 110 - 32% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/berkerpeksag/astor
	```
- [PyPi](https://pypi.org/project/astor) (📥 3.8M / month · 📦 3.8K · ⏱️ 10.12.2019):
	```
	pip install astor
	```
- [Conda](https://anaconda.org/conda-forge/astor) (📥 1.2M · ⏱️ 01.07.2020):
	```
	conda install -c conda-forge astor
	```
</details>
<details><summary><b><a href="https://github.com/newville/asteval">asteval</a></b> (🥉24 ·  ⭐ 120) - minimalistic evaluator of python expression using ast module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/newville/asteval) (👨‍💻 18 · 🔀 32 · 📦 580 · 📋 50 - 12% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/newville/asteval
	```
- [PyPi](https://pypi.org/project/asteval) (📥 140K / month · 📦 240 · ⏱️ 22.06.2021):
	```
	pip install asteval
	```
- [Conda](https://anaconda.org/conda-forge/asteval) (📥 130K · ⏱️ 27.02.2021):
	```
	conda install -c conda-forge asteval
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/simonpercivall/astunparse">astunparse</a></b> (🥈28 ·  ⭐ 160 · 💀) - An AST unparser for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pre-commit/pre-commit">pre-commit</a></b> (🥇32 ·  ⭐ 6.2K) - A framework for managing and maintaining multi-language pre-commit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pre-commit/pre-commit) (👨‍💻 120 · 🔀 450 · 📥 7.6K · 📋 1.2K - 1% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/pre-commit/pre-commit
	```
- [PyPi](https://pypi.org/project/pre-commit) (📥 3.3M / month · 📦 2.1K · ⏱️ 21.05.2021):
	```
	pip install pre-commit
	```
- [Conda](https://anaconda.org/conda-forge/pre-commit) (📥 600K · ⏱️ 27.05.2021):
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
