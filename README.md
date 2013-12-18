Špajza
======

A place to hold my recipes.

To render the recipes, you will Python 2.7.x with Pip and Virtualenv. For
directions for your platform, see the
[Hitchhiker's guide to Python](http://docs.python-guide.org/en/latest/).

Create a virtual environment:
```
virtualenv env
```

Activate the environment on Windows::
```
env\Scripts\activate.bat
```

or on Linux:
```
source venv/bin/activate
```

Install Sphinx (only the first time)
```
pip install -r requirements.txt
```

Generate HTML
```
make html
```

Check out `make help` for a full list of target formats.
