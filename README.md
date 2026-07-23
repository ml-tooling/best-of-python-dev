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
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-270-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-python-dev/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-python-dev?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 270 awesome open-source projects with a total of 1.1M stars grouped into 17 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-python-dev/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-python-dev/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-python-dev/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Linters & Style Checkers](#linters--style-checkers) _40 projects_
- [Type checkers](#type-checkers) _5 projects_
- [Code Formatters](#code-formatters) _7 projects_
- [Code Refactoring](#code-refactoring) _18 projects_
- [Code Security](#code-security) _8 projects_
- [Virtual Environments](#virtual-environments) _10 projects_
- [Dependency & Package Managers](#dependency--package-managers) _11 projects_
- [Code Metrics & Complexity](#code-metrics--complexity) _6 projects_
- [Logging](#logging) _21 projects_
- [Shell](#shell) _2 projects_
- [Documentation](#documentation) _28 projects_
- [Debugging Tools](#debugging-tools) _13 projects_
- [Testing Tools](#testing-tools) _43 projects_
- [Code Packaging](#code-packaging) _16 projects_
- [Build Tools](#build-tools) _14 projects_
- [System Monitoring & Profiling](#system-monitoring--profiling) _18 projects_
- [AST Tools](#ast-tools) _6 projects_
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

<details><summary><b><a href="https://docs.astral.sh/ruff">ruff</a></b> (🥇35 ·  ⭐ 49K · 📉) - An extremely fast Python linter and code formatter, written in Rust. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub]() (👨‍💻 930 · 🔀 2.2K · 📦 220K):

	```
	git clone https://github.com/charliermarsh/ruff
	```
- [PyPi](https://pypi.org/project/ruff) (📥 290M / month · 📦 79K · ⏱️ 16.07.2026):
	```
	pip install ruff
	```
- [Conda](https://anaconda.org/conda-forge/ruff) (📥 7.8M · ⏱️ 16.07.2026):
	```
	conda install -c conda-forge ruff
	```
</details>
<details><summary><b><a href="https://github.com/pylint-dev/pylint">pylint</a></b> (🥇33 ·  ⭐ 5.7K) - python code static checker. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub]() (👨‍💻 660 · 🔀 1.3K · 📦 490K):

	```
	git clone https://github.com/PyCQA/pylint
	```
- [PyPi](https://pypi.org/project/pylint) (📥 69M / month · 📦 13K · ⏱️ 14.06.2026):
	```
	pip install pylint
	```
- [Conda](https://anaconda.org/conda-forge/pylint) (📥 8.4M · ⏱️ 14.06.2026):
	```
	conda install -c conda-forge pylint
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8">flake8</a></b> (🥇33 ·  ⭐ 3.8K) - Flake8 is a wrapper around these tools: PyFlakes; pycodestyle; Ned.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/flake8) (👨‍💻 180 · 🔀 350 · 📦 690K):

	```
	git clone https://github.com/PyCQA/flake8
	```
- [PyPi](https://pypi.org/project/flake8) (📥 56M / month · 📦 27K · ⏱️ 20.06.2025):
	```
	pip install flake8
	```
- [Conda](https://anaconda.org/conda-forge/flake8) (📥 11M · ⏱️ 26.06.2025):
	```
	conda install -c conda-forge flake8
	```
</details>
<details><summary><b><a href="https://github.com/davidhalter/parso">parso</a></b> (🥇31 ·  ⭐ 670) - A Python Parser. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/parso) (👨‍💻 52 · 🔀 120 · 📦 600K):

	```
	git clone https://github.com/davidhalter/parso
	```
- [PyPi](https://pypi.org/project/parso) (📥 130M / month · 📦 1.2K · ⏱️ 01.05.2026):
	```
	pip install parso
	```
- [Conda](https://anaconda.org/conda-forge/parso) (📥 39M · ⏱️ 02.05.2026):
	```
	conda install -c conda-forge parso
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/wemake-python-styleguide">wemake-python-styleguide</a></b> (🥈29 ·  ⭐ 2.9K) - The strictest and most opinionated python linter ever!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-python-styleguide) (👨‍💻 220 · 🔀 420 · 📦 18K):

	```
	git clone https://github.com/wemake-services/wemake-python-styleguide
	```
- [PyPi](https://pypi.org/project/wemake-python-styleguide) (📥 280K / month · 📦 130 · ⏱️ 27.04.2026):
	```
	pip install wemake-python-styleguide
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-bugbear">flake8-bugbear</a></b> (🥈28 ·  ⭐ 1.1K) - A plugin for Flake8 finding likely bugs and design problems.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-bugbear) (👨‍💻 93 · 🔀 120 · 📦 43K):

	```
	git clone https://github.com/PyCQA/flake8-bugbear
	```
- [PyPi](https://pypi.org/project/flake8-bugbear) (📥 4.7M / month · 📦 1.5K · ⏱️ 29.11.2025):
	```
	pip install flake8-bugbear
	```
- [Conda](https://anaconda.org/conda-forge/flake8-bugbear) (📥 920K · ⏱️ 02.12.2025):
	```
	conda install -c conda-forge flake8-bugbear
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pycodestyle">pycodestyle</a></b> (🥈27 ·  ⭐ 5.2K · 💤) - Simple Python style checker in one Python file. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pycodestyle) (👨‍💻 140 · 🔀 750):

	```
	git clone https://github.com/PyCQA/pycodestyle
	```
- [PyPi](https://pypi.org/project/pycodestyle) (📥 86M / month · 📦 2.2K · ⏱️ 20.06.2025):
	```
	pip install pycodestyle
	```
- [Conda](https://anaconda.org/conda-forge/pycodestyle) (📥 11M · ⏱️ 22.06.2025):
	```
	conda install -c conda-forge pycodestyle
	```
</details>
<details><summary><b><a href="https://github.com/beartype/beartype">beartype</a></b> (🥈27 ·  ⭐ 3.4K) - Unbearably fast near-real-time pure-Python runtime-static type-checker. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beartype/beartype) (👨‍💻 33 · 🔀 72 · 📦 13K):

	```
	git clone https://github.com/beartype/beartype
	```
- [PyPi](https://pypi.org/project/beartype) (📥 98M / month · 📦 900 · ⏱️ 13.12.2025):
	```
	pip install beartype
	```
- [Conda](https://anaconda.org/conda-forge/beartype) (📥 770K · ⏱️ 14.12.2025):
	```
	conda install -c conda-forge beartype
	```
</details>
<details><summary><b><a href="https://github.com/openstack/hacking">hacking</a></b> (🥈26 ·  ⭐ 240) - OpenStack Hacking Style Checks. Mirror of code maintained at.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/openstack/hacking) (👨‍💻 190 · 🔀 65 · 📦 8K):

	```
	git clone https://github.com/openstack/hacking
	```
- [PyPi](https://pypi.org/project/hacking) (📥 210K / month · 📦 110 · ⏱️ 11.06.2026):
	```
	pip install hacking
	```
</details>
<details><summary><b><a href="https://github.com/nipunn1313/mypy-protobuf">mypy-protobuf</a></b> (🥈25 ·  ⭐ 710) - Generate mypy stub files from protobuf specs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub]() (👨‍💻 40 · 🔀 81 · 📦 4.7K):

	```
	git clone https://github.com/dropbox/mypy-protobuf
	```
- [PyPi](https://pypi.org/project/mypy-protobuf) (📥 9.9M / month · 📦 300 · ⏱️ 28.04.2026):
	```
	pip install mypy-protobuf
	```
- [Conda](https://anaconda.org/conda-forge/mypy-protobuf) (📥 190K · ⏱️ 28.04.2026):
	```
	conda install -c conda-forge mypy-protobuf
	```
</details>
<details><summary><b><a href="https://github.com/pylint-dev/pylint-django">pylint-django</a></b> (🥈25 ·  ⭐ 620) - A Pylint plugin to help Pylint understand the Django.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub]() (👨‍💻 73 · 🔀 120 · 📦 33K):

	```
	git clone https://github.com/PyCQA/pylint-django
	```
- [PyPi](https://pypi.org/project/pylint-django) (📥 2.1M / month · 📦 180 · ⏱️ 11.07.2026):
	```
	pip install pylint-django
	```
- [Conda](https://anaconda.org/conda-forge/pylint-django) (📥 570K · ⏱️ 11.07.2026):
	```
	conda install -c conda-forge pylint-django
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-isort">flake8-isort</a></b> (🥈25 ·  ⭐ 180 · 💤) - flake8 plugin that integrates isort. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-isort) (👨‍💻 40 · 🔀 200 · 📦 29K):

	```
	git clone https://github.com/gforcada/flake8-isort
	```
- [PyPi](https://pypi.org/project/flake8-isort) (📥 2.1M / month · 📦 630 · ⏱️ 25.10.2025):
	```
	pip install flake8-isort
	```
- [Conda](https://anaconda.org/conda-forge/flake8-isort) (📥 110K · ⏱️ 25.10.2025):
	```
	conda install -c conda-forge flake8-isort
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/flake8-comprehensions">flake8-comprehensions</a></b> (🥉24 ·  ⭐ 470 · 💤) - A flake8 plugin to help you write better.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adamchainz/flake8-comprehensions) (👨‍💻 16 · 🔀 23 · 📦 30K):

	```
	git clone https://github.com/adamchainz/flake8-comprehensions
	```
- [PyPi](https://pypi.org/project/flake8-comprehensions) (📥 1.8M / month · 📦 780 · ⏱️ 09.09.2025):
	```
	pip install flake8-comprehensions
	```
- [Conda](https://anaconda.org/conda-forge/flake8-comprehensions) (📥 1.2M · ⏱️ 10.09.2025):
	```
	conda install -c conda-forge flake8-comprehensions
	```
</details>
<details><summary><b><a href="https://github.com/mgedmin/check-manifest">check-manifest</a></b> (🥉24 ·  ⭐ 290 · 💤) - Tool to check the completeness of MANIFEST.in for Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mgedmin/check-manifest) (👨‍💻 23 · 🔀 37 · 📦 12K):

	```
	git clone https://github.com/mgedmin/check-manifest
	```
- [PyPi](https://pypi.org/project/check-manifest) (📥 980K / month · 📦 5K · ⏱️ 15.10.2025):
	```
	pip install check-manifest
	```
- [Conda](https://anaconda.org/conda-forge/check-manifest) (📥 210K · ⏱️ 15.10.2025):
	```
	conda install -c conda-forge check-manifest
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-import-order">flake8-import-order</a></b> (🥉22 ·  ⭐ 280) - Flake8 plugin that checks import order against.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-import-order) (👨‍💻 50 · 🔀 73):

	```
	git clone https://github.com/PyCQA/flake8-import-order
	```
- [PyPi](https://pypi.org/project/flake8-import-order) (📥 1.6M / month · 📦 650 · ⏱️ 24.06.2025):
	```
	pip install flake8-import-order
	```
- [Conda](https://anaconda.org/conda-forge/flake8-import-order) (📥 580K · ⏱️ 26.06.2025):
	```
	conda install -c conda-forge flake8-import-order
	```
</details>
<details><summary><b><a href="https://github.com/peterjc/flake8-black">flake8-black</a></b> (🥉22 ·  ⭐ 160 · 💤) - flake8 plugin to run black for checking Python coding style. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/peterjc/flake8-black) (👨‍💻 11 · 🔀 11 · 📦 8.8K):

	```
	git clone https://github.com/peterjc/flake8-black
	```
- [PyPi](https://pypi.org/project/flake8-black) (📥 640K / month · 📦 540 · ⏱️ 21.09.2025):
	```
	pip install flake8-black
	```
- [Conda](https://anaconda.org/conda-forge/flake8-black) (📥 500K · ⏱️ 22.09.2025):
	```
	conda install -c conda-forge flake8-black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-commas">flake8-commas</a></b> (🥉22 ·  ⭐ 130) - Flake8 extension for enforcing trailing commas in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-commas) (👨‍💻 15 · 🔀 30 · 📦 19K):

	```
	git clone https://github.com/PyCQA/flake8-commas
	```
- [PyPi](https://pypi.org/project/flake8-commas) (📥 310K / month · 📦 220 · ⏱️ 16.05.2024):
	```
	pip install flake8-commas
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-builtins">flake8-builtins</a></b> (🥉22 ·  ⭐ 120 · 💤) - Check for python builtins being used as variables or.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-builtins) (👨‍💻 21 · 🔀 25 · 📦 12K):

	```
	git clone https://github.com/gforcada/flake8-builtins
	```
- [PyPi](https://pypi.org/project/flake8-builtins) (📥 970K / month · 📦 590 · ⏱️ 25.10.2025):
	```
	pip install flake8-builtins
	```
- [Conda](https://anaconda.org/conda-forge/flake8-builtins) (📥 680K · ⏱️ 27.10.2025):
	```
	conda install -c conda-forge flake8-builtins
	```
</details>
<details><summary><b><a href="https://github.com/andreoliwa/nitpick">nitpick</a></b> (🥉20 ·  ⭐ 410 · 💤) - Enforce the same settings on multiple projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andreoliwa/nitpick) (👨‍💻 18 · 🔀 24 · 📦 1.4K):

	```
	git clone https://github.com/andreoliwa/nitpick
	```
- [PyPi](https://pypi.org/project/nitpick) (📥 11K / month · 📦 26 · ⏱️ 30.11.2025):
	```
	pip install nitpick
	```
</details>
<details><summary><b><a href="https://github.com/MartinThoma/flake8-simplify">flake8-simplify</a></b> (🥉19 ·  ⭐ 200) - A flake8 plugin that helps you to simplify code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MartinThoma/flake8-simplify) (👨‍💻 16 · 🔀 23):

	```
	git clone https://github.com/MartinThoma/flake8-simplify
	```
- [PyPi](https://pypi.org/project/flake8-simplify) (📥 400K / month · 📦 140 · ⏱️ 01.01.2026):
	```
	pip install flake8-simplify
	```
- [Conda](https://anaconda.org/conda-forge/flake8-simplify) (📥 75K · ⏱️ 06.01.2026):
	```
	conda install -c conda-forge flake8-simplify
	```
</details>
<details><summary>Show 20 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/pyflakes">pyflakes</a></b> (🥈30 ·  ⭐ 1.4K · 💀) - A simple program which checks Python source files for errors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/PyCQA/pydocstyle">pydocstyle</a></b> (🥈28 ·  ⭐ 1.1K · 💀) - docstring style checker. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/PyCQA/pep8-naming">pep8-naming</a></b> (🥈25 ·  ⭐ 530 · 💀) - Naming Convention checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/terrencepreilly/darglint">darglint</a></b> (🥈25 ·  ⭐ 480 · 💀) - A python documentation linter which checks that the docstring.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zheller/flake8-quotes">flake8-quotes</a></b> (🥈25 ·  ⭐ 180 · 💀) - Flake8 extension for checking quotes in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/klen/pylama">pylama</a></b> (🥉23 ·  ⭐ 1K · 💀) - Code audit tool for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/wemake-services/flake8-eradicate">flake8-eradicate</a></b> (🥉23 ·  ⭐ 310 · 💀) - Flake8 plugin to find commented out or dead code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/predictive-analytics-lab/data-science-types">data-science-types</a></b> (🥉21 ·  ⭐ 200 · 💀) - Type stubs for Python machine learning libraries. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/coala/coala">coala</a></b> (🥉20 ·  ⭐ 3.6K · 💀) - coala provides a unified command-line interface for linting and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/tylerwince/flake8-bandit">flake8-bandit</a></b> (🥉20 ·  ⭐ 110 · 💀) - Automated security testing using bandit and flake8. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deppen8/pandas-vet">pandas-vet</a></b> (🥉19 ·  ⭐ 170 · 💀) - A plugin for Flake8 that checks pandas code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Instagram/Fixit">Fixit</a></b> (🥉18 ·  ⭐ 690 · 💤) - Advanced Python linting framework with auto-fixes and.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/ambv/flake8-mypy">flake8-mypy</a></b> (🥉18 ·  ⭐ 100 · 💀) - A plugin for flake8 integrating Mypy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/jschaf/pylint-flask">pylint-flask</a></b> (🥉18 ·  ⭐ 64 · 💀) - A Pylint plugin to analyze Flask applications. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bndr/pycycle">pycycle</a></b> (🥉17 ·  ⭐ 340 · 💀) - Tool for pinpointing circular imports in Python. Find cyclic imports.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/life4/flakehell">flakehell</a></b> (🥉17 ·  ⭐ 230 · 💀) - Flake8 wrapper to make it nice, legacy-friendly, configurable. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/hchasestevens/bellybutton">bellybutton</a></b> (🥉15 ·  ⭐ 270 · 💀) - Custom Python linting through AST expressions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/justinabrahms/imhotep">imhotep</a></b> (🥉14 ·  ⭐ 220 · 💀) - A static-analysis bot for Github. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/cemsbr/yala">yala</a></b> (🥉14 ·  ⭐ 14 · 💀) - Yet Another Linter Aggregator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lyft/linty_fresh">linty_fresh</a></b> (🥉12 ·  ⭐ 180 · 💀) - Surface lint errors during code review. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code>mypy</code>
</details>
<br>

## Type checkers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Microsoft/pyright">pyright</a></b> (🥈31 ·  ⭐ 16K) - Static Type Checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Microsoft/pyright) (👨‍💻 150 · 🔀 1.8K · 📦 1.7K):

	```
	git clone https://github.com/Microsoft/pyright
	```
- [npm](https://www.npmjs.com/package/pyright) (📥 3.3M / month · 📦 95 · ⏱️ 25.06.2026):
	```
	npm install pyright
	```
</details>
<details><summary><b><a href="https://github.com/facebook/pyre-check">pyre-check</a></b> (🥉23 ·  ⭐ 7.2K) - Performant type-checking for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/pyre-check) (👨‍💻 310 · 🔀 450 · 📦 24):

	```
	git clone https://github.com/facebook/pyre-check
	```
- [PyPi](https://pypi.org/project/pyre-check) (📥 210K / month · 📦 87 · ⏱️ 07.07.2025):
	```
	pip install pyre-check
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/python/mypy">mypy</a></b> (🥇35 ·  ⭐ 21K) - Optional static typing for Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/agronholm/typeguard">typeguard</a></b> (🥉28 ·  ⭐ 1.8K) - Run-time type checker for Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/google/pytype">pytype</a></b> (🥉26 ·  ⭐ 4.9K · 💀) - A static type analyzer for Python code. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Code Formatters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/psf/black">black</a></b> (🥇36 ·  ⭐ 42K) - The uncompromising Python code formatter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/black) (👨‍💻 540 · 🔀 2.8K · 📦 690K):

	```
	git clone https://github.com/psf/black
	```
- [PyPi](https://pypi.org/project/black) (📥 160M / month · 📦 64K · ⏱️ 18.05.2026):
	```
	pip install black
	```
- [Conda](https://anaconda.org/conda-forge/black) (📥 19M · ⏱️ 22.05.2026):
	```
	conda install -c conda-forge black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/isort">isort</a></b> (🥈34 ·  ⭐ 7K) - A Python utility / library to sort imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/isort) (👨‍💻 350 · 🔀 660 · 📦 580K):

	```
	git clone https://github.com/PyCQA/isort
	```
- [PyPi](https://pypi.org/project/isort) (📥 120M / month · 📦 29K · ⏱️ 12.07.2026):
	```
	pip install isort
	```
- [Conda](https://anaconda.org/conda-forge/isort) (📥 9.7M · ⏱️ 28.02.2026):
	```
	conda install -c conda-forge isort
	```
</details>
<details><summary><b><a href="https://github.com/google/yapf">yapf</a></b> (🥈31 ·  ⭐ 14K · 💤) - A formatter for Python files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/yapf) (👨‍💻 160 · 🔀 900 · 📦 110K):

	```
	git clone https://github.com/google/yapf
	```
- [PyPi](https://pypi.org/project/yapf) (📥 9.1M / month · 📦 1.3K · ⏱️ 14.11.2024):
	```
	pip install yapf
	```
- [Conda](https://anaconda.org/conda-forge/yapf) (📥 3.6M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge yapf
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/hhatto/autopep8">autopep8</a></b> (🥉29 ·  ⭐ 4.6K · 💀) - A tool that automatically formats Python code to conform to the PEP.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/PyCQA/docformatter">docformatter</a></b> (🥉22 ·  ⭐ 590) - Formats docstrings to follow PEP 257. <code>❗Unlicensed</code>
- <b><a href="https://github.com/myint/pyformat">pyformat</a></b> (🥉16 ·  ⭐ 94 · 💀) - Formats Python code to follow a consistent style. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/lyz-code/autoimport">autoimport</a></b> (🥉15 ·  ⭐ 96 · 💀) - Autoimport automatically fixes wrong import statements. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Code Refactoring

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/davidhalter/jedi">jedi</a></b> (🥇34 ·  ⭐ 6.1K) - Awesome autocompletion, static analysis and refactoring library for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/jedi) (👨‍💻 180 · 🔀 530 · 📦 600K):

	```
	git clone https://github.com/davidhalter/jedi
	```
- [PyPi](https://pypi.org/project/jedi) (📥 140M / month · 📦 1.6K · ⏱️ 01.05.2026):
	```
	pip install jedi
	```
- [Conda](https://anaconda.org/conda-forge/jedi) (📥 40M · ⏱️ 23.06.2026):
	```
	conda install -c conda-forge jedi
	```
</details>
<details><summary><b><a href="https://github.com/jendrikseipp/vulture">vulture</a></b> (🥇27 ·  ⭐ 4.7K) - Find dead Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jendrikseipp/vulture) (👨‍💻 54 · 🔀 190 · 📦 7.5K):

	```
	git clone https://github.com/jendrikseipp/vulture
	```
- [PyPi](https://pypi.org/project/vulture) (📥 9.9M / month · 📦 660 · ⏱️ 25.03.2026):
	```
	pip install vulture
	```
- [Conda](https://anaconda.org/conda-forge/vulture) (📥 240K · ⏱️ 26.03.2026):
	```
	conda install -c conda-forge vulture
	```
</details>
<details><summary><b><a href="https://github.com/python-rope/rope">rope</a></b> (🥇27 ·  ⭐ 2.1K · 💤) - a python refactoring library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-rope/rope) (👨‍💻 85 · 🔀 170 · 📦 79K):

	```
	git clone https://github.com/python-rope/rope
	```
- [PyPi](https://pypi.org/project/rope) (📥 1.5M / month · 📦 320 · ⏱️ 12.07.2025):
	```
	pip install rope
	```
- [Conda](https://anaconda.org/conda-forge/rope) (📥 2.6M · ⏱️ 13.07.2025):
	```
	conda install -c conda-forge rope
	```
</details>
<details><summary><b><a href="https://github.com/asottile/pyupgrade">pyupgrade</a></b> (🥈24 ·  ⭐ 4K · 💤) - A tool (and pre-commit hook) to automatically upgrade syntax for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/pyupgrade) (👨‍💻 36 · 🔀 200):

	```
	git clone https://github.com/asottile/pyupgrade
	```
- [PyPi](https://pypi.org/project/pyupgrade) (📥 1.7M / month · 📦 630 · ⏱️ 19.11.2025):
	```
	pip install pyupgrade
	```
- [Conda](https://anaconda.org/conda-forge/pyupgrade) (📥 980K · ⏱️ 19.11.2025):
	```
	conda install -c conda-forge pyupgrade
	```
</details>
<details><summary><b><a href="https://www.github.com/PyCQA/autoflake">autoflake</a></b> (🥈24 ·  ⭐ 960) - Removes unused imports and unused variables. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub]() (👨‍💻 41 · 🔀 87):

	```
	git clone https://github.com/myint/autoflake
	```
- [PyPi](https://pypi.org/project/autoflake) (📥 5.9M / month · 📦 1.4K · ⏱️ 20.02.2026):
	```
	pip install autoflake
	```
- [Conda](https://anaconda.org/conda-forge/autoflake) (📥 680K · ⏱️ 20.02.2026):
	```
	conda install -c conda-forge autoflake
	```
</details>
<details><summary><b><a href="https://unimport.hakancelik.dev/">unimport</a></b> (🥉19 ·  ⭐ 250) - The ultimate linter and formatter for removing unused import statements.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub]() (👨‍💻 16 · 🔀 21 · 📦 170):

	```
	git clone https://github.com/hakancelik96/unimport
	```
- [PyPi](https://pypi.org/project/unimport) (📥 48K / month · 📦 45 · ⏱️ 02.06.2026):
	```
	pip install unimport
	```
</details>
<details><summary><b><a href="https://github.com/asottile/add-trailing-comma">add-trailing-comma</a></b> (🥉18 ·  ⭐ 370 · 💤) - A tool (and pre-commit hook) to automatically add.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/add-trailing-comma) (👨‍💻 11 · 🔀 29):

	```
	git clone https://github.com/asottile/add-trailing-comma
	```
- [PyPi](https://pypi.org/project/add-trailing-comma) (📥 81K / month · 📦 41 · ⏱️ 10.10.2025):
	```
	pip install add-trailing-comma
	```
</details>
<details><summary><b><a href="https://github.com/elmotec/massedit">massedit</a></b> (🥉15 ·  ⭐ 120 · 💤) - Programmatically edit text files with Python. Useful for source to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/elmotec/massedit) (👨‍💻 9 · 🔀 14 · 📦 54):

	```
	git clone https://github.com/elmotec/massedit
	```
- [PyPi](https://pypi.org/project/massedit) (📥 1.9K / month · 📦 3 · ⏱️ 21.09.2025):
	```
	pip install massedit
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/Instagram/MonkeyType">MonkeyType</a></b> (🥈21 ·  ⭐ 4.9K · 💀) - A Python library that generates static type annotations by.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pycqa/redbaron">redbaron</a></b> (🥈21 ·  ⭐ 720 · 💀) - Bottom-up approach to refactoring in python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/pycqa/eradicate">eradicate</a></b> (🥈21 ·  ⭐ 220 · 💤) - Removes commented-out code. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/PyCQA/baron">baron</a></b> (🥉20 ·  ⭐ 300 · 💀) - IDE allow you to refactor code, Baron allows you to write.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/facebookincubator/Bowler">Bowler</a></b> (🥉19 ·  ⭐ 1.6K · 💀) - Safe code refactoring for modern Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dropbox/pyannotate">pyannotate</a></b> (🥉19 ·  ⭐ 1.4K · 💀) - Auto-generate PEP-484 annotations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/myint/unify">unify</a></b> (🥉18 ·  ⭐ 94 · 💀) - Modifies strings to all use the same quote where possible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ilevkivskyi/com2ann">com2ann</a></b> (🥉17 ·  ⭐ 160 · 💀) - Tool for translation type comments to type annotations in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ambv/retype">retype</a></b> (🥉13 ·  ⭐ 140 · 💀) - Re-apply type annotations from .pyi stubs to your codebase. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/spulec/pep8ify">pep8ify</a></b> (🥉13 ·  ⭐ 120 · 💀) - A library that modifies python source code to conform to pep8. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Code Security

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/bandit">bandit</a></b> (🥇32 ·  ⭐ 8.1K) - Bandit is a tool designed to find common security issues in Python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PyCQA/bandit) (👨‍💻 200 · 🔀 780 · 📦 67K):

	```
	git clone https://github.com/PyCQA/bandit
	```
- [PyPi](https://pypi.org/project/bandit) (📥 27M / month · 📦 3.4K · ⏱️ 25.02.2026):
	```
	pip install bandit
	```
- [Conda](https://anaconda.org/conda-forge/bandit) (📥 690K · ⏱️ 25.02.2026):
	```
	conda install -c conda-forge bandit
	```
</details>
<details><summary><b><a href="https://github.com/pyupio/safety">safety</a></b> (🥈30 ·  ⭐ 2K) - Safety checks Python dependencies for known security vulnerabilities and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyupio/safety) (👨‍💻 56 · 🔀 180 · 📦 20K):

	```
	git clone https://github.com/pyupio/safety
	```
- [PyPi](https://pypi.org/project/safety) (📥 4.8M / month · 📦 1.4K · ⏱️ 29.05.2026):
	```
	pip install safety
	```
- [Conda](https://anaconda.org/conda-forge/safety) (📥 190K · ⏱️ 30.05.2026):
	```
	conda install -c conda-forge safety
	```
</details>
<details><summary><b><a href="https://github.com/sqlmapproject/sqlmap">sqlmap</a></b> (🥉25 ·  ⭐ 38K · 📉) - Automatic SQL injection and database takeover tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sqlmapproject/sqlmap) (👨‍💻 160 · 🔀 6.3K · 📦 24):

	```
	git clone https://github.com/sqlmapproject/sqlmap
	```
- [PyPi](https://pypi.org/project/sqlmap) (📥 61K / month · 📦 13 · ⏱️ 01.07.2026):
	```
	pip install sqlmap
	```
</details>
<details><summary><b><a href="https://github.com/dlint-py/dlint">dlint</a></b> (🥉18 ·  ⭐ 180) - Dlint is a tool for encouraging best coding practices and helping ensure.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dlint-py/dlint) (👨‍💻 16 · 🔀 17):

	```
	git clone https://github.com/dlint-py/dlint
	```
- [PyPi](https://pypi.org/project/dlint) (📥 93K / month · 📦 110 · ⏱️ 31.10.2024):
	```
	pip install dlint
	```
- [Conda](https://anaconda.org/conda-forge/dlint) (📥 14K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge dlint
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/dashingsoft/pyarmor">pyarmor</a></b> (🥈26 ·  ⭐ 5.1K) - A tool used to obfuscate python scripts, bind obfuscated scripts.. <code><a href="https://tldrlegal.com/search?q=SGI-B-2.0">❗️SGI-B-2.0</a></code>
- <b><a href="https://github.com/Yelp/detect-secrets">detect-secrets</a></b> (🥉24 ·  ⭐ 4.2K · 💀) - An enterprise friendly way of detecting and preventing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/landscapeio/dodgy">dodgy</a></b> (🥉19 ·  ⭐ 120 · 💀) - Dodgy: Searches for dodgy looking lines in Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/python-security/pyt">pyt</a></b> (🥉16 ·  ⭐ 2.2K · 💀) - A Static Analysis Tool for Detecting Security Vulnerabilities in.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
</details>
<br>

## Virtual Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/virtualenv">virtualenv</a></b> (🥇36 ·  ⭐ 5K) - Virtual Python Environment builder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/virtualenv) (👨‍💻 310 · 🔀 1.1K · 📦 510K):

	```
	git clone https://github.com/pypa/virtualenv
	```
- [PyPi](https://pypi.org/project/virtualenv) (📥 500M / month · 📦 2.2K · ⏱️ 21.07.2026):
	```
	pip install virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/virtualenv) (📥 23M · ⏱️ 21.07.2026):
	```
	conda install -c conda-forge virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pypa/pipenv">pipenv</a></b> (🥈35 ·  ⭐ 25K) - Python Development Workflow for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipenv) (👨‍💻 540 · 🔀 1.9K · 📦 170K):

	```
	git clone https://github.com/pypa/pipenv
	```
- [PyPi](https://pypi.org/project/pipenv) (📥 26M / month · 📦 260 · ⏱️ 08.06.2026):
	```
	pip install pipenv
	```
- [Conda](https://anaconda.org/conda-forge/pipenv) (📥 350K · ⏱️ 08.06.2026):
	```
	conda install -c conda-forge pipenv
	```
</details>
<details><summary><b><a href="https://github.com/ekalinin/nodeenv">nodeenv</a></b> (🥈31 ·  ⭐ 1.8K · 💤) - Virtual environment for Node.js & integrator with virtualenv. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ekalinin/nodeenv) (👨‍💻 110 · 🔀 220 · 📦 150K):

	```
	git clone https://github.com/ekalinin/nodeenv
	```
- [PyPi](https://pypi.org/project/nodeenv) (📥 190M / month · 📦 410 · ⏱️ 20.12.2025):
	```
	pip install nodeenv
	```
- [Conda](https://anaconda.org/conda-forge/nodeenv) (📥 9.1M · ⏱️ 20.12.2025):
	```
	conda install -c conda-forge nodeenv
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/pyenv/pyenv">pyenv</a></b> (🥈23 ·  ⭐ 41K · 💀) - Simple Python version management. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pyenv/pyenv-virtualenv">pyenv-virtualenv</a></b> (🥉14 ·  ⭐ 6.3K · 💀) - a pyenv plugin to manage virtualenv (a.k.a. python-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sashahart/vex">vex</a></b> (🥉14 ·  ⭐ 350 · 💀) - Run a command in the named virtualenv. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pyenv/pyenv-installer">pyenv-installer</a></b> (🥉12 ·  ⭐ 3.9K · 💀) - This tool is used to install `pyenv` and friends. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/raiyanyahya/freshenv">freshenv</a></b> (🥉12 ·  ⭐ 150 · 💀) - Provision, share, manage local and cloud developer environments. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/spotify/dh-virtualenv">dh-virtualenv</a></b> (🥉11 ·  ⭐ 1.6K · 💀) - Python virtualenvs in Debian packages. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/gtalarico/pipenv-pipes">pipenv-pipes</a></b> (🥉10 ·  ⭐ 130 · 💀) - A PipEnv Environment Switcher. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Dependency & Package Managers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pip">pip</a></b> (🥇36 ·  ⭐ 10K · 📉) - The Python package installer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pip) (👨‍💻 900 · 🔀 3.3K · 📦 250K):

	```
	git clone https://github.com/pypa/pip
	```
- [PyPi](https://pypi.org/project/pip) (📥 580M / month · 📦 6.1K · ⏱️ 31.05.2026):
	```
	pip install pip
	```
- [Conda](https://anaconda.org/conda-forge/pip) (📥 230M · ⏱️ 31.05.2026):
	```
	conda install -c conda-forge pip
	```
</details>
<details><summary><b><a href="https://github.com/python-poetry/poetry">poetry</a></b> (🥇32 ·  ⭐ 34K) - Python packaging and dependency management made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-poetry/poetry) (👨‍💻 660 · 🔀 2.5K):

	```
	git clone https://github.com/python-poetry/poetry
	```
- [PyPi](https://pypi.org/project/poetry) (📥 83M / month · 📦 920 · ⏱️ 09.05.2026):
	```
	pip install poetry
	```
- [Conda](https://anaconda.org/conda-forge/poetry) (📥 8.2M · ⏱️ 09.05.2026):
	```
	conda install -c conda-forge poetry
	```
</details>
<details><summary><b><a href="https://github.com/pypa/pipx">pipx</a></b> (🥈31 ·  ⭐ 13K) - Install and Run Python Applications in Isolated Environments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipx) (👨‍💻 200 · 🔀 580 · 📦 4.9K):

	```
	git clone https://github.com/pypa/pipx
	```
- [PyPi](https://pypi.org/project/pipx) (📥 6.9M / month · 📦 100 · ⏱️ 21.07.2026):
	```
	pip install pipx
	```
- [Conda](https://anaconda.org/conda-forge/pipx) (📥 240K · ⏱️ 05.06.2026):
	```
	conda install -c conda-forge pipx
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/pip-tools">pip-tools</a></b> (🥈31 ·  ⭐ 8K) - A set of tools to keep your pinned Python dependencies fresh. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/pip-tools) (👨‍💻 230 · 🔀 660 · 📦 38K):

	```
	git clone https://github.com/jazzband/pip-tools
	```
- [PyPi](https://pypi.org/project/pip-tools) (📥 17M / month · 📦 3.1K · ⏱️ 18.07.2026):
	```
	pip install pip-tools
	```
- [Conda](https://anaconda.org/conda-forge/pip-tools) (📥 340K · ⏱️ 18.07.2026):
	```
	conda install -c conda-forge pip-tools
	```
</details>
<details><summary><b><a href="https://github.com/pdm-project/pdm">PDM</a></b> (🥈30 ·  ⭐ 8.6K) - A modern Python package and dependency manager supporting the latest PEP.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pdm-project/pdm) (👨‍💻 250 · 🔀 480 · 📦 620):

	```
	git clone https://github.com/pdm-project/pdm
	```
- [PyPi](https://pypi.org/project/pdm) (📥 12M / month · 📦 240 · ⏱️ 23.06.2026):
	```
	pip install pdm
	```
- [Conda](https://anaconda.org/conda-forge/pdm) (📥 1.9M · ⏱️ 23.06.2026):
	```
	conda install -c conda-forge pdm
	```
</details>
<details><summary><b><a href="https://github.com/conda/conda">conda</a></b> (🥈30 ·  ⭐ 7.4K · 📉) - A system-level, binary package and environment manager running on all.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/conda) (👨‍💻 500 · 🔀 2.2K · 📦 52K):

	```
	git clone https://github.com/conda/conda
	```
- [PyPi](https://pypi.org/project/conda) (📥 5.5K / month · 📦 83 · ⏱️ 22.04.2017):
	```
	pip install conda
	```
- [Conda](https://anaconda.org/conda-forge/conda) (📥 78M · ⏱️ 01.07.2026):
	```
	conda install -c conda-forge conda
	```
</details>
<details><summary><b><a href="https://github.com/bndr/pipreqs">pipreqs</a></b> (🥉28 ·  ⭐ 7.4K) - pipreqs - Generate pip requirements.txt file based on imports of any.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bndr/pipreqs) (👨‍💻 76 · 🔀 420 · 📦 41K):

	```
	git clone https://github.com/bndr/pipreqs
	```
- [PyPi](https://pypi.org/project/pipreqs) (📥 940K / month · 📦 320 · ⏱️ 18.02.2024):
	```
	pip install pipreqs
	```
- [Conda](https://anaconda.org/conda-forge/pipreqs) (📥 120K · ⏱️ 20.06.2026):
	```
	conda install -c conda-forge pipreqs
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/mamba">mamba</a></b> (🥉20 ·  ⭐ 8.1K) - The Fast Cross-Platform Package Manager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/mamba) (👨‍💻 180 · 🔀 440):

	```
	git clone https://github.com/mamba-org/mamba
	```
- [Conda](https://anaconda.org/conda-forge/mamba) (📥 27M · ⏱️ 08.06.2026):
	```
	conda install -c conda-forge mamba
	```
</details>
<details><summary><b><a href="https://github.com/David-OConnor/pyflow">pyflow</a></b> (🥉16 ·  ⭐ 1.3K · 💤) - An installation and dependency system for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/David-OConnor/pyflow) (👨‍💻 30 · 🔀 48 · 📦 44):

	```
	git clone https://github.com/David-OConnor/pyflow
	```
- [PyPi](https://pypi.org/project/pyflow) (📦 1 · ⏱️ 02.07.2021):
	```
	pip install pyflow
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/dephell/dephell">dephell</a></b> (🥉20 ·  ⭐ 1.8K · 💀) - Python project management. Manage packages: convert between formats,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jaraco/pip-run">pip-run</a></b> (🥉15 ·  ⭐ 140 · 💀) - pip-run - dynamic dependency loader for Python. <code>❗Unlicensed</code>
</details>
<br>

## Code Metrics & Complexity

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/mccabe">mccabe</a></b> (🥇28 ·  ⭐ 680 · 💀) - McCabe complexity checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/mccabe) (👨‍💻 24 · 🔀 63 · 📦 520K):

	```
	git clone https://github.com/PyCQA/mccabe
	```
- [PyPi](https://pypi.org/project/mccabe) (📥 90M / month · 📦 930 · ⏱️ 24.01.2022):
	```
	pip install mccabe
	```
- [Conda](https://anaconda.org/conda-forge/mccabe) (📥 12M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge mccabe
	```
</details>
<details><summary><b><a href="http://prospector.readthedocs.io">prospector</a></b> (🥈26 ·  ⭐ 2.1K) - Prospector is a tool to analyse Python code by aggregating the.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub]() (👨‍💻 98 · 🔀 180 · 📦 5.5K):

	```
	git clone https://github.com/PyCQA/prospector
	```
- [PyPi](https://pypi.org/project/prospector) (📥 460K / month · 📦 310 · ⏱️ 16.07.2026):
	```
	pip install prospector
	```
- [Conda](https://anaconda.org/conda-forge/prospector) (📥 260K · ⏱️ 16.07.2026):
	```
	conda install -c conda-forge prospector
	```
</details>
<details><summary><b><a href="https://github.com/tonybaloney/wily">wily</a></b> (🥉21 ·  ⭐ 1.3K) - A Python application for tracking, reporting on timing and complexity in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tonybaloney/wily) (👨‍💻 25 · 🔀 67 · 📦 310):

	```
	git clone https://github.com/tonybaloney/wily
	```
- [PyPi](https://pypi.org/project/wily) (📥 54K / month · 📦 14 · ⏱️ 26.04.2026):
	```
	pip install wily
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/rubik/radon">radon</a></b> (🥈26 ·  ⭐ 1.9K · 💀) - Various code metrics for Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/rubik/xenon">xenon</a></b> (🥉20 ·  ⭐ 81 · 💀) - Monitoring tool based on radon. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mschwager/cohesion">cohesion</a></b> (🥉15 ·  ⭐ 250 · 💀) - A tool for measuring Python class cohesion. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Textualize/rich">rich</a></b> (🥇36 ·  ⭐ 56K) - Rich is a Python library for rich text and beautiful formatting in the terminal. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Textualize/rich) (👨‍💻 290 · 🔀 2.2K · 📦 550K):

	```
	git clone https://github.com/Textualize/rich
	```
- [PyPi](https://pypi.org/project/rich) (📥 590M / month · 📦 44K · ⏱️ 12.04.2026):
	```
	pip install rich
	```
- [Conda](https://anaconda.org/conda-forge/rich) (📥 23M · ⏱️ 12.04.2026):
	```
	conda install -c conda-forge rich
	```
</details>
<details><summary><b><a href="https://github.com/tqdm/tqdm">tqdm</a></b> (🥇36 ·  ⭐ 31K) - A Fast, Extensible Progress Bar for Python and CLI. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/tqdm/tqdm) (👨‍💻 130 · 🔀 1.5K · 📦 1.2M):

	```
	git clone https://github.com/tqdm/tqdm
	```
- [PyPi](https://pypi.org/project/tqdm) (📥 610M / month · 📦 58K · ⏱️ 17.07.2026):
	```
	pip install tqdm
	```
- [Conda](https://anaconda.org/conda-forge/tqdm) (📥 54M · ⏱️ 18.07.2026):
	```
	conda install -c conda-forge tqdm
	```
- [Docker Hub](https://hub.docker.com/r/tqdm/tqdm) (📥 7.6K · ⭐ 3 · ⏱️ 18.07.2026):
	```
	docker pull tqdm/tqdm
	```
</details>
<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥇32 ·  ⭐ 24K) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 77 · 🔀 800 · 📦 160K):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 77M / month · 📦 15K · ⏱️ 06.12.2024):
	```
	pip install loguru
	```
- [Conda](https://anaconda.org/conda-forge/loguru) (📥 4.6M · ⏱️ 16.01.2026):
	```
	conda install -c conda-forge loguru
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈31 ·  ⭐ 4.8K) - Simple, powerful, and fast logging for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 140 · 🔀 280 · 📦 36K):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 110M / month · 📦 5K · ⏱️ 06.06.2026):
	```
	pip install structlog
	```
- [Conda](https://anaconda.org/conda-forge/structlog) (📥 1.4M · ⏱️ 06.06.2026):
	```
	conda install -c conda-forge structlog
	```
</details>
<details><summary><b><a href="https://github.com/astanin/python-tabulate">tabulate</a></b> (🥈30 ·  ⭐ 2.6K) - Pretty-print tabular data in Python, a library and a command-line.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/astanin/python-tabulate) (👨‍💻 110 · 🔀 190):

	```
	git clone https://github.com/astanin/python-tabulate
	```
- [PyPi](https://pypi.org/project/tabulate) (📥 230M / month · 📦 12K · ⏱️ 04.03.2026):
	```
	pip install tabulate
	```
- [Conda](https://anaconda.org/conda-forge/tabulate) (📥 13M · ⏱️ 05.03.2026):
	```
	conda install -c conda-forge tabulate
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/sentry-python">sentry-sdk</a></b> (🥈30 ·  ⭐ 2.2K) - The official Python SDK for Sentry.io. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getsentry/sentry-python) (👨‍💻 340 · 🔀 640):

	```
	git clone https://github.com/getsentry/sentry-python
	```
- [PyPi](https://pypi.org/project/sentry-sdk) (📥 150M / month · 📦 1.8K · ⏱️ 22.07.2026):
	```
	pip install sentry-sdk
	```
- [Conda](https://anaconda.org/conda-forge/sentry-sdk) (📥 1.9M · ⏱️ 22.07.2026):
	```
	conda install -c conda-forge sentry-sdk
	```
</details>
<details><summary><b><a href="https://github.com/madzak/python-json-logger">python-json-logger</a></b> (🥈29 ·  ⭐ 1.8K · 📈) - Json Formatter for the standard python logger. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madzak/python-json-logger) (👨‍💻 64 · 🔀 230):

	```
	git clone https://github.com/madzak/python-json-logger
	```
- [PyPi](https://pypi.org/project/python-json-logger) (📥 120M / month · 📦 1.4K · ⏱️ 29.03.2026):
	```
	pip install python-json-logger
	```
- [Conda](https://anaconda.org/conda-forge/python-json-logger) (📥 17M · ⏱️ 09.06.2026):
	```
	conda install -c conda-forge python-json-logger
	```
</details>
<details><summary><b><a href="https://github.com/borntyping/python-colorlog">colorlog</a></b> (🥈29 ·  ⭐ 970) - A colored formatter for the python logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/borntyping/python-colorlog) (👨‍💻 37 · 🔀 99 · 📦 67K):

	```
	git clone https://github.com/borntyping/python-colorlog
	```
- [PyPi](https://pypi.org/project/colorlog) (📥 63M / month · 📦 3.2K · ⏱️ 23.07.2026):
	```
	pip install colorlog
	```
- [Conda](https://anaconda.org/conda-forge/colorlog) (📥 7.4M · ⏱️ 18.07.2026):
	```
	conda install -c conda-forge colorlog
	```
</details>
<details><summary><b><a href="https://github.com/xolox/python-coloredlogs">python-coloredlogs</a></b> (🥉27 ·  ⭐ 550 · 💤) - Colored terminal output for Pythons logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xolox/python-coloredlogs) (👨‍💻 17 · 🔀 45 · 📦 87K):

	```
	git clone https://github.com/xolox/python-coloredlogs
	```
- [PyPi](https://pypi.org/project/coloredlogs) (📥 37M / month · 📦 1.9K · ⏱️ 11.06.2021):
	```
	pip install coloredlogs
	```
- [Conda](https://anaconda.org/anaconda/coloredlogs) (📥 24K · ⏱️ 03.11.2025):
	```
	conda install -c anaconda coloredlogs
	```
</details>
<details><summary><b><a href="https://github.com/rsalmei/alive-progress">alive-progress</a></b> (🥉26 ·  ⭐ 5.9K) - A new kind of Progress Bar, with real-time throughput, ETA, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rsalmei/alive-progress) (👨‍💻 11 · 🔀 210 · 📦 5.1K):

	```
	git clone https://github.com/rsalmei/alive-progress
	```
- [PyPi](https://pypi.org/project/alive-progress) (📥 3.6M / month · 📦 590 · ⏱️ 20.07.2025):
	```
	pip install alive-progress
	```
- [Conda](https://anaconda.org/conda-forge/alive-progress) (📥 320K · ⏱️ 08.03.2026):
	```
	conda install -c conda-forge alive-progress
	```
</details>
<details><summary><b><a href="https://github.com/WoLpH/python-progressbar">progressbar2</a></b> (🥉25 ·  ⭐ 880) - Progressbar 2 - A progress bar for Python 2 and Python 3 - pip.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/WoLpH/python-progressbar) (👨‍💻 120 · 🔀 100):

	```
	git clone https://github.com/WoLpH/python-progressbar
	```
- [PyPi](https://pypi.org/project/progressbar2) (📥 19M / month · 📦 930 · ⏱️ 28.08.2024):
	```
	pip install progressbar2
	```
- [Conda](https://anaconda.org/conda-forge/progressbar2) (📥 5.2M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge progressbar2
	```
</details>
<details><summary><b><a href="https://github.com/Qix-/better-exceptions">better-exceptions</a></b> (🥉22 ·  ⭐ 4.7K · 💤) - Pretty and useful exceptions in Python, automatically. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Qix-/better-exceptions) (👨‍💻 20 · 🔀 200):

	```
	git clone https://github.com/Qix-/better-exceptions
	```
- [PyPi](https://pypi.org/project/better-exceptions) (📥 600K / month · 📦 100 · ⏱️ 29.01.2021):
	```
	pip install better-exceptions
	```
</details>
<details><summary><b><a href="https://github.com/shobrook/rebound">rebound</a></b> (🥉22 ·  ⭐ 4.1K) - Command-line tool that instantly fetches Stack Overflow results.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/shobrook/rebound) (👨‍💻 16 · 🔀 380):

	```
	git clone https://github.com/shobrook/rebound
	```
- [PyPi](https://pypi.org/project/rebound) (📥 45K / month · 📦 59 · ⏱️ 22.07.2026):
	```
	pip install rebound
	```
- [Conda](https://anaconda.org/conda-forge/rebound) (📥 1.3M · ⏱️ 10.07.2026):
	```
	conda install -c conda-forge rebound
	```
</details>
<details><summary><b><a href="https://github.com/cknd/stackprinter">stackprinter</a></b> (🥉22 ·  ⭐ 1.3K) - Debugging-friendly exceptions for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cknd/stackprinter) (👨‍💻 9 · 🔀 42 · 📦 450):

	```
	git clone https://github.com/cknd/stackprinter
	```
- [PyPi](https://pypi.org/project/stackprinter) (📥 440K / month · 📦 54 · ⏱️ 17.04.2026):
	```
	pip install stackprinter
	```
- [Conda](https://anaconda.org/conda-forge/stackprinter) (📥 20K · ⏱️ 20.04.2026):
	```
	conda install -c conda-forge stackprinter
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/prettytable/prettytable">prettytable</a></b> (🥈29 ·  ⭐ 1.7K) - A simple Python library for easily displaying tabular data.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/getlogbook/logbook">logbook</a></b> (🥉25 ·  ⭐ 1.5K · 💤) - A cool logging replacement for Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/liiight/notifiers">notifiers</a></b> (🥉24 ·  ⭐ 2.7K · 💀) - The easy way to send notifications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/explosion/wasabi">wasabi</a></b> (🥉24 ·  ⭐ 460 · 💀) - A lightweight console printing and formatting toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/samuelcolvin/python-devtools">python-devtools</a></b> (🥉21 ·  ⭐ 970 · 💀) - Dev tools for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/onelivesleft/PrettyErrors">PrettyErrors</a></b> (🥉20 ·  ⭐ 2.9K · 💀) - Prettify Python exception output to make it legible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/skorokithakis/tbvaccine">tbvaccine</a></b> (🥉16 ·  ⭐ 300 · 💀) - A small utility to pretty-print Python tracebacks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Shell

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/xxh/xxh">xxh</a></b> (🥉15 ·  ⭐ 5.8K · 💤) - Bring your favorite shell wherever you go through the ssh. Xonsh shell,.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/xxh/xxh) (👨‍💻 29 · 🔀 120):

	```
	git clone https://github.com/xxh/xxh
	```
- [PyPi](https://pypi.org/project/xxh-xxh) (📥 770 / month · ⏱️ 06.04.2024):
	```
	pip install xxh-xxh
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/xonsh/xonsh">xonsh</a></b> (🥇27 ·  ⭐ 9.5K) - Python-powered shell. Full-featured, cross-platform and AI-.. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
</details>
<br>

## Documentation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/squidfunk/mkdocs-material">mkdocs-material</a></b> (🥇34 ·  ⭐ 27K) - Documentation that simply works. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/squidfunk/mkdocs-material) (👨‍💻 330 · 🔀 4.1K · 📦 90K):

	```
	git clone https://github.com/squidfunk/mkdocs-material
	```
- [PyPi](https://pypi.org/project/mkdocs-material) (📥 17M / month · 📦 14K · ⏱️ 17.07.2026):
	```
	pip install mkdocs-material
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs-material) (📥 1.1M · ⏱️ 18.07.2026):
	```
	conda install -c conda-forge mkdocs-material
	```
</details>
<details><summary><b><a href="https://github.com/mkdocs/mkdocs">mkdocs</a></b> (🥇32 ·  ⭐ 22K · 💤) - Project documentation with Markdown. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocs/mkdocs) (👨‍💻 260 · 🔀 2.6K · 📦 100K):

	```
	git clone https://github.com/mkdocs/mkdocs
	```
- [PyPi](https://pypi.org/project/mkdocs) (📥 17M / month · 📦 7.1K · ⏱️ 30.08.2024):
	```
	pip install mkdocs
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs) (📥 1.2M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge mkdocs
	```
</details>
<details><summary><b><a href="https://github.com/readthedocs/sphinx_rtd_theme">sphinx_rtd_theme</a></b> (🥈29 ·  ⭐ 5K) - Sphinx theme from Read the Docs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/readthedocs/sphinx_rtd_theme) (👨‍💻 120 · 🔀 1.8K · 📦 16):

	```
	git clone https://github.com/readthedocs/sphinx_rtd_theme
	```
- [PyPi](https://pypi.org/project/sphinx_rtd_theme) (📥 14M / month · 📦 20K · ⏱️ 12.01.2026):
	```
	pip install sphinx_rtd_theme
	```
- [Conda](https://anaconda.org/conda-forge/sphinx_rtd_theme) (📥 5.4M · ⏱️ 23.01.2026):
	```
	conda install -c conda-forge sphinx_rtd_theme
	```
</details>
<details><summary><b><a href="https://github.com/mkdocstrings/mkdocstrings">mkdocstrings</a></b> (🥈29 ·  ⭐ 2.1K) - Automatic documentation from sources, for MkDocs. <code><a href="http://bit.ly/3hkKRql">ISC</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocstrings/mkdocstrings) (👨‍💻 55 · 🔀 120 · 📦 29K):

	```
	git clone https://github.com/mkdocstrings/mkdocstrings
	```
- [PyPi](https://pypi.org/project/mkdocstrings) (📥 7.5M / month · 📦 2.1K · ⏱️ 11.07.2026):
	```
	pip install mkdocstrings
	```
- [Conda](https://anaconda.org/conda-forge/mkdocstrings) (📥 380K · ⏱️ 12.07.2026):
	```
	conda install -c conda-forge mkdocstrings
	```
</details>
<details><summary><b><a href="https://github.com/mkdocstrings/griffe">Griffe</a></b> (🥈29 ·  ⭐ 660) - Signatures for entire Python programs. Extract the structure, the frame,.. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/mkdocstrings/griffe) (👨‍💻 50 · 🔀 67 · 📦 18K):

	```
	git clone https://github.com/mkdocstrings/griffe
	```
- [PyPi](https://pypi.org/project/griffe) (📥 31M / month · 📦 610 · ⏱️ 19.06.2026):
	```
	pip install griffe
	```
- [Conda](https://anaconda.org/conda-forge/griffe) (📥 1M · ⏱️ 21.06.2026):
	```
	conda install -c conda-forge griffe
	```
</details>
<details><summary><b><a href="https://github.com/tox-dev/sphinx-autodoc-typehints">sphinx-autodoc-typehints</a></b> (🥈28 ·  ⭐ 580) - Type hints support for the Sphinx autodoc extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/sphinx-autodoc-typehints) (👨‍💻 70 · 🔀 110 · 📦 61K):

	```
	git clone https://github.com/tox-dev/sphinx-autodoc-typehints
	```
- [PyPi](https://pypi.org/project/sphinx-autodoc-typehints) (📥 9M / month · 📦 7.6K · ⏱️ 21.07.2026):
	```
	pip install sphinx-autodoc-typehints
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autodoc-typehints) (📥 1.1M · ⏱️ 21.07.2026):
	```
	conda install -c conda-forge sphinx-autodoc-typehints
	```
</details>
<details><summary><b><a href="https://www.breathe-doc.org/">breathe</a></b> (🥈25 ·  ⭐ 810 · 💤) - Sphinx Doxygen renderer. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub]() (👨‍💻 120 · 🔀 210 · 📦 20K):

	```
	git clone https://github.com/michaeljones/breathe
	```
- [PyPi](https://pypi.org/project/breathe) (📥 1.5M / month · 📦 130 · ⏱️ 08.07.2025):
	```
	pip install breathe
	```
- [Conda](https://anaconda.org/conda-forge/breathe) (📥 1.4M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge breathe
	```
</details>
<details><summary><b><a href="https://github.com/sphinx-doc/sphinx-autobuild">sphinx-autobuild</a></b> (🥈25 ·  ⭐ 600 · 💤) - Rebuild Sphinx documentation on changes, with hot.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub]() (👨‍💻 37 · 🔀 94 · 📦 33K):

	```
	git clone https://github.com/executablebooks/sphinx-autobuild
	```
- [PyPi](https://pypi.org/project/sphinx-autobuild) (📥 5.8M / month · 📦 2.3K · ⏱️ 25.08.2025):
	```
	pip install sphinx-autobuild
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autobuild) (📥 560K · ⏱️ 04.11.2025):
	```
	conda install -c conda-forge sphinx-autobuild
	```
</details>
<details><summary><b><a href="https://github.com/pdoc3/pdoc">pdoc3</a></b> (🥉23 ·  ⭐ 1.2K · 💤) - Auto-generate API documentation for Python projects. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/pdoc3/pdoc) (👨‍💻 69 · 🔀 140 · 📦 5.2K):

	```
	git clone https://github.com/pdoc3/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc3) (📥 280K / month · 📦 490 · ⏱️ 20.03.2025):
	```
	pip install pdoc3
	```
- [Conda](https://anaconda.org/anaconda/pdoc3) (📥 2.9K · ⏱️ 17.10.2025):
	```
	conda install -c anaconda pdoc3
	```
</details>
<details><summary><b><a href="https://github.com/econchick/interrogate">interrogate</a></b> (🥉23 ·  ⭐ 660) - Explain yourself! Interrogate a codebase for docstring coverage. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/econchick/interrogate) (👨‍💻 17 · 🔀 49 · 📦 9.4K):

	```
	git clone https://github.com/econchick/interrogate
	```
- [PyPi](https://pypi.org/project/interrogate) (📥 1.5M / month · 📦 390 · ⏱️ 07.04.2024):
	```
	pip install interrogate
	```
</details>
<details><summary><b><a href="https://github.com/clayrisser/sphinx-markdown-builder">sphinx-markdown-builder</a></b> (🥉23 ·  ⭐ 160) - DISCONTINUED: sphinx builder that outputs markdown.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/clayrisser/sphinx-markdown-builder) (👨‍💻 19 · 🔀 60 · 📦 1.6K):

	```
	git clone https://github.com/clayrisser/sphinx-markdown-builder
	```
- [PyPi](https://pypi.org/project/sphinx-markdown-builder) (📥 500K / month · 📦 230 · ⏱️ 11.03.2026):
	```
	pip install sphinx-markdown-builder
	```
</details>
<details><summary><b><a href="https://github.com/asottile/blacken-docs">blacken-docs</a></b> (🥉21 ·  ⭐ 670 · 💤) - Run Black on Python code blocks in documentation files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub]() (👨‍💻 26 · 🔀 45 · 📦 1.6K):

	```
	git clone https://github.com/asottile/blacken-docs
	```
- [PyPi](https://pypi.org/project/blacken-docs) (📥 120K / month · 📦 120 · ⏱️ 08.09.2025):
	```
	pip install blacken-docs
	```
- [Conda](https://anaconda.org/conda-forge/blacken-docs) (📥 64K · ⏱️ 08.09.2025):
	```
	conda install -c conda-forge blacken-docs
	```
</details>
<details><summary><b><a href="https://github.com/bitprophet/releases">releases</a></b> (🥉20 ·  ⭐ 180 · 💤) - A powerful Sphinx changelog-generating extension. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bitprophet/releases) (👨‍💻 10 · 🔀 41 · 📦 760):

	```
	git clone https://github.com/bitprophet/releases
	```
- [PyPi](https://pypi.org/project/releases) (📥 62K / month · 📦 41 · ⏱️ 28.04.2023):
	```
	pip install releases
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-releases) (📥 59K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge sphinx-releases
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazydocs">lazydocs</a></b> (🥉19 ·  ⭐ 240 · 💤) - Generate markdown API documentation from Google-style Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/lazydocs) (👨‍💻 13 · 🔀 43 · 📦 420):

	```
	git clone https://github.com/ml-tooling/lazydocs
	```
- [PyPi](https://pypi.org/project/lazydocs) (📥 21K / month · 📦 65 · ⏱️ 27.07.2021):
	```
	pip install lazydocs
	```
</details>
<details><summary><b><a href="https://github.com/timvink/mkdocs-print-site-plugin">mkdocs-print-site-plugin</a></b> (🥉18 ·  ⭐ 180) - MkDocs Plugin that adds an additional page that.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/timvink/mkdocs-print-site-plugin) (👨‍💻 17 · 🔀 28):

	```
	git clone https://github.com/timvink/mkdocs-print-site-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-print-site-plugin) (📥 190K / month · 📦 22 · ⏱️ 03.08.2025):
	```
	pip install mkdocs-print-site-plugin
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/sphinx-doc/sphinx">sphinx</a></b> (🥇31 ·  ⭐ 7.7K) - The Sphinx documentation generator. <code>❗Unlicensed</code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://alabaster.readthedocs.io/">alabaster</a></b> (🥈28 ·  ⭐ 770 · 💀) - A light, configurable Sphinx theme. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mitmproxy/pdoc">pdoc</a></b> (🥈25 ·  ⭐ 2.4K · 💤) - API Documentation for Python Projects. <code><a href="https://tldrlegal.com/search?q=MIT-0">❗️MIT-0</a></code>
- <b><a href="https://github.com/numpy/numpydoc">numpydoc</a></b> (🥉24 ·  ⭐ 350) - Numpys Sphinx extensions. <code>❗Unlicensed</code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ryan-roemer/sphinx-bootstrap-theme">sphinx-bootstrap-theme</a></b> (🥉22 ·  ⭐ 590 · 💀) - Sphinx Bootstrap Theme. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/orzih/mkdocs-with-pdf">mkdocs-with-pdf</a></b> (🥉21 ·  ⭐ 360 · 💀) - Generate a single PDF file from MkDocs repository. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mkdocstrings/pytkdocs">pytkdocs</a></b> (🥉21 ·  ⭐ 54 · 💀) - Load Python objects documentation. <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/timothycrosley/portray">portray</a></b> (🥉20 ·  ⭐ 860 · 💀) - Your Project with Great Documentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin/">mkdocs-awesome-pages-plugin</a></b> (🥉20 ·  ⭐ 620 · 💀) - An MkDocs plugin that simplifies configuring page.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zhaoterryy/mkdocs-pdf-export-plugin">mkdocs-pdf-export-plugin</a></b> (🥉20 ·  ⭐ 220 · 💀) - An MkDocs plugin to export content pages as PDF files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zhaoterryy/mkdocs-git-revision-date-plugin">mkdocs-git-revision-date-plugin</a></b> (🥉20 ·  ⭐ 56 · 💀) - MkDocs plugin for setting revision date from git per.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pycco-docs/pycco">pycco</a></b> (🥉19 ·  ⭐ 840 · 💀) - Literate-style documentation generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zayd62/mkdocs-versioning">mkdocs-versioning</a></b> (🥉15 ·  ⭐ 40 · 💀) - A tool that allows for versioning sites built with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Debugging Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/gruns/icecream">icecream</a></b> (🥇27 ·  ⭐ 10K) - Never use print() to debug again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gruns/icecream) (👨‍💻 38 · 🔀 220 · 📦 24):

	```
	git clone https://github.com/gruns/icecream
	```
- [PyPi](https://pypi.org/project/icecream) (📥 1.9M / month · 📦 600 · ⏱️ 03.04.2026):
	```
	pip install icecream
	```
- [Conda](https://anaconda.org/conda-forge/icecream) (📥 110K · ⏱️ 04.04.2026):
	```
	conda install -c conda-forge icecream
	```
</details>
<details><summary><b><a href="https://github.com/eliben/pyelftools">pyelftools</a></b> (🥇27 ·  ⭐ 2.3K) - Parsing ELF and DWARF in Python. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/eliben/pyelftools) (👨‍💻 110 · 🔀 540 · 📦 12K):

	```
	git clone https://github.com/eliben/pyelftools
	```
- [PyPi](https://pypi.org/project/pyelftools) (📥 15M / month · 📦 360 · ⏱️ 29.05.2026):
	```
	pip install pyelftools
	```
- [Conda](https://anaconda.org/conda-forge/pyelftools) (📥 1.7M · ⏱️ 29.05.2026):
	```
	conda install -c conda-forge pyelftools
	```
</details>
<details><summary><b><a href="https://github.com/pdbpp/pdbpp">pdbpp</a></b> (🥈24 ·  ⭐ 1.4K) - pdb++, a drop-in replacement for pdb (the Python debugger). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pdbpp/pdbpp) (👨‍💻 41 · 🔀 74):

	```
	git clone https://github.com/pdbpp/pdbpp
	```
- [PyPi](https://pypi.org/project/pdbpp) (📥 1.4M / month · 📦 640 · ⏱️ 23.02.2026):
	```
	pip install pdbpp
	```
- [Conda](https://anaconda.org/conda-forge/pdbpp) (📥 400K · ⏱️ 23.02.2026):
	```
	conda install -c conda-forge pdbpp
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/snoop">snoop</a></b> (🥉23 ·  ⭐ 1.5K) - A powerful set of Python debugging tools, based on PySnooper. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/snoop) (👨‍💻 23 · 🔀 43):

	```
	git clone https://github.com/alexmojaki/snoop
	```
- [PyPi](https://pypi.org/project/snoop) (📥 260K / month · 📦 54 · ⏱️ 18.07.2026):
	```
	pip install snoop
	```
- [Conda](https://anaconda.org/conda-forge/snoop) (📥 17K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge snoop
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-hunter">python-hunter</a></b> (🥉19 ·  ⭐ 870 · 💤) - Hunter is a flexible code tracing toolkit. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-hunter) (👨‍💻 10 · 🔀 51):

	```
	git clone https://github.com/ionelmc/python-hunter
	```
- [PyPi](https://pypi.org/project/hunter) (📥 1.1M / month · 📦 17 · ⏱️ 22.08.2025):
	```
	pip install hunter
	```
- [Conda](https://anaconda.org/conda-forge/hunter) (📥 240K · ⏱️ 03.11.2025):
	```
	conda install -c conda-forge hunter
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/birdseye">Birdseye</a></b> (🥉16 ·  ⭐ 1.7K · 💤) - Graphical Python debugger which lets you easily view the values of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/birdseye) (👨‍💻 10 · 🔀 73):

	```
	git clone https://github.com/alexmojaki/birdseye
	```
- [PyPi](https://pypi.org/project/birdseye) (📥 1.2K / month · 📦 9 · ⏱️ 06.09.2025):
	```
	pip install birdseye
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/gotcha/ipdb">ipdb</a></b> (🥇27 ·  ⭐ 1.8K · 💀) - Integration of IPython pdb. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/cool-RR/PySnooper">PySnooper</a></b> (🥈26 ·  ⭐ 16K · 💀) - Never use print for debugging again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/inducer/pudb">pudb</a></b> (🥈24 ·  ⭐ 3.2K · 💤) - Full-screen console debugger for Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/cs01/gdbgui">gdbgui</a></b> (🥉21 ·  ⭐ 10K · 💀) - Browser-based frontend to gdb (gnu debugger). Add breakpoints,.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/lmacken/pyrasite">pyrasite</a></b> (🥉18 ·  ⭐ 1.8K · 💀) - Inject code into running Python processes. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/ionelmc/python-manhole">python-manhole</a></b> (🥉18 ·  ⭐ 400 · 💀) - Debugging manhole for python applications. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/reloadware/reloadium">reloadium</a></b> (🥉15 ·  ⭐ 3K · 💀) - Hot Reloading and Profiling for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Testing Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python">best-of-web-python - Testing</a></b> ( ⭐ 2.6K · 💤)  - Testing libraries & tools for python web frameworks.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.html">unittest</a></b>  - Unittest is a test framework included in the Python standard library.

<details><summary><b><a href="https://github.com/pytest-dev/pytest">pytest</a></b> (🥇39 ·  ⭐ 14K · 📉) - The pytest framework makes it easy to write small tests, yet.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest) (👨‍💻 1.1K · 🔀 3.2K · 📦 1.8M):

	```
	git clone https://github.com/pytest-dev/pytest
	```
- [PyPi](https://pypi.org/project/pytest) (📥 1B / month · 📦 190K · ⏱️ 19.06.2026):
	```
	pip install pytest
	```
- [Conda](https://anaconda.org/conda-forge/pytest) (📥 53M · ⏱️ 22.06.2026):
	```
	conda install -c conda-forge pytest
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/playwright-python">playwright-python</a></b> (🥇33 ·  ⭐ 15K) - Python version of the Playwright testing and automation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/microsoft/playwright-python) (👨‍💻 55 · 🔀 1.2K · 📦 59K):

	```
	git clone https://github.com/microsoft/playwright-python
	```
- [PyPi](https://pypi.org/project/playwright) (📥 86M / month · 📦 6.8K · ⏱️ 29.06.2026):
	```
	pip install playwright
	```
</details>
<details><summary><b><a href="https://github.com/HypothesisWorks/hypothesis">hypothesis</a></b> (🥇33 ·  ⭐ 8.8K) - The property-based testing library for Python. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/HypothesisWorks/hypothesis) (👨‍💻 390 · 🔀 660 · 📦 44K):

	```
	git clone https://github.com/HypothesisWorks/hypothesis
	```
- [PyPi](https://pypi.org/project/hypothesis) (📥 42M / month · 📦 7.5K · ⏱️ 23.07.2026):
	```
	pip install hypothesis
	```
- [Conda](https://anaconda.org/conda-forge/hypothesis) (📥 20M · ⏱️ 22.07.2026):
	```
	conda install -c conda-forge hypothesis
	```
</details>
<details><summary><b><a href="https://github.com/tox-dev/tox">tox</a></b> (🥇33 ·  ⭐ 3.9K) - Command line driven CI frontend and development task automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/tox) (👨‍💻 350 · 🔀 570 · 📦 140K):

	```
	git clone https://github.com/tox-dev/tox
	```
- [PyPi](https://pypi.org/project/tox) (📥 35M / month · 📦 14K · ⏱️ 21.07.2026):
	```
	pip install tox
	```
- [Conda](https://anaconda.org/conda-forge/tox) (📥 2M · ⏱️ 21.07.2026):
	```
	conda install -c conda-forge tox
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-asyncio">pytest-asyncio</a></b> (🥇33 ·  ⭐ 1.6K) - Asyncio support for pytest. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-asyncio) (👨‍💻 82 · 🔀 190 · 📦 220K):

	```
	git clone https://github.com/pytest-dev/pytest-asyncio
	```
- [PyPi](https://pypi.org/project/pytest-asyncio) (📥 240M / month · 📦 41K · ⏱️ 26.05.2026):
	```
	pip install pytest-asyncio
	```
- [Conda](https://anaconda.org/conda-forge/pytest-asyncio) (📥 3.8M · ⏱️ 26.05.2026):
	```
	conda install -c conda-forge pytest-asyncio
	```
</details>
<details><summary><b><a href="https://github.com/robotframework/robotframework">robotframework</a></b> (🥈32 ·  ⭐ 12K) - Generic automation framework for acceptance testing and RPA. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/robotframework/robotframework) (👨‍💻 230 · 🔀 2.6K · 📦 14K):

	```
	git clone https://github.com/robotframework/robotframework
	```
- [PyPi](https://pypi.org/project/robotframework) (📥 4.9M / month · 📦 1.2K · ⏱️ 17.07.2026):
	```
	pip install robotframework
	```
- [Conda](https://anaconda.org/conda-forge/robotframework) (📥 280K · ⏱️ 04.03.2026):
	```
	conda install -c conda-forge robotframework
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-cov">pytest-cov</a></b> (🥈32 ·  ⭐ 2K) - Coverage plugin for pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-cov) (👨‍💻 100 · 🔀 230):

	```
	git clone https://github.com/pytest-dev/pytest-cov
	```
- [PyPi](https://pypi.org/project/pytest-cov) (📥 220M / month · 📦 78K · ⏱️ 21.03.2026):
	```
	pip install pytest-cov
	```
- [Conda](https://anaconda.org/conda-forge/pytest-cov) (📥 19M · ⏱️ 22.03.2026):
	```
	conda install -c conda-forge pytest-cov
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-mock">pytest-mock</a></b> (🥈31 ·  ⭐ 2K) - Thin-wrapper around the mock package for easier use with pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-mock) (👨‍💻 84 · 🔀 160 · 📦 140K):

	```
	git clone https://github.com/pytest-dev/pytest-mock
	```
- [PyPi](https://pypi.org/project/pytest-mock) (📥 99M / month · 📦 9.4K · ⏱️ 16.09.2025):
	```
	pip install pytest-mock
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mock) (📥 5.8M · ⏱️ 17.09.2025):
	```
	conda install -c conda-forge pytest-mock
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-xdist">pytest-xdist</a></b> (🥈31 ·  ⭐ 1.9K) - pytest plugin for distributed testing and loop-on-failures.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-xdist) (👨‍💻 120 · 🔀 270 · 📦 140K):

	```
	git clone https://github.com/pytest-dev/pytest-xdist
	```
- [PyPi](https://pypi.org/project/pytest-xdist) (📥 160M / month · 📦 5.6K · ⏱️ 01.07.2025):
	```
	pip install pytest-xdist
	```
- [Conda](https://anaconda.org/conda-forge/pytest-xdist) (📥 14M · ⏱️ 02.07.2025):
	```
	conda install -c conda-forge pytest-xdist
	```
</details>
<details><summary><b><a href="https://github.com/asweigart/pyautogui">pyautogui</a></b> (🥈30 ·  ⭐ 10K) - A cross-platform GUI automation Python module for human beings. Used.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/asweigart/pyautogui) (👨‍💻 52 · 🔀 1.3K · 📦 57K):

	```
	git clone https://github.com/asweigart/pyautogui
	```
- [PyPi](https://pypi.org/project/pyautogui) (📥 2.9M / month · 📦 1K · ⏱️ 24.05.2023):
	```
	pip install pyautogui
	```
- [Conda](https://anaconda.org/conda-forge/pyautogui) (📥 490K · ⏱️ 18.05.2026):
	```
	conda install -c conda-forge pyautogui
	```
</details>
<details><summary><b><a href="https://github.com/wntrblm/nox">nox</a></b> (🥈28 ·  ⭐ 1.5K) - Flexible test automation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub]() (👨‍💻 120 · 🔀 180 · 📦 8.2K):

	```
	git clone https://github.com/theacodes/nox
	```
- [PyPi](https://pypi.org/project/nox) (📥 6.1M / month · 📦 1.8K · ⏱️ 12.07.2026):
	```
	pip install nox
	```
- [Conda](https://anaconda.org/conda-forge/nox) (📥 620K · ⏱️ 12.07.2026):
	```
	conda install -c conda-forge nox
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-bdd">pytest-bdd</a></b> (🥈28 ·  ⭐ 1.5K) - BDD library for the pytest runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-bdd) (👨‍💻 71 · 🔀 240 · 📦 5K):

	```
	git clone https://github.com/pytest-dev/pytest-bdd
	```
- [PyPi](https://pypi.org/project/pytest-bdd) (📥 3.5M / month · 📦 110 · ⏱️ 05.12.2024):
	```
	pip install pytest-bdd
	```
- [Conda](https://anaconda.org/conda-forge/pytest-bdd) (📥 78K · ⏱️ 03.07.2026):
	```
	conda install -c conda-forge pytest-bdd
	```
</details>
<details><summary><b><a href="https://github.com/spulec/freezegun">freezegun</a></b> (🥈27 ·  ⭐ 4.5K · 💤) - Let your Python tests travel through time. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spulec/freezegun) (👨‍💻 130 · 🔀 290):

	```
	git clone https://github.com/spulec/freezegun
	```
- [PyPi](https://pypi.org/project/freezegun) (📥 54M / month · 📦 1.3K · ⏱️ 09.08.2025):
	```
	pip install freezegun
	```
- [Conda](https://anaconda.org/conda-forge/freezegun) (📥 2.2M · ⏱️ 09.08.2025):
	```
	conda install -c conda-forge freezegun
	```
</details>
<details><summary><b><a href="https://github.com/Teemu/pytest-sugar">pytest-sugar</a></b> (🥈27 ·  ⭐ 1.5K · 💤) - a plugin for py.test that changes the default look and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Teemu/pytest-sugar) (👨‍💻 58 · 🔀 81 · 📦 31K):

	```
	git clone https://github.com/Teemu/pytest-sugar
	```
- [PyPi](https://pypi.org/project/pytest-sugar) (📥 7.5M / month · 📦 1.5K · ⏱️ 23.08.2025):
	```
	pip install pytest-sugar
	```
- [Conda](https://anaconda.org/conda-forge/pytest-sugar) (📥 630K · ⏱️ 24.08.2025):
	```
	conda install -c conda-forge pytest-sugar
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-html">pytest-html</a></b> (🥈27 ·  ⭐ 770) - Plugin for generating HTML reports for pytest results. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-html) (👨‍💻 66 · 🔀 250 · 📦 59K):

	```
	git clone https://github.com/pytest-dev/pytest-html
	```
- [PyPi](https://pypi.org/project/pytest-html) (📥 20M / month · 📦 1.1K · ⏱️ 19.01.2026):
	```
	pip install pytest-html
	```
- [Conda](https://anaconda.org/conda-forge/pytest-html) (📥 1.2M · ⏱️ 21.01.2026):
	```
	conda install -c conda-forge pytest-html
	```
</details>
<details><summary><b><a href="https://github.com/TheKevJames/coveralls-python">coveralls-python</a></b> (🥈27 ·  ⭐ 570) - Show coverage stats online via coveralls.io. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TheKevJames/coveralls-python) (👨‍💻 67 · 🔀 190 · 📦 37K):

	```
	git clone https://github.com/TheKevJames/coveralls-python
	```
- [PyPi](https://pypi.org/project/coveralls) (📥 1.2M / month · 📦 2.6K · ⏱️ 28.02.2026):
	```
	pip install coveralls
	```
- [Conda](https://anaconda.org/conda-forge/coveralls) (📥 1.6M · ⏱️ 28.02.2026):
	```
	conda install -c conda-forge coveralls
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/pytest-benchmark">pytest-benchmark</a></b> (🥉26 ·  ⭐ 1.4K) - pytest fixture for benchmarking code. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ionelmc/pytest-benchmark) (👨‍💻 55 · 🔀 130):

	```
	git clone https://github.com/ionelmc/pytest-benchmark
	```
- [PyPi](https://pypi.org/project/pytest-benchmark) (📥 13M / month · 📦 1.9K · ⏱️ 09.11.2025):
	```
	pip install pytest-benchmark
	```
- [Conda](https://anaconda.org/conda-forge/pytest-benchmark) (📥 3.3M · ⏱️ 09.11.2025):
	```
	conda install -c conda-forge pytest-benchmark
	```
</details>
<details><summary><b><a href="https://github.com/airspeed-velocity/asv">asv</a></b> (🥉26 ·  ⭐ 1K) - Airspeed Velocity: A simple Python benchmarking tool with web-based reporting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/airspeed-velocity/asv) (👨‍💻 98 · 🔀 210 · 📦 1.8K):

	```
	git clone https://github.com/airspeed-velocity/asv
	```
- [PyPi](https://pypi.org/project/asv) (📥 530K / month · 📦 210 · ⏱️ 27.06.2026):
	```
	pip install asv
	```
- [Conda](https://anaconda.org/conda-forge/asv) (📥 1.5M · ⏱️ 27.06.2026):
	```
	conda install -c conda-forge asv
	```
</details>
<details><summary><b><a href="https://github.com/nose-devs/nose2">nose2</a></b> (🥉26 ·  ⭐ 820) - The successor to nose, based on unittest2. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/nose-devs/nose2) (👨‍💻 86 · 🔀 130 · 📦 27K):

	```
	git clone https://github.com/nose-devs/nose2
	```
- [PyPi](https://pypi.org/project/nose2) (📥 690K / month · 📦 360 · ⏱️ 02.03.2026):
	```
	pip install nose2
	```
- [Conda](https://anaconda.org/conda-forge/nose2) (📥 240K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nose2
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-testinfra">pytest-testinfra</a></b> (🥉25 ·  ⭐ 2.4K · 💤) - Testinfra test your infrastructures. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-testinfra) (👨‍💻 140 · 🔀 360 · 📦 2.7K):

	```
	git clone https://github.com/pytest-dev/pytest-testinfra
	```
- [PyPi](https://pypi.org/project/pytest-testinfra) (📥 1.5M / month · 📦 20 · ⏱️ 30.03.2025):
	```
	pip install pytest-testinfra
	```
- [Conda](https://anaconda.org/conda-forge/pytest-testinfra) (📥 42K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge pytest-testinfra
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-randomly">pytest-randomly</a></b> (🥉25 ·  ⭐ 700) - Pytest plugin to randomly order tests and control random.seed. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-randomly) (👨‍💻 20 · 🔀 34 · 📦 12K):

	```
	git clone https://github.com/pytest-dev/pytest-randomly
	```
- [PyPi](https://pypi.org/project/pytest-randomly) (📥 9M / month · 📦 940 · ⏱️ 20.04.2026):
	```
	pip install pytest-randomly
	```
- [Conda](https://anaconda.org/conda-forge/pytest-randomly) (📥 400K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge pytest-randomly
	```
</details>
<details><summary><b><a href="https://github.com/lk-geimfari/mimesis">mimesis</a></b> (🥉24 ·  ⭐ 4.8K) - Mimesis is a fast Python library for generating fake data in multiple.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lk-geimfari/mimesis) (👨‍💻 130 · 🔀 360 · 📦 2.3K):

	```
	git clone https://github.com/lk-geimfari/mimesis
	```
- [PyPi](https://pypi.org/project/mimesis) (📦 100 · ⏱️ 16.07.2026):
	```
	pip install mimesis
	```
- [Conda](https://anaconda.org/conda-forge/mimesis) (📥 390K · ⏱️ 11.01.2026):
	```
	conda install -c conda-forge mimesis
	```
</details>
<details><summary><b><a href="https://github.com/tarpas/pytest-testmon">pytest-testmon</a></b> (🥉24 ·  ⭐ 1K · 💤) - Selects tests affected by changed files. Executes the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tarpas/pytest-testmon) (👨‍💻 29 · 🔀 78 · 📦 1.7K):

	```
	git clone https://github.com/tarpas/pytest-testmon
	```
- [PyPi](https://pypi.org/project/pytest-testmon) (📥 4.4M / month · 📦 59 · ⏱️ 01.12.2025):
	```
	pip install pytest-testmon
	```
- [Conda](https://anaconda.org/conda-forge/pytest-testmon) (📥 200K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge pytest-testmon
	```
</details>
<details><summary><b><a href="https://github.com/joeyespo/pytest-watch">pytest-watch</a></b> (🥉23 ·  ⭐ 730 · 💤) - Local continuous test runner with pytest and watchdog. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/joeyespo/pytest-watch) (👨‍💻 16 · 🔀 54 · 📦 12K):

	```
	git clone https://github.com/joeyespo/pytest-watch
	```
- [PyPi](https://pypi.org/project/pytest-watch) (📥 880K / month · 📦 560 · ⏱️ 20.05.2018):
	```
	pip install pytest-watch
	```
- [Conda](https://anaconda.org/conda-forge/pytest-watch) (📥 260K · ⏱️ 02.10.2025):
	```
	conda install -c conda-forge pytest-watch
	```
</details>
<details><summary><b><a href="https://github.com/avast/pytest-docker">pytest-docker</a></b> (🥉23 ·  ⭐ 480 · 💤) - Docker-based integration tests. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/avast/pytest-docker) (👨‍💻 30 · 🔀 77 · 📦 2.7K):

	```
	git clone https://github.com/avast/pytest-docker
	```
- [PyPi](https://pypi.org/project/pytest-docker) (📥 2.1M / month · 📦 150 · ⏱️ 12.11.2025):
	```
	pip install pytest-docker
	```
</details>
<details><summary><b><a href="https://github.com/gabrielcnr/pytest-datadir">pytest-datadir</a></b> (🥉23 ·  ⭐ 280) - pytest plugin for manipulating test data directories and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gabrielcnr/pytest-datadir) (👨‍💻 16 · 🔀 26 · 📦 2.3K):

	```
	git clone https://github.com/gabrielcnr/pytest-datadir
	```
- [PyPi](https://pypi.org/project/pytest-datadir) (📥 1.6M / month · 📦 270 · ⏱️ 30.07.2025):
	```
	pip install pytest-datadir
	```
- [Conda](https://anaconda.org/conda-forge/pytest-datadir) (📥 530K · ⏱️ 30.07.2025):
	```
	conda install -c conda-forge pytest-datadir
	```
</details>
<details><summary><b><a href="https://github.com/CleanCut/green">green</a></b> (🥉21 ·  ⭐ 790) - Green is a clean, colorful, fast python test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CleanCut/green) (👨‍💻 41 · 🔀 75 · 📦 1.4K):

	```
	git clone https://github.com/CleanCut/green
	```
- [PyPi](https://pypi.org/project/green) (📥 17K / month · 📦 130 · ⏱️ 18.04.2024):
	```
	pip install green
	```
- [Conda](https://anaconda.org/conda-forge/green) (📥 470K · ⏱️ 02.03.2026):
	```
	conda install -c conda-forge green
	```
</details>
<details><summary><b><a href="https://github.com/Erotemic/xdoctest">xdoctest</a></b> (🥉21 ·  ⭐ 220) - A rewrite of Pythons builtin doctest module (with pytest plugin.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Erotemic/xdoctest) (👨‍💻 14 · 🔀 18):

	```
	git clone https://github.com/Erotemic/xdoctest
	```
- [PyPi](https://pypi.org/project/xdoctest) (📥 990K / month · 📦 260 · ⏱️ 27.03.2026):
	```
	pip install xdoctest
	```
- [Conda](https://anaconda.org/conda-forge/xdoctest) (📥 280K · ⏱️ 27.03.2026):
	```
	conda install -c conda-forge xdoctest
	```
</details>
<details><summary><b><a href="https://github.com/man-group/pytest-plugins">pytest-plugins</a></b> (🥉19 ·  ⭐ 600) - A grab-bag of nifty pytest plugins. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/man-group/pytest-plugins) (👨‍💻 67 · 🔀 89):

	```
	git clone https://github.com/man-group/pytest-plugins
	```
- [PyPi](https://pypi.org/project/pytest-virtualenv) (📥 36K / month · 📦 73 · ⏱️ 29.11.2024):
	```
	pip install pytest-virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/pytest-shutil) (📥 140K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge pytest-shutil
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/nose-devs/nose">nose</a></b> (🥈28 ·  ⭐ 1.4K · 💀) - nose is nicer testing for python. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1%2B">❗️LGPL-2.1+</a></code>
- <b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥉25 ·  ⭐ 3.6K · 💀) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/hamcrest/PyHamcrest">PyHamcrest</a></b> (🥉24 ·  ⭐ 790 · 💀) - Hamcrest matchers for Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/datadriventests/ddt">ddt</a></b> (🥉24 ·  ⭐ 440 · 💀) - Data-Driven Tests for Python Unittest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/xiaocong/uiautomator">uiautomator</a></b> (🥉22 ·  ⭐ 1.9K · 💀) - Python wrapper of Android uiautomator test tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tvorog/pytest-lazy-fixture">pytest-lazy-fixture</a></b> (🥉22 ·  ⭐ 380 · 💀) - It helps to use fixtures in pytest.mark.parametrize. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/realpython/pytest-mypy">pytest-mypy</a></b> (🥉22 ·  ⭐ 260 · 💀) - A Pytest Plugin for Mypy. <code>❗Unlicensed</code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nestorsalceda/mamba">Mamba Test Runner</a></b> (🥉21 ·  ⭐ 520 · 💀) - The definitive testing tool for Python. Born under the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ActivisionGameScience/assertpy">assertpy</a></b> (🥉19 ·  ⭐ 520 · 💀) - Simple assertion library for unit testing in python with a fluent.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/sixpack/sixpack">sixpack</a></b> (🥉18 ·  ⭐ 1.8K · 💀) - Sixpack is a language-agnostic a/b-testing framework. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/emirozer/fake2db">fake2db</a></b> (🥉15 ·  ⭐ 2.1K · 💀) - create custom test databases that are populated with fake data. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/pytest-dev/pytest-play">pytest-play</a></b> (🥉14 ·  ⭐ 73 · 💀) - pytest plugin that let you automate actions and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Code Packaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://packaging.python.org/overview/">Python.org Packaging</a></b>  - An Overview of Packaging for Python.

<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">pyinstaller</a></b> (🥇33 ·  ⭐ 13K) - Freeze (package) Python programs into stand-alone executables. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 490 · 🔀 2K · 📦 90K):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
- [PyPi](https://pypi.org/project/pyinstaller) (📥 11M / month · 📦 2.3K · ⏱️ 13.06.2026):
	```
	pip install pyinstaller
	```
- [Conda](https://anaconda.org/conda-forge/pyinstaller) (📥 2M · ⏱️ 15.06.2026):
	```
	conda install -c conda-forge pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/Nuitka/Nuitka">Nuitka</a></b> (🥈29 ·  ⭐ 15K) - Nuitka is a Python compiler written in Python. Its fully compatible.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Nuitka/Nuitka) (👨‍💻 210 · 🔀 780 · 📦 4K):

	```
	git clone https://github.com/Nuitka/Nuitka
	```
- [PyPi](https://pypi.org/project/nuitka) (📥 460K / month · 📦 240 · ⏱️ 21.06.2026):
	```
	pip install nuitka
	```
- [Conda](https://anaconda.org/conda-forge/nuitka) (📥 3.5M · ⏱️ 24.06.2026):
	```
	conda install -c conda-forge nuitka
	```
</details>
<details><summary><b><a href="https://github.com/beeware/briefcase">briefcase</a></b> (🥈26 ·  ⭐ 3.3K) - Tools to support converting a Python project into a standalone.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/beeware/briefcase) (👨‍💻 220 · 🔀 520 · 📦 880):

	```
	git clone https://github.com/beeware/briefcase
	```
- [PyPi](https://pypi.org/project/briefcase) (📥 39K / month · 📦 45 · ⏱️ 08.07.2026):
	```
	pip install briefcase
	```
</details>
<details><summary><b><a href="https://github.com/pex-tool/pex">pex</a></b> (🥈24 ·  ⭐ 4.2K) - The PEX packaging toolchain. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub]() (👨‍💻 130 · 🔀 310):

	```
	git clone https://github.com/pantsbuild/pex
	```
- [PyPi](https://pypi.org/project/pex) (📥 6.4M / month · 📦 65 · ⏱️ 20.07.2026):
	```
	pip install pex
	```
</details>
<details><summary><b><a href="https://github.com/ronaldoussoren/py2app">py2app</a></b> (🥈24 ·  ⭐ 420) - py2app is a Python setuptools command which will allow you to make.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ronaldoussoren/py2app) (👨‍💻 31 · 🔀 45 · 📦 5.6K):

	```
	git clone https://github.com/ronaldoussoren/py2app
	```
- [PyPi](https://pypi.org/project/py2app) (📥 71K / month · 📦 42 · ⏱️ 13.02.2026):
	```
	pip install py2app
	```
</details>
<details><summary><b><a href="https://github.com/marcelotduarte/cx_Freeze">cx_Freeze</a></b> (🥉22 ·  ⭐ 1.6K) - Creates standalone executables from Python scripts with the.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/marcelotduarte/cx_Freeze) (👨‍💻 130 · 🔀 240):

	```
	git clone https://github.com/marcelotduarte/cx_Freeze
	```
- [PyPi](https://pypi.org/project/cx_freeze) (📥 200K / month · 📦 140 · ⏱️ 13.04.2026):
	```
	pip install cx_freeze
	```
- [Conda](https://anaconda.org/conda-forge/cx_freeze) (📥 1.4M · ⏱️ 13.04.2026):
	```
	conda install -c conda-forge cx_freeze
	```
</details>
<details><summary><b><a href="https://github.com/py2exe/py2exe">py2exe</a></b> (🥉22 ·  ⭐ 990) - Create standalone Windows programs from Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py2exe/py2exe) (👨‍💻 25 · 🔀 110 · 📦 2.2K):

	```
	git clone https://github.com/py2exe/py2exe
	```
- [PyPi](https://pypi.org/project/py2exe) (📥 15K / month · 📦 12 · ⏱️ 21.06.2026):
	```
	pip install py2exe
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉20 ·  ⭐ 1.9K) - shiv is a command line utility for building fully self contained Python.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 45 · 🔀 110):

	```
	git clone https://github.com/linkedin/shiv
	```
- [PyPi](https://pypi.org/project/shiv) (📥 340K / month · 📦 29 · ⏱️ 01.11.2024):
	```
	pip install shiv
	```
</details>
<details><summary><b><a href="https://github.com/conda/constructor">constructor</a></b> (🥉19 ·  ⭐ 500) - tool for creating installers from conda packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/constructor) (👨‍💻 81 · 🔀 180 · 📦 27):

	```
	git clone https://github.com/conda/constructor
	```
- [Conda](https://anaconda.org/anaconda/constructor) (📥 26K · ⏱️ 07.07.2026):
	```
	conda install -c anaconda constructor
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/pypa/packaging">packaging</a></b> (🥇30 ·  ⭐ 720) - Core utilities for Python packages. <code>❗Unlicensed</code>
- <b><a href="https://github.com/indygreg/PyOxidizer">PyOxidizer</a></b> (🥉21 ·  ⭐ 4.8K · 💀) - A modern Python application packaging and distribution tool. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/takluyver/pynsist">pynsist</a></b> (🥉19 ·  ⭐ 890 · 💀) - Build Windows installers for Python applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/facebookincubator/xar">xar</a></b> (🥉16 ·  ⭐ 1.6K · 💀) - executable archive format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jamesabel/pyship">pyship</a></b> (🥉14 ·  ⭐ 45 · 📈) - pyship - ship Python desktop apps to end users. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/google/subpar">subpar</a></b> (🥉9 ·  ⭐ 570 · 💀) - Subpar is a utility for creating self-contained python executables... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Build Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/setuptools">setuptools</a></b> (🥇37 ·  ⭐ 2.8K) - Official project repository for the Setuptools build system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools) (👨‍💻 650 · 🔀 1.4K · 📦 870K):

	```
	git clone https://github.com/pypa/setuptools
	```
- [PyPi](https://pypi.org/project/setuptools) (📥 1.4B / month · 📦 34K · ⏱️ 04.07.2026):
	```
	pip install setuptools
	```
- [Conda](https://anaconda.org/conda-forge/setuptools) (📥 210M · ⏱️ 09.07.2026):
	```
	conda install -c conda-forge setuptools
	```
</details>
<details><summary><b><a href="https://github.com/pypa/wheel">wheel</a></b> (🥇32 ·  ⭐ 560) - The official binary distribution format for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/wheel) (👨‍💻 91 · 🔀 180 · 📦 390K):

	```
	git clone https://github.com/pypa/wheel
	```
- [PyPi](https://pypi.org/project/wheel) (📥 560M / month · 📦 16K · ⏱️ 22.04.2026):
	```
	pip install wheel
	```
- [Conda](https://anaconda.org/conda-forge/wheel) (📥 180M · ⏱️ 22.04.2026):
	```
	conda install -c conda-forge wheel
	```
</details>
<details><summary><b><a href="https://github.com/pyinvoke/invoke">invoke</a></b> (🥈30 ·  ⭐ 4.7K) - Pythonic task management & command execution. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pyinvoke/invoke) (👨‍💻 63 · 🔀 390 · 📦 34K):

	```
	git clone https://github.com/pyinvoke/invoke
	```
- [PyPi](https://pypi.org/project/invoke) (📥 81M / month · 📦 1.4K · ⏱️ 07.04.2026):
	```
	pip install invoke
	```
- [Conda](https://anaconda.org/conda-forge/invoke) (📥 2.8M · ⏱️ 07.04.2026):
	```
	conda install -c conda-forge invoke
	```
</details>
<details><summary><b><a href="https://github.com/pypa/twine">twine</a></b> (🥈30 ·  ⭐ 1.7K · 💤) - Utilities for interacting with PyPI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pypa/twine) (👨‍💻 130 · 🔀 320 · 📦 140K):

	```
	git clone https://github.com/pypa/twine
	```
- [PyPi](https://pypi.org/project/twine) (📥 35M / month · 📦 23K · ⏱️ 04.09.2025):
	```
	pip install twine
	```
- [Conda](https://anaconda.org/conda-forge/twine) (📥 2M · ⏱️ 04.09.2025):
	```
	conda install -c conda-forge twine
	```
</details>
<details><summary><b><a href="https://setuptools-scm.readthedocs.io/en/latest/">setuptools_scm</a></b> (🥈28 ·  ⭐ 950) - the blessed package to manage your versions by scm tags. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub]() (👨‍💻 160 · 🔀 240):

	```
	git clone https://github.com/pypa/setuptools_scm
	```
- [PyPi](https://pypi.org/project/setuptools_scm) (📥 130M / month · 📦 2.7K · ⏱️ 21.07.2026):
	```
	pip install setuptools_scm
	```
- [Conda](https://anaconda.org/conda-forge/setuptools_scm) (📥 7.9M · ⏱️ 21.07.2026):
	```
	conda install -c conda-forge setuptools_scm
	```
</details>
<details><summary><b><a href="https://github.com/SCons/scons">scons</a></b> (🥈27 ·  ⭐ 2.4K) - SCons - a software construction tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SCons/scons) (👨‍💻 170 · 🔀 340 · 📦 4.3K):

	```
	git clone https://github.com/SCons/scons
	```
- [PyPi](https://pypi.org/project/scons) (📥 990K / month · 📦 58 · ⏱️ 16.11.2025):
	```
	pip install scons
	```
- [Conda](https://anaconda.org/conda-forge/scons) (📥 1.5M · ⏱️ 17.11.2025):
	```
	conda install -c conda-forge scons
	```
</details>
<details><summary><b><a href="https://github.com/pypa/flit">flit</a></b> (🥉26 ·  ⭐ 2.2K · 💤) - Simplified packaging of Python modules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pypa/flit) (👨‍💻 83 · 🔀 150 · 📦 2.8K):

	```
	git clone https://github.com/pypa/flit
	```
- [PyPi](https://pypi.org/project/flit) (📥 18M / month · 📦 930 · ⏱️ 25.03.2025):
	```
	pip install flit
	```
- [Conda](https://anaconda.org/conda-forge/flit) (📥 460K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge flit
	```
</details>
<details><summary><b><a href="https://github.com/pydoit/doit">doit</a></b> (🥉26 ·  ⭐ 2K) - CLI task management & automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydoit/doit) (👨‍💻 70 · 🔀 190 · 📦 2.3K):

	```
	git clone https://github.com/pydoit/doit
	```
- [PyPi](https://pypi.org/project/doit) (📥 770K / month · 📦 140 · ⏱️ 09.02.2026):
	```
	pip install doit
	```
- [Conda](https://anaconda.org/conda-forge/doit) (📥 570K · ⏱️ 09.02.2026):
	```
	conda install -c conda-forge doit
	```
</details>
<details><summary><b><a href="https://github.com/buildbot/buildbot">buildbot</a></b> (🥉23 ·  ⭐ 5.4K · 💤) - Python-based continuous integration testing framework; your.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/buildbot/buildbot) (👨‍💻 900 · 🔀 1.6K · 📦 410):

	```
	git clone https://github.com/buildbot/buildbot
	```
- [PyPi](https://pypi.org/project/buildbot) (📥 23K / month · 📦 20 · ⏱️ 12.05.2025):
	```
	pip install buildbot
	```
- [Conda](https://anaconda.org/conda-forge/buildbot) (📥 190K · ⏱️ 13.05.2025):
	```
	conda install -c conda-forge buildbot
	```
</details>
<details><summary><b><a href="https://github.com/pybuilder/pybuilder">pybuilder</a></b> (🥉20 ·  ⭐ 2K) - Software build automation tool for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pybuilder/pybuilder) (👨‍💻 40 · 🔀 270):

	```
	git clone https://github.com/pybuilder/pybuilder
	```
- [PyPi](https://pypi.org/project/pybuilder) (📥 48K / month · 📦 6 · ⏱️ 02.04.2026):
	```
	pip install pybuilder
	```
- [Conda](https://anaconda.org/conda-forge/pybuilder) (📥 400K · ⏱️ 02.04.2026):
	```
	conda install -c conda-forge pybuilder
	```
</details>
<details><summary><b><a href="https://github.com/rags/pynt">pynt</a></b> (🥉16 ·  ⭐ 160 · 💤) - A pynt of Python build. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rags/pynt) (👨‍💻 10 · 🔀 19 · 📦 130):

	```
	git clone https://github.com/rags/pynt
	```
- [PyPi](https://pypi.org/project/pynt) (📥 7K / month · 📦 1 · ⏱️ 24.06.2018):
	```
	pip install pynt
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/universal-build">universal-build</a></b> (🥉12 ·  ⭐ 25 · 💀) - Universal build utilities for containerized build pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/universal-build) (👨‍💻 5 · 🔀 8):

	```
	git clone https://github.com/ml-tooling/universal-build
	```
- [PyPi](https://pypi.org/project/universal-build) (📥 280 / month · 📦 7 · ⏱️ 16.11.2021):
	```
	pip install universal-build
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/buildout/buildout">buildout</a></b> (🥉20 ·  ⭐ 610) - Buildout is a deployment automation tool written in and extended.. <code><a href="https://tldrlegal.com/search?q=ZPL-2.1">❗️ZPL-2.1</a></code>
- <b><a href="https://github.com/paver/paver">paver</a></b> (🥉19 ·  ⭐ 460 · 💀) - Python-based project scripting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## System Monitoring & Profiling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/giampaolo/psutil">psutil</a></b> (🥇36 ·  ⭐ 11K) - Cross-platform lib for process and system monitoring in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/giampaolo/psutil) (👨‍💻 250 · 🔀 1.5K · 📦 800K):

	```
	git clone https://github.com/giampaolo/psutil
	```
- [PyPi](https://pypi.org/project/psutil) (📥 370M / month · 📦 20K · ⏱️ 28.01.2026):
	```
	pip install psutil
	```
- [Conda](https://anaconda.org/conda-forge/psutil) (📥 66M · ⏱️ 29.01.2026):
	```
	conda install -c conda-forge psutil
	```
</details>
<details><summary><b><a href="https://github.com/benfred/py-spy">py-spy</a></b> (🥇30 ·  ⭐ 15K) - Sampling profiler for Python programs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/py-spy) (👨‍💻 57 · 🔀 530 · 📦 8.8K):

	```
	git clone https://github.com/benfred/py-spy
	```
- [PyPi](https://pypi.org/project/py-spy) (📥 23M / month · 📦 240 · ⏱️ 24.04.2026):
	```
	pip install py-spy
	```
- [Conda](https://anaconda.org/conda-forge/py-spy) (📥 910K · ⏱️ 27.04.2026):
	```
	conda install -c conda-forge py-spy
	```
- [Cargo](https://crates.io/crates/py-spy) (📦 5 · ⏱️ 24.04.2026):
	```
	cargo install py-spy
	```
</details>
<details><summary><b><a href="https://github.com/plasma-umass/scalene">Scalene</a></b> (🥈27 ·  ⭐ 13K) - Scalene: a high-performance, high-precision CPU, GPU, and memory.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/plasma-umass/scalene) (👨‍💻 62 · 🔀 440 · 📦 1K):

	```
	git clone https://github.com/plasma-umass/scalene
	```
- [PyPi](https://pypi.org/project/scalene) (📥 340K / month · 📦 75 · ⏱️ 12.05.2026):
	```
	pip install scalene
	```
</details>
<details><summary><b><a href="https://github.com/joerick/pyinstrument">pyinstrument</a></b> (🥈27 ·  ⭐ 7.6K) - Call stack profiler for Python. Shows you why your code is slow!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joerick/pyinstrument) (👨‍💻 76 · 🔀 260 · 📦 4.5K):

	```
	git clone https://github.com/joerick/pyinstrument
	```
- [PyPi](https://pypi.org/project/pyinstrument) (📥 10M / month · 📦 240 · ⏱️ 04.01.2026):
	```
	pip install pyinstrument
	```
- [Conda](https://anaconda.org/conda-forge/pyinstrument) (📥 1.3M · ⏱️ 04.01.2026):
	```
	conda install -c conda-forge pyinstrument
	```
</details>
<details><summary><b><a href="https://github.com/sumerc/yappi">Yappi</a></b> (🥈27 ·  ⭐ 1.7K) - Yet Another Python Profiler, but this time multithreading, asyncio and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sumerc/yappi) (👨‍💻 35 · 🔀 82 · 📦 1.7K):

	```
	git clone https://github.com/sumerc/yappi
	```
- [PyPi](https://pypi.org/project/yappi) (📥 3.9M / month · 📦 89 · ⏱️ 17.03.2026):
	```
	pip install yappi
	```
- [Conda](https://anaconda.org/conda-forge/yappi) (📥 430K · ⏱️ 18.03.2026):
	```
	conda install -c conda-forge yappi
	```
</details>
<details><summary><b><a href="https://github.com/bloomberg/memray">memray</a></b> (🥈26 ·  ⭐ 15K) - Memray is a memory profiler for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bloomberg/memray) (👨‍💻 72 · 🔀 440 · 📦 24):

	```
	git clone https://github.com/bloomberg/memray
	```
- [PyPi](https://pypi.org/project/memray) (📥 15M / month · 📦 150 · ⏱️ 08.04.2026):
	```
	pip install memray
	```
- [Conda](https://anaconda.org/conda-forge/memray) (📥 730K · ⏱️ 08.04.2026):
	```
	conda install -c conda-forge memray
	```
</details>
<details><summary><b><a href="https://github.com/pythonprofilers/memory_profiler">memory-profiler</a></b> (🥉25 ·  ⭐ 4.5K · 💤) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pythonprofilers/memory_profiler) (👨‍💻 100 · 🔀 390):

	```
	git clone https://github.com/pythonprofilers/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📥 9.1M / month · 📦 460 · ⏱️ 15.11.2022):
	```
	pip install memory_profiler
	```
- [Conda](https://anaconda.org/conda-forge/memory_profiler) (📥 5M · ⏱️ 04.12.2025):
	```
	conda install -c conda-forge memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/fabianp/memory_profiler">memory_profiler</a></b> (🥉25 ·  ⭐ 4.5K · 💤) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fabianp/memory_profiler) (👨‍💻 62 · 🔀 390):

	```
	git clone https://github.com/fabianp/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📥 9.1M / month · 📦 460 · ⏱️ 15.11.2022):
	```
	pip install memory_profiler
	```
- [Conda](https://anaconda.org/conda-forge/memory_profiler) (📥 5M · ⏱️ 04.12.2025):
	```
	conda install -c conda-forge memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/pympler/pympler">pympler</a></b> (🥉25 ·  ⭐ 1.2K) - Development tool to measure, monitor and analyze the memory behavior.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pympler/pympler) (👨‍💻 31 · 🔀 89):

	```
	git clone https://github.com/pympler/pympler
	```
- [PyPi](https://pypi.org/project/pympler) (📥 5.6M / month · 📦 260 · ⏱️ 28.06.2024):
	```
	pip install pympler
	```
- [Conda](https://anaconda.org/conda-forge/pympler) (📥 780K · ⏱️ 15.07.2026):
	```
	conda install -c conda-forge pympler
	```
</details>
<details><summary><b><a href="https://github.com/pyutils/line_profiler">line_profiler</a></b> (🥉24 ·  ⭐ 3.2K) - Line-by-line profiling for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyutils/line_profiler) (👨‍💻 55 · 🔀 140):

	```
	git clone https://github.com/pyutils/line_profiler
	```
- [PyPi](https://pypi.org/project/line_profiler) (📥 2.8M / month · 📦 400 · ⏱️ 23.02.2026):
	```
	pip install line_profiler
	```
- [Conda](https://anaconda.org/conda-forge/line_profiler) (📥 5.5M · ⏱️ 24.02.2026):
	```
	conda install -c conda-forge line_profiler
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/nicolargo/glances">Glances</a></b> (🥈27 ·  ⭐ 33K) - Glances an Eye on your system. A top/htop alternative for.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/aristocratos/bpytop">Bpytop</a></b> (🥉23 ·  ⭐ 8.2K · 💀) - Linux/OSX/FreeBSD resource monitor. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/python-diamond/Diamond">Diamond</a></b> (🥉22 ·  ⭐ 1.8K · 💀) - Diamond is a python daemon that collects system metrics and publishes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nvdv/vprof">vprof</a></b> (🥉20 ·  ⭐ 4K · 💀) - Visual profiler for Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/what-studio/profiling">Profiling</a></b> (🥉18 ·  ⭐ 3K · 💀) - Was an interactive continuous Python profiler. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/alexmojaki/heartrate">heartrate</a></b> (🥉17 ·  ⭐ 1.5K · 💀) - Simple real time visualisation of the execution of a Python program. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/csurfer/pyheat">pyheat</a></b> (🥉16 ·  ⭐ 730 · 💀) - pprofile + matplotlib = Python program profiled as an awesome heatmap!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/agermanidis/livepython">livepython</a></b> (🥉11 ·  ⭐ 2.6K · 💀) - Visually trace Python code in real-time. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## AST Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/alexmojaki/executing">executing</a></b> (🥇29 ·  ⭐ 400) - Get information about what a Python frame is currently doing,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/executing) (👨‍💻 12 · 🔀 39 · 📦 340K):

	```
	git clone https://github.com/alexmojaki/executing
	```
- [PyPi](https://pypi.org/project/executing) (📥 140M / month · 📦 800 · ⏱️ 01.09.2025):
	```
	pip install executing
	```
- [Conda](https://anaconda.org/conda-forge/executing) (📥 29M · ⏱️ 01.09.2025):
	```
	conda install -c conda-forge executing
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/gast">gast</a></b> (🥈25 ·  ⭐ 150 · 💤) - Python AST that abstracts the underlying Python version. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/gast) (👨‍💻 13 · 🔀 38 · 📦 220K):

	```
	git clone https://github.com/serge-sans-paille/gast
	```
- [PyPi](https://pypi.org/project/gast) (📥 19M / month · 📦 530 · ⏱️ 29.11.2025):
	```
	pip install gast
	```
- [Conda](https://anaconda.org/conda-forge/gast) (📥 4.5M · ⏱️ 30.11.2025):
	```
	conda install -c conda-forge gast
	```
</details>
<details><summary><b><a href="https://github.com/lmfit/asteval">asteval</a></b> (🥉24 ·  ⭐ 220) - Safe, minimalistic evaluator of python expression using ast module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub]() (👨‍💻 28 · 🔀 49):

	```
	git clone https://github.com/newville/asteval
	```
- [PyPi](https://pypi.org/project/asteval) (📥 5.8M / month · 📦 210 · ⏱️ 11.06.2026):
	```
	pip install asteval
	```
- [Conda](https://anaconda.org/conda-forge/asteval) (📥 1.1M · ⏱️ 12.06.2026):
	```
	conda install -c conda-forge asteval
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/simonpercivall/astunparse">astunparse</a></b> (🥈26 ·  ⭐ 220 · 💀) - An AST unparser for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/berkerpeksag/astor">astor</a></b> (🥉23 ·  ⭐ 860 · 💀) - Python AST read/write. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/python/typed_ast">typed_ast</a></b> (🥉21 ·  ⭐ 230 · 💀) - Modified fork of CPythons ast module that parses `# type:`.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pre-commit/pre-commit">pre-commit</a></b> (🥇34 ·  ⭐ 15K) - A framework for managing and maintaining multi-language pre-commit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pre-commit/pre-commit) (👨‍💻 170 · 🔀 990 · 📦 290K):

	```
	git clone https://github.com/pre-commit/pre-commit
	```
- [PyPi](https://pypi.org/project/pre-commit) (📥 170M / month · 📦 37K · ⏱️ 21.07.2026):
	```
	pip install pre-commit
	```
- [Conda](https://anaconda.org/conda-forge/pre-commit) (📥 10M · ⏱️ 22.07.2026):
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
