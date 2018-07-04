# qgis cheatsheet

## python from pyenv

Use python from pyenv for QGIS (macOS):

        $ env PYTHON_CONFIGURE_OPTS="--enable-framework CC=clang" pyenv install 3.6.5
        $ ln -s ~/.pyenv/versions/3.6.5/Python.framework /Library/Frameworks/Python.framework

Then install QGIS.
