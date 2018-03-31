# pypi upload cheatsheet

Install required tools:

    $ pip install -U wheel twine

Create source distribution:

    $ python setup.py sdist
    
Create universal wheel:

    $ python setup.py bdist_wheel --universal

Upload to pypi:

    $ twine upload dist/*
