# python-notebook-example

Quick example of python/jupyter notebook.
VS Code has some native support of Jupyter notebooks.

## Setting up repo from clone

```sh
# check on your python
python --version

# create a virtual environment in your project folder
# python 3 has virtualenv built-in as venv
python -m venv .venv

# activate the virtual env
source .venv/bin/activate

# install dependecies
pip -r requirements.txt
```

## Creating this repo from scratch

```sh
# check on your python
python --version

# create a virtual environment in your project folder
# python 3 has virtualenv built-in as venv
python -m venv .venv

# activate the virtual env
source .venv/bin/activate

# only ipykernel is need
# there is no need to install jupyter
pip install ipykernel -U

# write pip dependencies
# these can be used to install pip -r requirements.txt
pip freeze > requirements.txt

touch example.ipynb
```

## References

[Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).
VS Code.

[How to install Python packages with pip and requirements.txt](https://note.nkmk.me/en/python-pip-install-requirements/).
nkmk.me.
note.nkmk.me.

[Keeping credentials safe in Jupyter Notebooks](https://towardsdatascience.com/keeping-credentials-safe-in-jupyter-notebooks-fbd215a8e311).
Alexandra Souly.
Towards Data Science.
