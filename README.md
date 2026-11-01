# Computational Theory

## Project overview

This project contains undergraduate computational theory problems and supporting
Python examples. The main learning material is provided in
[`problems.ipynb`](problems.ipynb), a Jupyter notebook that combines written
explanations with executable code.

## Installation and setup

You need Python 3 and `pip`. The repository lists its Python dependencies in
[`requirements.txt`](requirements.txt).

From the repository directory, create and activate a virtual environment:

On Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

On macOS or Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the listed dependencies:

```text
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

[`requirements.txt`](requirements.txt) is the source of truth for the
project's dependencies. Install from that file rather than maintaining a
separate package list in this README.

## Running the project

Launch the notebook from the repository directory with either Jupyter Notebook:

```console
jupyter notebook problems.ipynb
```

or JupyterLab:

```console
jupyter lab problems.ipynb
```

These commands should be run after activating `.venv`, so Jupyter uses the
environment where the project dependencies were installed. In the browser,
select the Python kernel associated with `.venv` (usually shown as
`Python 3` or `Python (computational-theory)`) before running the cells.

## Repository structure

| File | Purpose |
| --- | --- |
| [`problems.ipynb`](problems.ipynb) | Main Jupyter notebook containing the project problems, explanations, and executable Python examples. |
| [`requirements.txt`](requirements.txt) | Python dependency list used to set up the project environment. |
| [`AGENTS.md`](AGENTS.md) | Repository guidance for contributors and documentation style. |
| [`.gitignore`](.gitignore) | Lists generated files and local environment files that Git should ignore. |
