# pyenv cheatsheet

[pyenv](https://github.com/yyuu/pyenv)

[pyenv-virtualenv](https://github.com/yyuu/pyenv-virtualenv)

[Command reference](https://github.com/yyuu/pyenv/blob/master/COMMANDS.md)

## pyenv
### pyenv install

List available python versions:

        $ pyenv install -l

Install Python 3.5.1:

        $ pyenv install 3.5.1
        $ pyenv rehash

### pyenv versions

List installed versions:

        $ pyenv versions

### pyenv global
Select a python version as a global:

        $ pyenv global 3.5.1

### pyenv local

Sets a local application-specific Python version:

        $ pyenv local 2.7.6

Unset the local version:

        $ pyenv local --unset

## pyenv-virtualenv
### List existing virtualenvs

        $ pyenv virtualenvs

### Create virtualenv

From current version with name "venv35":

        $ pyenv virtualenv venv35

From version 2.7.10 with name "venv27":

        $ pyenv virtualenv 2.7.10 venv27

### Activate/deactivate

        $ pyenv activate <name>
        $ pyenv deactivate

### Delete existing virtualenv

        $ pyenv uninstall venv27
        
        
## pipenv

### install packages

        $ pipenv install <package_name>
