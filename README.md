# astro_setup
setup for experimental astrophysics work

From a base directory, download setup.py, pyproject.toml, and a folder python_files. If python_files should have a file called __init__.py and it should be empty. You can add a the init file with:
> touch python_files/__init__.py
Should look like:

setup.py
pyproject.toml
/python_project
/python_project/__init__.py (blank, in python_project folder)

Then, add an editable install by running in the command line: 
> pip install -e .


File descriptors:
- setup.py: running this will recognize the python_files package that I carry around via recognition of __init__.py, which should be blank and in the python files directory. Add it with:
 touch python_files/__init__.py
