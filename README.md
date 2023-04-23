# python-notebook-example

Quick example of python/jupyter notebook.
I also wanted to see if there were any differences in Github Enterprise.

[Main repo on Github](https://github.com/hparra/python-notebook-example/).

## Setting up repo from clone

```sh
# check on your python
# you should have major version 3
python --version

# create a virtual environment in your project folder
# python 3 has virtualenv built-in as venv
python -m venv .venv

# activate the virtual env
source .venv/bin/activate

# install dependencies
pip install -r requirements.txt
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

## Editing *.ipyb

VS Code has great support.

## Testing Github Enterprise

Is this going to work there?
Just create new repo there and add as new remote.

```sh
# check your remotes
git remote -v

# add new remote
git remote add NAME URL

# do it!
git push NAME BRANCH
```

Looks like they work just fine on GitHub Enterprise Server 3.6.7.

## References

[Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).
VS Code.

[How to install Python packages with pip and requirements.txt](https://note.nkmk.me/en/python-pip-install-requirements/).
nkmk.me.
note.nkmk.me.

[Keeping credentials safe in Jupyter Notebooks](https://towardsdatascience.com/keeping-credentials-safe-in-jupyter-notebooks-fbd215a8e311).
Alexandra Souly.
Towards Data Science.

[Managing remote repositories](https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories).
Github.
